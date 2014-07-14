## Programming Bitcoin Reading List and Projects

* The goal of this document is to provide a reading list for learning to program Bitcoin transactions
* The theme of this document is practical and pragmatic instruction with the goal of writing code 

The document is split into two major sections: [Content](#content) and [Code](#code)

* The Content section contains a reading list which emphasizes programming Bitcoin transactions
* The Code section contains a list of open-source bitcoin projects ranging from modern popular tools to early historic implementations
* WIP: please send suggestions to [@eigenjoy](https://twitter.com/eigenjoy) or [open a GitHub issue](https://github.com/jashmenn/bitcoin-reading-list/issues)

### <a name="content"></a>Content

#### Posts
* [Programming Bitcoin Transaction Scripts](https://docs.google.com/document/d/1D_gi_7Sf9sOyAHG25cMpOO4xtLq3iJUtjRwcZXFLv1E/edit) (Kofler)
* [Developer’s Introduction to Bitcoin](http://bitcoinmagazine.com/9249/developers-introduction-bitcoin/) (Buterin)
* [How Bitcoin Works Under the Hood](http://www.imponderablethings.com/2013/07/how-bitcoin-works-under-hood.html) (Driscoll)
* [Bitcoin Developer Guide](http://bitcoindev.us.to/en/developer-guide)
* [Bitcoin Scripts](http://www.bitcoinsecurity.org/2012/07/22/7/) (Koshy)
* [Bitcoins the hard way: Using the raw Bitcoin protocol](http://www.righto.com/2014/02/bitcoins-hard-way-using-raw-bitcoin.html) (Shirriff)
* [Bitcoin mining the hard way: the algorithms, protocols, and bytes](http://www.righto.com/2014/02/bitcoin-mining-hard-way-algorithms.html) (Shirriff)
* [Proving Your Bitcoin Reserves](https://iwilcox.me.uk/2014/proving-bitcoin-reserves) (Maxwell)

#### Tutorials
* [The libbitcoin Tutorial](http://libbitcoin.dyne.org/doc/) (Taaki)
* [How to Parse the Bitcoin Blockchain](http://codesuppository.blogspot.com/2014/01/how-to-parse-bitcoin-blockchain.html) (Ratcliff)
* [How to extract every single bitcoin transaction from the blockchain and save it to an ASCII comma separated text file](http://codesuppository.blogspot.com/2014/03/how-to-extract-every-single-bitcoin.html) (Ratcliff)
* [How To Clone Scrypt Based Altcoins for Fun and Profit](http://devtome.com/doku.php?id=scrypt_altcoin_cloning_guide&rev=1391981820) (shakezula)
* [Signing Offline Transactions](https://gist.github.com/jashmenn/9811205) (Maxwell)
* [2 of 2 escrow example](https://gist.github.com/jashmenn/9811198) (Maxwell)
* [2 of 3 multisig example](https://gist.github.com/jashmenn/9811185) (Andresen)
* [How to decrypt messages in the blockchain from btcmsg](https://gist.github.com/ripper234/1625828) (ripper234)

#### Papers
* [Original bitcoin paper](https://bitcoin.org/bitcoin.pdf) (Satoshi)
* [Annotated bitcoin paper](http://news.rapgenius.com/Satoshi-nakamoto-bitcoin-a-peer-to-peer-electronic-cash-system-annotated) (Satoshi / Rap Genius Community)
* [Proof of Ownership](http://frozenlock.files.wordpress.com/2011/11/master-bitcoin.pdf) (Fortin)
* [Colored Coins](https://bitcoil.co.il/BitcoinX.pdf) (Rosenfeld)

#### Specifications
* [BIP70: Payments Protocol](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) (Andresen)
* [Working with the Payments Protocol](https://code.google.com/p/bitcoinj/wiki/PaymentProtocol) (Andresen)
* [BIP32: Hierarchical Deterministic (HD) Wallets](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki) (Wuille)
* [BIP32 Implementation: Money Tree HD Wallet](https://github.com/BitVault/money-tree) (BitVault)
* [Deterministic Wallet](https://en.bitcoin.it/wiki/Deterministic_wallet)
* [Technical background of version 1 Bitcoin addresses](https://en.bitcoin.it/wiki/Technical_background_of_Bitcoin_addresses)
* [Transactions Reference](https://en.bitcoin.it/wiki/Transactions)
* [Script Reference](https://en.bitcoin.it/wiki/Script)
* [Raw Transactions API](https://en.bitcoin.it/wiki/Raw_Transactions)
* [Colored Coins Protocol Specification](https://github.com/Flavien/colored-coins-protocol/blob/master/specification.mediawiki) (Flavien)
* [The Mastercoin Protocol Specification](https://github.com/mastercoin-MSC/spec) (Gross)
* [Counterparty: Financial Instruments (Announcement)](https://bitcointalk.org/index.php?topic=395761.0)

#### Discussion
* [There Is No 'From' Address](https://iwilcox.me.uk/2014/no-from-address) (iwilcox)
* [Disentangling Crypto-Coin Mining: Timestamping, Proof-of-Publication, and Validation](http://www.mail-archive.com/bitcoin-development%40lists.sourceforge.net/msg03307.html) (Todd)
* [Double-spending unconfirmed transactions is a lot easier than most people realise](  http://www.reddit.com/r/Bitcoin/comments/239bj1/doublespending_unconfirmed_transactions_is_a_lot/) (Todd)
* [Replace-by-fee scorched-earth without child-pays-for-parent](http://www.mail-archive.com/bitcoin-development%40lists.sourceforge.net/msg05211.html) (Todd / Anonymous)

#### Videos
* [Programming Bitcoin Youtube Channel](https://www.youtube.com/programmingbitcoin) (Murray)
* [How Bitcoin Works Under the Hood](https://www.youtube.com/watch?v=Lx9zgZCMqXE) (Driscoll)
* [Coding Multi-Signature Addresses](https://www.youtube.com/watch?v=zIbUSaZBJgU) (D'Angelo)

#### API Docs
* [Bitcoin Doxygen](https://dev.visucore.com/bitcoin/doxygen/annotated.html)
* [Original Bitcoin client/API calls list](https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list)

#### Sidechains
* [Tree-chains preliminary summary](http://www.mail-archive.com/bitcoin-development@lists.sourceforge.net/msg04388.html) (Todd)
* [Why do people think that side-chains are going to be secure?](http://www.reddit.com/r/Bitcoin/comments/22vn4m/why_do_people_think_that_sidechains_are_going_to/cgqy5w6) (Maxwell)
* [Discussion on 2-way pegging: is there a way to do bitcoin-staging?](http://sourceforge.net/p/bitcoin/mailman/bitcoin-development/thread/20130519132359.GA12366%40netbook.cypherspace.org/#msg30868065)
* [Sidechains, Treechains, the TL;DR](http://blog.greenaddress.it/2014/06/13/sidechains-treechains-the-tldr/) (Sanders)
* [Sidechains Explained](http://cryptobizmagazine.com/sidechains-explained/) (Payne)
* [Side Chains: The How, The Challenges and the Potential](http://bitcoinmagazine.com/12349/side-chains-challenges-potential/) (Buterin)
* [Sidechain Technical Feasibility Discussion](https://bitcointalk.org/index.php?topic=566704.0;all) (discussion)
* [Alternative Chains / merged mining](https://en.bitcoin.it/wiki/Alternative_Chains) 

#### Beyond Payments
* [Timelock: time-release encryption incentivised by Bitcoins](http://www.mail-archive.com/bitcoin-development%40lists.sourceforge.net/msg05547.html) (Todd / Taaki)
* [Decentralized digital asset exchange with honest pricing and market depth](http://www.mail-archive.com/bitcoin-development%40lists.sourceforge.net/msg03892.html) (Todd / Mizrahi)


### <a name="code"></a>Code

#### Core
* [bitcoin](https://github.com/bitcoin/bitcoin) `C++` (Satoshi) 
* [bitcoinj: Java implementation of a Bitcoin client-only node](https://code.google.com/p/bitcoinj/) `Java` (bitcoinj)
* [bitcoin-qt: Qt GUI for C++ Bitcoin client](https://github.com/laanwj/bitcoin-qt) `C++` (laanwj)
* [bitcoinjs-lib: Bitcoin-related functions implemented in pure JavaScript](https://github.com/bitcoinjs/bitcoinjs-lib) `JavaScript` (bitcoinjs)
* [btcd: alternative full node bitcoin implementation written in Go](https://github.com/conformal/btcd) `Go` (conformal)
* [bitcore: interface to the bitcoin network](http://bitcore.io/) `Javascript` (BitPay)
* [cbitcoin low-level bitcoin library in standard C](https://github.com/MatthewLM/cbitcoin/) `C` (Mitchell)
* [btcwire: Implements the bitcoin wire protocol - core wire protocol package from btcd](https://github.com/conformal/btcwire) `Go` (conformal)

#### Tools
* [pybitcointools: SImple, common-sense Bitcoin-themed Python ECC library](https://github.com/vbuterin/pybitcointools) `Python` (vbuterin)
* [bitcointools: Python-based tools for the Bitcoin cryptocurrency system](https://github.com/gavinandresen/bitcointools) `Python` (gavinandresen)
* [cryptocoin: Python module for working with cryptocurrencies](https://github.com/lyndsysimon/cryptocoin) `Python` (lyndsysimon)
* [bitcoin-ruby: bitcoin utils and protocol in ruby.](https://github.com/lian/bitcoin-ruby) `Ruby` (lian)
* [pycoin: Python-based Bitcoin utility library.](https://github.com/richardkiss/pycoin) `Python` (richardkiss)
* [bitcoin-testnet-box: Create a private, difficulty 1 bitcoin testnet](https://github.com/freewil/bitcoin-testnet-Box) `Shell` (freewil)
* [mastercoin-tools](https://github.com/grazcoin/mastercoin-tools) `Javascript` (grazcoin)

#### Non-currency Applications
* [dissent: decentralized, transferable, and open software license system using the Bitcoin protocol](https://github.com/aaron-lebo/dissent) `Python` (Lebo)

#### Beyond Payments
* [paypub: Trustless payments for information publishing on Bitcoin](https://github.com/unsystem/paypub) `C++` (Taaki / Todd)

#### Miners
* [poclbm: PyOpenCL bitcoin miner](https://github.com/m0mchil/poclbm) `Python` (m0mchil) 
* [DiabloMiner: OpenCL miner for Bitcoin](https://github.com/Diablo-D3/DiabloMiner) `Java` (Diablo-D3)
* [cpuminer: CPU miner for bitcoin](https://github.com/jgarzik/cpuminer) `C` (jgarzik)
* [Open-Source-FPGA-Bitcoin-Miner: Bitcoin Miner for Altera FPGAs](https://github.com/progranism/Open-Source-FPGA-Bitcoin-Miner) `Verilog` (progranism)
* [jsMiner: A Javascript Bitcoin miner](https://github.com/jwhitehorn/jsMiner) `JavaScript` (jwhitehorn)
* [pyminer: Python miner for bitcoin](https://github.com/jgarzik/pyminer) `Python` (jgarzik)
* [Bitcoin-JavaScript-Miner: A Bitcoin miner implemented in JavaScript.](https://github.com/progranism/Bitcoin-JavaScript-Miner) `JavaScript` (progranism)
* [cellminer: Bitcoin miner for the Cell Broadband Engine Architecture](https://github.com/verement/cellminer) `C` (verement)
* [oclminer: OpenCL bitcoin miner](https://github.com/tcatm/oclminer) `C` (tcatm)
* [Phoenix-Miner: Modular, fast, efficient Bitcoin miner](https://github.com/jedi95/Phoenix-Miner) `Python` (jedi95)
* [tumen_miner: An experimental BitCoin miner, which uses WebCL](https://github.com/temujin9/tumen_miner) `PHP` (temujin9)
* [Minimal-Bitcoin-Miner: CPU based Bitcoin Miner in C#](https://github.com/lithander/Minimal-Bitcoin-Miner) `C#` (lithander)

#### Wallets
* [coinpunk: self-hosted Bitcoin wallet service](https://github.com/kyledrake/coinpunk) `Javascript` (kyledrake)
* [termcoin: A bitcoin wallet for your terminal](https://github.com/chjj/termcoin) `Javascript` (chjj)
* [pywallet: bitcoin wallet importer/exporter](https://github.com/joric/pywallet) `Python` (joric)
* [Hive: Bitcoin wallet for OS X](https://github.com/hivewallet/hive-osx) `Objective-C` (jsuder)
* [bitaddress.org: JavaScript Client-Side Bitcoin Wallet Generator](https://github.com/pointbiz/bitaddress.org) `Javascript` (pointbiz)
* [Multibit: desktop bitcoin client, powered by bitcoinj](https://github.com/jim618/multibit) `Java` (jim618)
* [bitcoin-wallet: A new kind of Bitcoin client](https://github.com/elis/bitcoin-wallet) `Python` (elis)
* [picocoin: A small bitcoin client](https://github.com/jgarzik/picocoin) `C` (jgarzik)
* [sx: sx - command line Bitcoin to empower the sysadmin](https://github.com/spesmilo/sx) `Python` (spesmilo)
* [Safebit: Chrome app wallet](https://github.com/elis/Safebit) (elis)
* [Bitcoin-akka: a client to btcwallet, written in Scala and built on akka](https://github.com/goldmar/bitcoin-akka/) (goldmar)

#### Clients
* [libbitcoin: libbitcoin asynchronous C++ library for Bitcoin](https://github.com/spesmilo/libbitcoin) `C++` (spesmilo)
* [electrum: Bitcoin thin client](https://github.com/spesmilo/electrum) `Python` (spesmilo)
* [BitcoinArmory: Python-Based Bitcoin Software](https://github.com/etotheipi/BitcoinArmory) `Python` (etotheipi)
* [bitcoin-js-remote: Javascript remote for bitcoind](https://github.com/tcatm/bitcoin-js-remote) `JavaScript` (tcatm)
* [bitcoinjs-gui: Bitcoin client implementation in HTML5/JavaScript](https://github.com/bitcoinjs/bitcoinjs-gui) `JavaScript` (bitcoinjs)
* [bitcoin-php: Bitcoin library for PHP](https://github.com/mikegogulski/bitcoin-php) `PHP` (mikegogulski)
* [bitcoin-python: Friendly bitcoin API binding for Python](https://github.com/toomanysecrets0/bitcoin-python) `Python` (toomanysecrets0)
* [python-bitcoinrpc: Python interface to bitcoin's JSON-RPC API](https://github.com/jgarzik/python-bitcoinrpc) `Python` (jgarzik)
* [bitcoinjs: Bitcoin client library in JavaScript using Node.js / MongoDB](https://github.com/bitcoinjs/bitcoinjs-server/) `javascript` (justmoon)
* [caesure: Python Bitcoin Client](https://github.com/samrushing/caesure) `Python` (samrushing)
* [chrome-bitcoin: bitcoin client in chrome](https://github.com/kiba/chrome-bitcoin) `JavaScript` (kiba)
* [node-bitcoin: Communicate with bitcoind via JSON-RPC](https://github.com/freewil/node-bitcoin) `JavaScript` (freewil)
* [gocoin: Bitcoin client library for Go / golang](https://github.com/piotrnar/gocoin) `Go` (piotrnar)
* [python-bitcoinlib: Bitcoin library](https://github.com/petertodd/python-bitcoinlib) `Python` (petertodd)
* [cbitcoin: A low-level bitcoin library written in standard C.](https://github.com/MatthewLM/cbitcoin) `C` (MatthewLM)
* [GoBit: A Golang implementation of Bitcoin](https://github.com/ThePiachu/GoBit) `Go` (ThePiachu)
* [Protocoin: A pure Python Bitcoin protocol implementation](https://github.com/perone/protocoin) `Python` (perone)
* [BitcoinLib: C# Bitcoin, Litecoin and Bitcoin-Clones Library & RPC Wrapper](https://github.com/GeorgeKimionis/BitcoinLib) `C#` (GeorgeKimionis)

#### Mobile
* [bitcoin-wallet: Bitcoin Wallet app for your Android device](https://github.com/schildbach/bitcoin-wallet) `Java` (schildbach)
* [bitcoinApp: bitcoin for iOS devices](https://github.com/udibr/bitcoinApp) `Objective-C` (udibr) 
* [bitcoin-android: Send and receive bitcoins from your Android phone](https://github.com/barmstrong/bitcoin-android) `Java` (barmstrong)
* [bitcoin-mobile-android](https://github.com/bitcoin-labs/bitcoin-mobile-android) `Java` (Schaaf)
* [BitcoinDroid: A thin Android client for Bitcoin](https://github.com/opposablebrain/BitcoinDroid) `Java` (opposablebrain)
* [CoreBitcoin: Well-documented Bitcoin implementation in Objective-C](https://github.com/oleganza/CoreBitcoin) `C` (oleganza)
* [wallet: Mycelium Bitcoin Wallet for Android](https://github.com/mycelium-com/wallet) `Java` (mycelium-com)
* [BitcoinKit: Cocoa framework for creating Bitcoin wallet apps](https://github.com/hivewallet/BitcoinKit) `C` (hivewallet)
* [BTCSquared: iOS framework for Bluetooth LE transactions](https://github.com/Gliph/BTCSquared) `Objective C` (Gliph)

#### Exchanges
* [buttercoin: Opensource Bitcoin Exchange](https://github.com/buttercoin/buttercoin) `Javascript` (buttercoin)
* [QtBitcoinTrader: Secure Multi Trading Client](https://github.com/JulyIGHOR/QtBitcoinTrader) `C++` (JulyIGHOR)
* [BitWasp: Open Source Bitcoin Marketplace Software](https://github.com/Bit-Wasp/BitWasp) `PHP` (Bit-Wasp)
* [bitcoin-central: Bitcoin Central](https://github.com/davout/bitcoin-central) `Ruby` (davout)
* [ZeroReserve: Friend 2 Friend Payment and Bitcoin exchange](https://github.com/zeroreserve/ZeroReserve) `C++` (zeroreserve)
* [benjamin: bitcoin trading bot & analytics platform](https://github.com/mathisonian/benjamin) `JavaScript` (mathisonian)
* [Dark-Exchange: Dark Exchange is a distributed p2p exchange for bitcoin.](https://github.com/macourtney/Dark-Exchange) `Clojure` (macourtney)
* [btcnearme: Find Bitcoin traders near you... settle in cash](https://github.com/famulus/btcnearme) `Ruby` (famulus)
* [bitrated: Bitrated.com - Bitcoin arbitration marketplace](https://github.com/shesek/bitrated) `CoffeeScript` (shesek)
* [intersango: bitcoin exchange](https://github.com/dooglus/intersango) `PHP` (dooglus)
* [bitwrk: A Bitcoin-friendly, Anonymous Marketplace for Computing Power](https://github.com/indyjo/bitwrk) `Go` (indyjo)

#### Merchant Tools
* [BitPay: Bitcoin payment application](https://github.com/warpi/BitPay) `Java` (warpi)
* [bitcoin-wp-e-commerce: Bitcoin payment plugin for WP e-Commerce for WordPress](https://github.com/mikegogulski/bitcoin-wp-e-commerce) `PHP` (mikegogulski)
* [Magento-Bitcoin-Payment-Module: Magento Payment Gateway Plugin for Bitcoin RPC API](https://github.com/jalder/Magento-Bitcoin-Payment-Module) `PHP` (jalder)
* [bitcoin-virtuemart: Bitcoin payment plugin for VirtueMart shopping cart for Joomla!](https://github.com/mikegogulski/bitcoin-virtuemart) `PHP` (mikegogulski)
* [magento-bitcoin: Bitcoin payment module for Magento.](https://github.com/ticean/magento-bitcoin) `PHP` (ticean)
* [Zen-Cart-Bitcoin-Payment-Module: A payment modules to interact with bitcoind for zen cart.](https://github.com/jalder/Zen-Cart-Bitcoin-Payment-Module) `PHP` (jalder)
* [MultiBitMerchant: A free and open source Bitcoin ecommerce platform, with several representative clients](https://github.com/gary-rowe/MultiBitMerchant) `Java` (gary-rowe)

#### Bots
* [Bitcoin arbitrage: opportunity detector](https://github.com/maxme/bitcoin-arbitrage) `Python` (maxme)
* [gekko: A bitcoin trading bot](https://github.com/askmike/gekko) `Node.js` (askmike)
* [Redbit: Automated Bitcoin Trading Bot](https://github.com/hyppo/Redbit) `Python` (hyppo)
* [ArBit: An automated Bitcoin arbitrage trading program.](https://github.com/goteppo/ArBit) `Go` (goteppo)
* [cryptrade: Node.js Bitcoin bot for MtGox/Bitstamp/BTC-E/CEX.IO](https://github.com/pulsecat/cryptrade) `CoffeeScript` (pulsecat)
* [btc-trader: Robot for Bitcoin trading on BTC-e](https://github.com/therussianphysicist/btc-trader) `Ruby` (therussianphysicist)
* [ga-bitbot: Genetic algorithm trade system for bitcoin](https://code.google.com/p/ga-bitbot/) `Python` 

#### Block Exploration
* [bitcoin-abe: Abe: block browser for Bitcoin and similar currencies](https://github.com/jtobey/bitcoin-abe) `Python` (jtobey)
* [insight: A bitcoin blockchain API for web wallets](https://github.com/bitpay/insight) `JavaScript` (bitpay)
* [node-bitcoin-explorer: A Block Explorer clone built using node-bitcoin-p2p](https://github.com/bitcoinjs/node-bitcoin-explorer) `JavaScript` (bitcoinjs)
* [btcplex: BTCplex is an open source Bitcoin block chain browser written in Go, it allows you to search and navigate the block chain.](https://github.com/tsileo/btcplex) `Go` (tsileo)
* [blockparser: Fast, quick and dirty bitcoin blockchain parser](https://github.com/znort987/blockparser) `C++` (znort987)

#### Pooling
* [p2pool: Peer-to-peer Bitcoin mining pool](https://github.com/forrestv/p2pool) `Python` (forrestv)
* [bitcoin-pool: early pooling server](https://github.com/doublec/bitcoin-pool) `C++` (doublec)
* [What is Pool Hopping?](http://bitcoin.stackexchange.com/questions/5072/what-is-pool-hopping) (Perry)
* [bitHopper: A python based poolhopper for bitcoin](https://github.com/c00w/bitHopper) `Python` (c00w)
* [Bitcoin-mining-proxy: Multi-pool, multi-worker proxy for Bitcoin miners ](https://github.com/cdhowie/Bitcoin-mining-proxy) `PHP` (cdhowie)
* [stratum-mining: Demo implementation of Bitcoin mining pool on Stratum protocol](https://github.com/slush0/stratum-mining) `Python` (slush0)

#### Sites
* [petulant-lana: A one-time-payment filehosting site, using Bitcoin](https://github.com/bearbin/petulant-lana) `Go` (bearbin)
* [bitstarter-leaderboard: Bitcoin-powered crowdfunder](https://github.com/startup-class/bitstarter-leaderboard) `Javascript` (Srinivasan)
* [feedopensource: Iteratively Fund Open Source Projects With Bitcoin](https://github.com/dominictarr/feedopensource) `JavaScript` (dominictarr)
* [Bitcoin-Poker-Room: Sources for Bitcoin Poker Room.](https://github.com/hippich/Bitcoin-Poker-Room) `Python` (hippich)
* [BitHub: pay Bitcoin for GitHub commits](https://github.com/WhisperSystems/BitHub) `Java` (WhisperSystems) 

#### Related Protocols
* [bitid: Bitcoin Authentication Open Protocol](https://github.com/bitid/bitid) (Larch)
