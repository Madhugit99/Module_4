# MovieToken 

Welcome to the MovieToken smart contract! This contract allows you to create and manage tokens for movie-related activities. Below is a simple guide to get you started:

## Overview

MovieToken is a Solidity smart contract that enables basic token operations such as minting, redeeming, burning, and transferring.

## Features

1. **Minting Tokens:** The contract owner can create new tokens and assign them to specific addresses.
2. **Redeeming Tokens:** Users can exchange tokens for specific types of rewards, ensuring the token type is valid and they have enough balance.
3. **Burning Tokens:** Users can reduce their token balance by burning a certain amount of tokens.
4. **Transferring Tokens:** Users can send tokens to other addresses.

## Token Types

MovieToken supports two types of tokens:
- PremiumToken
- RegularToken

## Functions

1. **Deployment:**
   - Deploy the contract, providing an initial owner address.

2. **Minting Tokens:**
   - Use the `mintTokens` function to create and assign tokens to a specific address.

3. **Redeeming Tokens:**
   - Use the `redeemToken` function to exchange tokens for rewards, specifying the token type and the quantity.

4. **Burning Tokens:**
   - Use the `burnTokens` function to reduce the token balance by burning a certain amount.

5. **Transferring Tokens:**
   - Use the `transferTokens` function to send tokens to another address.

## Example Usage

1. **Mint Tokens:**
   - Mint 100 tokens for a user: `mintTokens(userAddress, 100)`

2. **Redeem Tokens:**
   - Redeem 50 PremiumTokens: `redeemToken("PremiumToken", 50)`

3. **Burn Tokens:**
   - Burn 25 tokens: `burnTokens(25)`

4. **Transfer Tokens:**
   - Transfer 30 tokens to another user: `transferTokens(anotherUserAddress, 30)`

## License

This smart contract is licensed under the MIT License.

## Author 
Madhu 

mvmati99@gmail.com
