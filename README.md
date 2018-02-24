
This application is a simple desktop Bitcoin wallet that has the following features:

* _Simplified payment verification_, so it syncs directly from the peer to peer network.
* It's a BIP 32 hierarchical deterministic wallet.
* Supports backup/restore from 12 "wallet words" in the standard fashion as seen in Hive, BreadWallet, etc.
* Password encryption (scrypt)
* Cross platform JavaFX app that can be bundled into native Mac/Win/Linux packages
* Twitter Bootstrap style theming, some nice animations
* QR codes
* Bundled Tor client
* Can run on main network, testnet, local regtest mode etc.

It is not designed to be used directly. Instead it's meant to be forked by developers and used as a base for the 
development of real wallets. A great use case is to build contract based apps. It's been used as the foundation of:

* Lighthouse, a crowdfunding wallet
* Bitcoin Authenticator, a wallet that supports two-factor auth
* BitSquare, a decentralised Bitcoin exchange
* ... and more

# How to use with Bitcoinrwj
* Build [bitcoinrwj](https://github.com/spl0i7/bitcoinrwj) core jars
* Assuming you're using Intellij Idea, Open this project.
* Right Click Project -> Open Module Settings -> Libraries -> Click "+" -> Add Newly built bitcoinrwj core jars
* Build the project

