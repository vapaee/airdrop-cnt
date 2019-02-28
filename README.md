<center><h1>Cards & Tokens announces the CNT Tokens Airdrop</h1></center>

<center><img src="https://cdn.steemitimages.com/DQmWLAJ8E1L1L1N4Ga78VRwW6qjSMuF1a9pYTXLkEMUcfHE/airdrop-final.png"></center>


# Vapaée Tokens Smart Contract

As you already know, Vapaée is the company with which I'm going to build many excellent dapps on the Telos network. Cards & Tokens is just the first one of many to come. Each one of this dapps will have its own token and all of them will be allocated in the 'vapaeetokens' smart contract account.  

That smart contract is an adaptation of the basic eosio.token code provided by block.one, adding some features like auto-claim airdrop, token exchange and staking. All in one.

The final code will be open source but is not ready yet. However, I already published a reduced version of this adaptation that contains only what is necessary to perform an airdrop based on the original Telos snapshot. You can find it at
https://github.com/vapaee/airdrop-on-telos  


# Airdrop baseed on TELOS original snapshot

You may also know that Telos Foundation planned this snapshots to facilitate airdrops over its users but a technical issue got in the way... 
To summarize there's no way for me to change the logic (code) that answers to the question of "what's the balance of token XXX for a given account?" because it looks directly to the smart contract "accounts" table of the smart contract, meaning that there's no technical way to "perform" an airdrop without actually incurring in RAM costs (because the balances MUST be allocated in that table).

However the snapshot provided with necessary info to implement a hybrid solution between POORMAN token strategy and a classic airdrop. That solution is what I implemented. It is open source and already available in the mentioned repository. I will be posting again with more details on this issue.

If you wanna know more about the Telos snapshot please check out this trading card with is a prototype of a future album of TELOS.

<center><a href="http://app.cardsandtokens.com/deploy/card/telos-card-06-telos-network-proposals-for-snapshot-and-airdrops" rel="nofollow noopener" title="This link will take you away from steemit.com"><img src="https://steemitimages.com/640x0/https://cdn.steemitimages.com/DQmRGo1yGZnXvAjzLE9V7Uo2bFp6JDsVXLc1YNYs7oH3Grz/telos-card-06-telos-network-proposals-for-snapshot-and-airdrops.png;"></a></center>

# Airdrop

The CNT token was partially executed for all accounts present in the first snapshot (taken on 17 of January) with a balance greater or equals to 100.0000 TLOS. For those who were present in the snapshot but with less tokens, it's possible to claim their tokens by calling the 'claim' action using cleos in the following way:

    cleos --url https://telos.eos.barcelona push action vapaeetokens claim '["accountname","CNT","accountname"]' -p accountname

For more info about the CNT Token itself, please visit http://cardsandtokens.com/token

# Airdrop x2

Last june it was released a <a href="https://steemit.com/eos/@viterbo/cards-and-tokens-announces-airdrop-x2-for-eos-token-holders" target="_blank">special promo</a> in which users may pay 1 EOS Token to participate in a second CNT airdrop.  
Here is the table with the corresponding airdrops.


