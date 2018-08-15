# Collection of DApps and Smart Contracts for Ethereum

![Screenshot](https://github.com/kozyilmaz/ethereum-dapps/raw/master/docs/wallet-tests.png "Ethereum DApp Development")

## Contents

This repository contains sample DApps and smart contracts and all smart contracts are deployed on Ethereum's **Rinkeby** testnet. [Metamask](https://metamask.io) browser extension is used for testing/development purposes  
Some of the tests may require Metamask/Mist due to account access, however pages like `crc32.html` may be tested just using [Infura](https://infura.io).  
Please check out the `*.js` files in `app` directory, by setting `infuraAPIKey` variable you may execute most of the tests without Metamask/Mist presence  

* Wallet DApp in `app/wallet.*` interfaces with the [NoNameToken, a StandardBurnable ERC20 token smart contract](https://rinkeby.etherscan.io/address/0x0edd6c7576e31a740e7bef46388bf91057631b60#code)
* CRC32 DApp in `app/crc32.*` interfaces with a [IEEE 802.3 compliant CRC32 calculator smart contract](https://rinkeby.etherscan.io/address/0x0f7363cbad2f8d9f63bb64aad5dabaf3f1ff1a0c#code)
* Ethereum connection may be checked using `app/conn.*` files

## HowTo

Please refer to the following step-by-step guides to setup and develop with Truffle  

[How to setup Truffle for macOS and Linux](docs/README.00-truffle.md)  
[How to build Geth on macOS and Linux](docs/README.01-geth.md)
