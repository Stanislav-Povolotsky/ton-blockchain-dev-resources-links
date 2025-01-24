# TON blockchain developer resources

Useful links for TON developer. 
Feel free to add more links and make a pull request. Contribution appreciated.

## TON blockchain

- TON blockchain organization  
  https://github.com/ton-blockchain/
- TON blockchain documentation  
  https://docs.ton.org/  
  Documentation that can answer almost any TON developer question.
- Main TON repo  
  https://github.com/ton-blockchain/ton  
  here you can find the source code of:
  - [TVM](https://github.com/ton-blockchain/ton/tree/master/crypto/vm) (TON Virtual Machine)
  - [validator](https://github.com/ton-blockchain/ton/tree/master/validator) and [liteserver](https://github.com/ton-blockchain/ton/blob/master/validator/impl/liteserver.cpp)
  - [lite-client](https://github.com/ton-blockchain/ton/tree/master/lite-client) client-side library to communicate with TON blockchain
  - [emulator](https://github.com/ton-blockchain/ton/tree/master/emulator) - library to execute smart contracts code offline (without blockchain).
  - [fift](https://github.com/ton-blockchain/ton/tree/master/crypto/fift) - compiler/decompiler/interpreter for [Fift language](https://docs.ton.org/v3/documentation/smart-contracts/fift/overview) (low level stack-based programming language for smart contracts)
  - [FunC](https://github.com/ton-blockchain/ton/tree/master/crypto/func) - compiler for [FunC language](https://docs.ton.org/v3/documentation/smart-contracts/func/overview) (high level language for smart contracts)
  - [simple blockchain explorer](https://github.com/ton-blockchain/ton/tree/master/blockchain-explorer)
  - And a lot of other useful stuff

  [Releases](https://github.com/ton-blockchain/ton/releases) - binary versions of all specified tools, compilers (for Linux, Windows, MacOS)
- TEPs (TON Enhancement Proposals) - a set of standards for the TON blockchain (similar to Bitcoin's BIP or Ethereum's ERC)
  https://github.com/ton-blockchain/TEPs/
  - [TEP-62](https://github.com/ton-blockchain/TEPs/blob/master/text/0062-nft-standard.md) NFT standard
  - [TEP-74](https://github.com/ton-blockchain/TEPs/blob/master/text/0074-jettons-standard.md) Fungible tokens (Jettons) standard
  - [TEP-115](https://github.com/ton-blockchain/TEPs/blob/master/text/0115-ton-connect.md) TON Connect standard for communication protocol between TON wallets and TON (d)apps

## Blockchain explorers

- [TonViewer.com](https://tonviewer.com/) my favorite blockchain explorer with a nice design and a large amount of transaction information. It uses [TonAPI](https://TonAPI.io) API to query all the information about blockchain and transactions and has a button (at right bottom corner) to find out how to you use [TonAPI](https://TonAPI.io) to query all this information as a developer.
- [TonScan.org](https://tonscan.org/) my second favorite blockchain explorer, which I use often use to get more low-level information (like [Blocks](https://tonscan.org/blocks) or [Blockchain configuration](https://tonscan.org/config))
- [TonCoin.org explorer](https://explorer.toncoin.org) most low-level explorer (looks like [simple blockchain explorer](https://github.com/ton-blockchain/ton/tree/master/blockchain-explorer) from ton blockchain source code)

## API

### [TonAPI](http://tonapi.io/)

Most popular API. See [docs](https://docs.tonconsole.com/tonapi).  
This API is designed to provide users with a simple and streamlined experience, eliminating the complexity of the TON blockchain. For instance, you don't need to worry about supporting all wallet standards, performing verifications, or decoding raw bits and bytes. 


### [opentonapi](https://github.com/tonkeeper/opentonapi)

Opentonapi is an open source version of [TonAPI](http://tonapi.io/) and is 100% compatible with it.  
Opentonapi simplifies development of TON-based applications and provides an API centered around high-level concepts like Jettons, NFTs and so on keeping a way to access low-level details.

## Libraries for different programming languages

### JavaScript/TypeScript libraries

ToDO: add

### Python libraries

ToDO: add

### Golang libraries

ToDO: add