| Ethereum account   | amount  | tx |
|--------------------|--------:|---:|
| 0x480a42416E2461b93146a34993b1A59eBb9b5942 | 5051.9000 CNT   | <a href="https://telostracker.io/trx/97be18822f6b679049b0048fb9bfd86e3489a32cf438c4efe627f3c0a1bd7ae4">  gqydoobuhege </a> |
| 0xC058f776dD3E8F967A7747Fb411e074832e2F9c6 | 5234.1000 CNT   | <a href="https://telostracker.io/trx/b380984f6db6f11e208defcb45a53be261549e067db41cda6dc86646a5a6f880">  gq4tsojuhege </a> |
| 0xFAACC0bB2cdcA1ba63F9253E0d1b14B9Eea77662 | 5240.7900 CNT   | <a href="https://telostracker.io/trx/33d1eb1a9fe14f2efb6e4e26309c2eace66c1e36716f41045d16b54542797a85">  gm2dsojshage </a> |
| 0x60750b7c635C0c42967BF88c8c87F0Ce93c9D50b | 6216.2600 CNT   | <a href="https://telostracker.io/trx/4f49f3f58355e16679cf0000394c409e3a2f175827f28cf87013c57fe523b49d">  gi2dcnjzgene </a> |
| 0x839dd7995901ba79f48eBe7942b8Ade2caE53978 | 23208.8000 CNT  | <a href="https://telostracker.io/trx/d94e733189bc387f7995ee07e55444003ed19b2fe490d30214d5f1a84bd9ad15">  gqytimzwgige </a> |
| 0xF09F00bBC3ed01ff85356716Db846d4274f50c58 | 5072.3200 CNT   | <a href="https://telostracker.io/trx/32968052a44b1935b23e25edf93be2a1bda89a8b876dc89d3884f0ca9247aa89">  ha3dmmrygyge </a> |
| 0x930E0bc710B67f74AAaD179D49812eDcEDA63a4A | 5400.2400 CNT   | <a href="https://telostracker.io/trx/74d904098f6190a0e78530557a6aaf390c296498a6b8019f1e41c12a55ad2bca">  g43tamztgige </a> |
| 0x52746720d8c1701754dfe4dd3e1fD8d326099301 | 5099.6000 CNT   | <a href="https://telostracker.io/trx/c4ffe950c4cea0d16e02ce424d0a3f1e0343b7a26679a74a54bb3fff8bd07c7c">  guydonrqhage </a> |
| 0x5F52a05B14c92fD0751b20DeADE04E528A13796B | 5166.8200 CNT   | <a href="https://telostracker.io/trx/2b3f0f4a3b3a3b32fc6038fd12586d815527048f4f75aa4f28ea2303f4f73adc">  heydqmzugege </a> |
| 0x56e76a049A9c258723719D1c19474f3B6E90685f | 5080.5500 CNT   | <a href="https://telostracker.io/trx/8e5c97f96896e934e0fa42e886f6ab665be5080d8a09cb582d8c6e1c5fd94ae6">  gy4dcmzqgyge </a> |
| 0x171320Fd0801c038a3ed6728038a05b5736c7814 | 5001.8700 CNT   | <a href="https://telostracker.io/trx/dd6e53a46b8d5a525b13788fbafec5ab65bcc764cdfc5c4792e1c0b2fca1bafe">  heytqmryhege </a> |
| 0x8C06652E95AE7487471Adfc142e336D3f939Df1E | 5049.7900 CNT   | <a href="https://telostracker.io/trx/76fa80380ef77b9b4da82951e244f4f05b16fa358ba2f738e1be0927148fda36">  g44tmnztgage </a> |
| 0xBec98D7be218e251A870bD10c9bA3E0A1acAD700 | 5050.7600 CNT   | <a href="https://telostracker.io/trx/29c9f1f1a2ae45f72f0fccd8f192ef7661dfd0435f6dcd6040452a4757f6671c">  guztemzzgyge </a> |
| 0x92E93ED25a91E7ac6B6E814533764F2E28683482 | 5000.3900 CNT   | <a href="https://telostracker.io/trx/0a23ea387f88571a82cbd10847fddde47395f092dfda8c007bd3cc056a013915">  hezdimjxgage </a> |
| 0xC341F30F1620905b0036f0CEe5D81A954c476C07 | 5047.5800 CNT   | <a href="https://telostracker.io/trx/a053f3397282a274cfbca0292da8edbac21d6957cf7b6eaf7ed883b9265d23b1">  gm4tcnjzgqge </a> |
| 0xD1B4D9793cDEa7C55C04e45bFED9E36A4F8917b3 | 5022.9500 CNT   | <a href="https://telostracker.io/trx/2223519541bbd89ce733370ea722799793be6c73ba8e33da9964988e4bc910af">  gy3tqojwgige </a> |
| 0xb7826b9c8842B39Ed13d2298e6CFd5414b5d1B9c | 5117.7400 CNT   | <a href="https://telostracker.io/trx/8cbe443defe01a6d05acbb4083b9b1507ed6bf53fe37826260bd38fa538e7932">  gy4danzsgige </a> |
| 0x103916E82c97c10BAd900BBcfA0cb0059de88F83 | 5020.3900 CNT   | <a href="https://telostracker.io/trx/219de4be6d9bd55ee7b969dfbd7568e8e719a512a01e856e1277959703b7b7a0">  hezdinryg4ge </a> |
| 0xaeEe3335BeE1EcB9060D73d65BAb9575792f0b95 | 5219.9200 CNT   | <a href="https://telostracker.io/trx/3a751aa52410b57a8ce1faa323478565311707b0ad36756b4fb7522057e3d096">  gq3tqnjxg4ge </a> |
| 0x06Cab99A828dB49841832EC56436a96C46695f26 | 5004.8900 CNT   | <a href="https://telostracker.io/trx/322ee9ac354e2479bbffcd9f12cf98e0960a8833135212c017dc6336b907ed8e">  g42tknzvgege </a> |
| 0x37564161E5618697F8AA99b2D0C09698430Db7F8 | 5090.4400 CNT   | <a href="https://telostracker.io/trx/0e0ad4ededd9e36954d1024f63596d3390cc681859bb65a9f3df13c7eda8e562">  gy3tsnzuhage </a> |
| 0x87d4AbE27A3137E8a3f32AC035f4974A006c00B2 | 5000.3900 CNT   | <a href="https://telostracker.io/trx/d7944a3ffb8748b7fb11174ddc658c3628a2d6af5ee8c860112728a95a2c2252">  hezdsnjshage </a> |
| 0x69832120693fe3020A520AbA4Af358e608326210 | 13389.0000 CNT  | <a href="https://telostracker.io/trx/9f472f9b967c88802815723d3dde2fcc36b3dbaed0f8f1211275fdf35ba55537">  guzdeobugqge </a> |
| 0x74b4A93CC09f899081f328227E20DB17fBF6Cca6 | 5192.3200 CNT   | <a href="https://telostracker.io/trx/2620926e84fd72bec01e11beb3d6e5dce311d667efef945331766f485313df08">  g44tsmzqgege </a> |


