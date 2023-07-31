# MY OWN TOKEN NINJA HOTHORI
This repository is made for my ethereum beginner project which is used to create MY TOKEN using contracts

## Problem Statement

create a contract together to fulfill the following requirements:

1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. Your contract will have a mapping of addresses to balances (address => uint)
3. You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
5. Lastly,  burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Description
This program  written in Solidity by using a simple contract, solidity is  a programming language used for developing smart contracts on the Ethereum blockchain.
This contract with name MyToken has 3 public access variable that contain (Token Name,Token Abbreviation and Total supply).
Then in the next step  we mapped address into balances.
Then we use a Function with name Mint that increase the total supply and  increases the balance of the (sender) address by that amount.
Then we use  burn function to burn the balance and subtract the burn amount from total_supply and balances of the address provided.
Here,  we  have to provided a if statement to check balance is greater than the value to be burnt, if balance is less than value than the further code will not execute.




## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at (https://remix.ethereum.org/.)

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken1" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by passing the address. call any of the three function and set the value, and you can burn, mint or check the balance of your NFT.

## Author
Ashish

## License

This project is licensed under the [MIT License] (LICENSE)
