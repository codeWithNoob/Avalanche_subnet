# Avalanche_subnet
## DeFi Kingdom Clone on Avalanche
### Overview
Welcome to DeFi Empire, a thrilling blockchain-based gaming experience where players can collect, build, and battle with their digital assets, earning rewards through various game activities. In this project, we have created a DeFi Kingdom clone on the Avalanche network, combining decentralized finance and gaming into an immersive universe.

## Table of Contents
Prerequisites
Project Steps
Smart Contracts
Usage
Author
License

## Prerequisites
Before you begin, ensure you have the following tools and resources:

Unix computer (MacOS or Linux)
Solidity programming language knowledge
Remix online IDE
Metamask wallet extension
Web browser
## Project Steps
Follow these steps to create your DeFi Kingdom clone on Avalanche:

Set up your EVM subnet: Follow the provided guide and Avalanche documentation to create a custom EVM subnet on the Avalanche network. This enables low-fee deployment of your smart contracts and the creation of a custom token.

Define your native currency: Establish your own native currency, which serves as the in-game currency for your DeFi Kingdom clone. This currency facilitates transactions, rewards, and various in-game activities.

Connect to Metamask: Use the provided guide to connect your EVM Subnet to Metamask. Ensure your custom EVM subnet is selected as the network in Metamask.

Deploy basic building blocks: Leverage Solidity and Remix to deploy foundational smart contracts for your game. These contracts define activities like battling, exploring, and trading. Example contracts provided in the guide:

ERC20 Token Contract
Vault Contract
Test your application: Utilize Remix to interact with your deployed smart contracts. Deploy tokens, liquidity pools, and other components critical to your DeFi Kingdom clone. Test functionalities such as battling, exploring, and trading within your game.

## Smart Contracts
We have deployed two foundational smart contracts for DeFi Empire:

## ERC20.sol
ERC20 Token Contract: This contract implements a standard ERC20 token with functionalities for transfers, allowances, minting, and burning. Players can use this token as an in-game currency.

## Vault.sol
Vault Contract: The Vault contract enables users to deposit and withdraw their tokens while maintaining the total supply and individual balances. This contract serves as the basis for managing liquidity within the game.


## Usage
To start your DeFi Kingdom adventure, follow these steps:

Set up your EVM subnet using the provided guide and Avalanche documentation.

Define your native currency within the game.

Connect your EVM Subnet to Metamask as outlined in the guide.

Deploy the foundational smart contracts using Remix.

Test your DeFi Kingdom clone by interacting with the deployed smart contracts through Remix.

## Author
codeWithNoob


## License
This project is licensed under the MIT License.