# Steemit promo airdrops

During the promo campaign of Cards & Tokens many users participated and received CNT tokens in their Ethereum wallet. Those tokens were replicated in the vapaeetokens smart contract only for the accounts that were registered in the EOS smart contract (meaning those who has been included in the EOS genesis snapshot). Unfortunately not all the ETH accounts were registered in the EOS genesis, so they didn't receive the airdrop yet.

If you are or know someone on the following table that have not received the proper airdrop please let me know. What I need is the current Telos account name to be the airdrop target (just like the other ones).


| account            | amount  | tx |
|--------------------|--------:|---:|
| @devcore           | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xf14F05b4568D94c6c31BE44D53F251759801dab1" target="_blank"> 3000.0000 CNT</a>   | <a href="https://telostracker.io/trx/97bb726472f46096b66f2e510f8ffe05884600ad729fad3cd98f3d80b6f69f42"> gqytkmjygene </a> |
| @bitcoinquest      | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x4543f502cb0962282E41bd65F2667f7a0Ca3BE44" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @yesmin            | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xEF308E49659ea1A0DCCB384c39c01ecF53979DE8" target="_blank"> 7000.0000 CNT</a>   | <a href="https://telostracker.io/trx/e43a06a07a607e855701c3b2a06840b4240216e98f9cb971742a1956bddea57b"> gyytknztgege </a> |
| @emojiet           | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x078603ae44A80e4E6177942D77f17A2b276949e7" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @myjournal         | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xBB314fA9bD4046256b4754A870dB50F5Fb8Aa484" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @perchits          | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x973d80Bf65D06118ed8e9787c7821b69bf7FAc51" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/f7ca4a29a3f6ad72860c86de7080b028c1b079ded05fff779581d3e253b7d76c"> gi3domzygene </a> |
| @sa4van            | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x74BcF6c182B9b2a01d30CC0A405949ab57c774F7" target="_blank"> 3500.0000 CNT</a>   | <a href="https://telostracker.io/trx/bc46d491d89aabe5df79281507cf97e380975a26a54f1ff3661da8945c52f7ef"> gy3tqnjyhage </a> |
| @healaa            | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xd397A799a623C180Bc91989AE774A0854c797663" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @viperblckz        | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x69347cf6a9a596e48667e27b01299ec898ea7cdd" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/10ca54c9f3e22ae22b57170fa025e46e669c846b7de69fb506126954f2b6a2d5"> gi2dkmrwhege </a> |
| @natxlaw           | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x8141c48249B9879dd565BdA9A3E7E02b69ceB34D" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/cdddbdc752cafc7741f3f52f2d805d119fb6b2d76a7ed16744174256d9e27a11"> gy3dcoagenes </a> |
| @shuvomahfuz       | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x224DCf86D7A1818Cc3CB8CF7ADd09dDF3f9ae3C4" target="_blank"> 6000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @mycryptostalker   | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x5a900fFf9D3833C1505cab8241E6FB2a4F1dc70F" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @voluntary-io      | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xdAc2e81999D835eEad986171554d2CBE8711C935" target="_blank"> 7000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @cryptogecko       | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x3A0d032939ff3A7745f2FA2361FC7F5000935616" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @logan1617         | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xdac5876916e9ee712c6d53246b0dcedb39bfb1c9" target="_blank"> 6000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @gcalvete          | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xa30b5e3c8Fee56C135Aecb733cd708cC31A5657a" target="_blank"> 6000.0000 CNT</a>   | <a href="https://telostracker.io/trx/89b567950b80e0a651d8e68a0ce9a55d13ee19917089ce7f32e70cfb6a7b8cdd"> gyztqojtgage </a> |
| @ferfla            | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x17B50871b0d826Cd981d01FaF521Fa9D43812fBD" target="_blank"> 405000.0000 CNT</a> | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @yobana            | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xffE99D62590bcB63C561d682325BfA06BCc39fe2" target="_blank"> 6000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @silent-ghost      | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xDD3de350EF20D33210ef563e27521614abba4294" target="_blank"> 8000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @samstickkz        | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xad787485655550dA5c493Bc712B85A4548a8DEf9" target="_blank"> 5000.0000 CNT</a>   | <a href="https://telostracker.io/trx/adee68bba8977d3454fd8f8885f25ecbeeefccd4298b479689ab52e9fcaf664c"> haydanbvgege </a> |
| @beesteem          | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x52746720d8c1701754dfe4dd3e1fD8d326099301" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/7371b0a8f31b5b348fdf6a4c2276cde075dd987b2143e56992749d1e1c6d86fa"> guydonrqhage </a> |
| @dalexx            | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xE3347F8E662583d6EEeE6C3117a7ddDacE070984" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/d4d1dd9b6f8fb7655af0239a6d9d1494edef4b467d0715374aeec222e5978da7"> ha2tmnzrguge </a> |
| @excy4yaweh        | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xF8CCCb38863Ba4861669Cf54c9535DA474d14847" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @wellnessguy       | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x8F71012Aa45D7016d9185224A8fA6ca260524602" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @scooter77         | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x1164Ef6eAc4fBacB1BC748D6954e4a72d1c95d73" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/0ecc555c810551797ce66e4578e1be1844f6b4d7772b24f8f1199831238c1e82"> geytkmbwgyge </a> |
| @kingyus           | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xAb209A212db3BA9630026e5f82F83BD7fd6c2D55" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @pairmike          | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xda1343d66d39e89322b7b5af6635cc2e9b2d5065" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/1da5fccbf07d4c2221a55a1ebb37d1b6c842299b7a953215662c0739778b3a94"> geztiojtg4ge </a> |
| @wakeupworldnews   | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xfaacc0bb2cdca1ba63f9253e0d1b14b9eea77662" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/ec7596c0e70adc139cd99ed3dfeb80b0395f2ed342ec51cc0319d538dc227bd0"> gm2dsojshage </a> |
| @amberlamps        | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x785aC98c0a95d996Cb1F3e3F42EF93EEFdfbED4e" target="_blank"> 3000.0000 CNT</a>   | <a href="https://telostracker.io/trx/14ad875e9460871d220867c4a71e9ed5958f827a730930607b62897d0d4f928d"> gy4dcmbwgege </a> |
| @deismac           | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xe49441a10338DeE6CBEfA471fDFa1EB3499475A5" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/c7f7f52c6cb6dc71b37e9a627524bb2ea8213e253bcc6ce6505d26722c909c5d"> guzdsmjxhage </a> |
| @radus             | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x8FfEEaA9457f313eDa0B9C53175432cA8dbB2a0b" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/a26ad162b0443597481cfc87c62e2857f39579c075c675ea5d0995824484b643"> haytcmzrhage </a> |
| @scandinavianlife  | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x684b73f413264C1389D30111145936531e43597E" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/5fc6fcd6c228f56d9c18f68be5bf9717f05b5e0e733c6005532d8312a7a4c44e"> guzdsmrugege </a> |
| @satoshibit        | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x62963d29b6442f69ead4410d6544daa97da900c0" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/5efe51e91ec28732b2f4e5bb677d87463e2168fa684d1452b6ed5febb9999e68"> gyztqojshage </a> |
| @stone89son        | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x71E90a070e20999Ed492C8299050B6508424A3b4" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/0a12b91bea59e01d4efc353d365f06d62169c3851497d653a546d2c681235fa4"> gy4domzshage </a> |
| @napkin            | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x60389e3DBdcc9EaE591C028B3342A625Db7b9Ba0" target="_blank"> 2000.0000 CNT</a>   | <a href="https://telostracker.io/trx/b6ecf5be98e07a09efa8ebd2f35ef71f3562a396fbf710046dd3f9cf8bcd08c7"> haydonjyguge </a> |
| @jpederson96       | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0xe33661d331C750ff850D1Ca21b27F903a52B88A3" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/d700a252f267e679c6142581a50143208d937e739bd9b7dcd5c9b825102ba8d0"> ha2tcnjugyge </a> |
| @joooc             | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x413c8dE1eaD694520423B0603411fc5d4D7237D8" target="_blank"> 2000.0000 CNT</a>   | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @leejy             | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x60750b7c635C0c42967BF88c8c87F0Ce93c9D50b" target="_blank"> 2000.0000 CNT</a>   | <a href="https://telostracker.io/trx/1161a5031f60d46b63b361177250ce5abc65bc76d0d595ab5c30c757ce78e4e0"> gi2dcnjzgene </a> |
| @andrew88          | <a href="https://etherscan.io/token/0xf5943eaa87a71a29013666ecd84a83af4ae2ecfc?a=0x5433DcD85904a83883AE7d698Ea4E05E782D7DdF" target="_blank"> 1000.0000 CNT</a>   | <a href="https://telostracker.io/trx/4f04f916195b582874b31299edfbce4d7f7e5382eec9f61304a714ae5e4a700a"> hezdonbwhege </a> |


