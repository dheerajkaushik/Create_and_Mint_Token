#  Token (DK) README

## Introduction

This repository contains the Solidity smart contract code for the  token, an ERC-20 compatible token designed for various purposes. This tokens can be used for transactions, rewards, and other activities.

## Contract Details

The Token.sol file contains the source code for the token contract. Here are the key details of the contract:

- Token Name: Dheeraj Token
- Token Symbol: DK
- Decimals: 18
- Total Supply: 0 (initially)

The contract includes standard ERC-20 functions such as balanceOf and transfer. 

It also includes functionalities for minting and burning tokens, accessible only by the contract owner.

The contract owner has right to to mint new tokens. Other addresses can interact with the contract by transferring tokens and burning their own tokens.

## Deployment on Local Hardhat Test Network:-


1. Clone the repository and install its dependencies:

```

git clone https://github.com/dheerajkaushik/Create_and_Mint_Token.git
npm install
```

2. Install the `@remix-project/remixd` dependency to connect Remix IDE:

```
npm install -g @remix-project/remixd
```

3. Run the following command in the terminal to connect Remix IDE to the Hardhat local host:

```
remixd -s ./ --remix-ide https://remix.ethereum.org
```

4. Open a new terminal and start Hardhat's testing network:

```
npx hardhat node
```

5. Open the [Remix](https://remix.ethereum.org/) online IDE in your browser.

6. In the file explorer in the workspace, select "localhost" to connect to the local Hardhat network.

7. Rewrite the (Token.sol) file in the contracts directory with your RUK token contract code.

8. Compile the contract in the Remix IDE.

9. Select the environment as "Dev-Hardhat Provider".

10. Deploy your contract on the local Hardhat network using the deploy button in Remix.

11. Confirm the deployment transaction in Remix.

12. Wait for the deployment transaction to be confirmed on the local Hardhat network.

13. Once the contract is deployed, you will see the contract address in the Remix console.

## Interacting with the Contract using Remix with Hardhat Provider

1. In the "At Address" input field, enter the contract address obtained during deployment.

2. Click the "At Address" button to load the contract instance.

3. You can now interact with the RUK token contract through the provided functions.

   - Use the (balanceOf) function to check the token balance.
   - Use the (transfer) function to send tokens from your address to another address.
   - Use the (mint) function (accessible only to the contract owner) to mint

   - Use the (burn) function to burn a specific amount of your tokens.


## Authors

Dheeraj kaushik


