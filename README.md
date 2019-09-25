# Zilliqa-Node-Starter-Basic
A basic starter for working with the Zilliqa JS SDK at https://github.com/Zilliqa/Zilliqa-JavaScript-Library

## Overview
[Zilliqa](https://zilliqa.com/) is a blockchain network which implements sharding to address scalabliity issues faced by the first generation blockchains such as Bitcoin and Etherium. 

This is a basic Node.js starter project which demonstrates the use of the [official Zilliqa Javascript SDK](https://github.com/Zilliqa/Zilliqa-JavaScript-Library)

In addition to a cryptocurrency ($ZIL), the Zilliqa network offers the ability to create Distributed Applications (DApps) through the use of Smart Contracts, in a similar way to the Etherium network. However, smart contracts on Zilliqa network are written in a specific language called [Scilla](https://scilla-lang.org).

This project operates on Zilliqa's public community testnet, so does not send tokens or currency of any 'real' value, however ***it is your responsiblity to carefully consider the security implications of deploying code on a cryptoraphic network, especially in a production environment. This code is safe for use in a development environment but not suitable for use in a production environment without modification and no liablity is accepted for any losses which may occur.***

The single `index.js` file in this project demonstrates:
- Connecting to a wallet / account on the Zilliqa testnet
- Sending (test) funds to another wallet / account on the testnet
- Deploying a simple HelloWorld smart contract to the testnet
- Updating the data stored by the smart contract
- Querying the updated data / state of the contract

This repo is not an official Zilliqa product.
> The motivation for this repo is to address issues with the 'Quickstart' example for the SDK repo not working out of the box!  

## System requirements and prerequisites
- It is assumed you are a developer with some knowledge of Node.js and ideally the basics of blockchain technology
- You are using a linux / Ubuntu / Debian based system
- You have Node.js installed. This code is only tested with Node version 10.x and known to cause errors with v 12.x.
You can check your node version using:
'$ node -v'
- You have the latest version yarn package manager installed [installation options](prerequisites). It is possible to use npm but this may cause errors.

>**Ideally, you should [Create a new Nucleus Wallet](https://dev-wallet.zilliqa.com/generate) (a Zilliqa devnet wallet)**.
You can 'fund' the wallet by sending testnet tokens from the [ZIL faucet](https://dev-wallet.zilliqa.com/faucet)
You should then replace the private key value in the file 'index.js' with the one from this wallet.
The code should work with the existing private key but this cannot be guaranteed.

## Quickstart

- **Clone this repo and change the project directory**

`$ git clone https://github.com/cloudwheels/Zilliqa-Node-Starter-Basic.git`
`$ cd Zilliqa-Node-Starter-Basic`

- **Ideally replace the private key value in `index.js` with your own**

- **Install dependencies with yarn**

`$ yarn install`

- **Run the project**

`$ node .`

-----

Each network transaction may take some minutes to complete and verify.

You can view transactions on the Zilliqa explorer [Viewblock](https://viewblock.io) (remember to select 'testnet' transactions'