# Steemit promo airdrops (late registration)

In the same promo campaign there were late registrations that were not attended in that moment. Those accounts have receive a "consolation prize" of 500 CNT that were sent to the corresponding telos account (based on the EOS genesis snapshot).

Again, there were unregistered accounts for the genesis of EOS, so they did not receive this consolation prize. Let me know if you are one of those cases and where (what account) to point to the airdrop.


| account            | Ethereum acount  | tx |
|--------------------|------------------|---:|
| @veteranoftruth    | 0x71c6ff6d3bc3280a5b7c7a4ddcc4ab908e217467 | <a href="https://telostracker.io/trx/97d409ecdb49f3110bd980353538ce483e32f355f9c474d7e4b4fac6192d8333"> guztmnrrg4ge </a> |
| @nijmai            | 0x1Fc76251EA81D473a22ECba8437b843A70F11DBA | <a href="https://telostracker.io/trx/d7b1202dba73ddccdf02a0566ac2481ba619d85fb364140a4f12a84cc0ee941d"> g42tmnrygege </a> |
| @radus             | 0x8FfEEaA9457f313eDa0B9C53175432cA8dbB2a0b | <a href="https://telostracker.io/trx/41e33ec464043ce3a6ea63563ef992f238adc27ceba4790f31688c153bde4c2f"> haytcmzrhage </a> |
| @yepidan           | 0x79e2Dbf7aBE8385767B798A7bfACEf4CA2E93299 | <a href="https://telostracker.io/trx/229f9e62906ca2ef6d163e5a7b87ccd7566e5a850144c3c67c3dbcb29186ec3c"> gu3tmnjygqge </a> |
| @nitego            | 0xbFA9E94B0FA6C05F0b574821BdAee2578aA40197 | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @indend007         | 0x2E26F45D030d5bd4d46B8a8bb571F6d4A1b3a1BF | <a href="https://telostracker.io/trx/08f535c1eb4d3acbe7ad7d1023b371014e17b8d76595d818838d9992cc2aac1a"> guzdsmbygige </a> |
| @drycounty         | 0xa3bB5420C91C5A0dd6FE18B7DEf0f7a9e290AB24 | <a href="https://telostracker.io/trx/0697548a7e46696a41899d951f70964b1189dda7d3ea7c8b4bad20a787c69991"> g43danjsgage </a> |
| @unknown78         | 0xb79798DAFf2F2E1eD9B2d5181f519485D5eF89dc | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @technewbie        | 0x0f62038497c7074e0A4c7092c2CfBBAB28aa7fa5 | <a href="https://telostracker.io/trx/6fff198fcdc9e5aa60920f2f43603387b8f58cd5572d5e0143b8415f6ac45824"> gu2tombtgqge </a> |
| @draceos           | 0xaeEe3335BeE1EcB9060D73d65BAb9575792f0b95 | <a href="https://telostracker.io/trx/87e22b44412960287246b289706dbdb162eedead75454ded03cdb1fe3d574039"> gq3tqnjxg4ge </a> |
| @cryptohorizons    | 0x43624b74eF6BE60e5932B2925E53BDBDc0775F73 | <a href="https://telostracker.io/trx/????????????????????????????????????????????????????????????????"> ???????????? </a> |
| @lover33           | 0x4906E4f95ad546cE865916F65C825e00630bFfa8 | <a href="https://telostracker.io/trx/e4f89d07e039c0cef49492c869f8d3a1927a68721d3d425b994b2a71e66c6983"> gq3timzsgyge </a> |
| @phi2818           | 0x2A90853d49C05Bd79a582234269F59AD64b927DA | <a href="https://telostracker.io/trx/a1fd9cfe82782b18e90f648861a4f8cc170269a7fa1d08c85958256669704608"> gi4tenjsguge </a> |
| @jpederson96       | 0xe33661d331C750ff850D1Ca21b27F903a52B88A3 | <a href="https://telostracker.io/trx/0e0759ae1f7e051b0373db45ba5f77a5fee95b2c16c00edc61036aed92f690fb"> ha2tcnjugyge </a> |
| @yennsth           | 0x???????????????????????????????????????? | <a href="https://telostracker.io/trx/1a7921813eb07687ce7566e2ea32950ada2149d00ad1a78654f4d679d65c8cba"> geytcnjzgmge </a> |

<hr>

# Worker Proposal (coming soon)

Finally, I would like to ask the entire TELOS community to support the worker proposal that I am working on right now. Basically, I would ask for funds to buy RAM for the main smart contract, to prevent users from having to buy memory and be able to use it freely. This will facilitate the adoption of the users.


