
# MyToken Smart Contract

## Overview

The `MyToken` smart contract is a basic Solidity contract designed to manage a simple cryptocurrency token. It allows for minting (creating) and burning (destroying) tokens for specified addresses. This README provides an overview of the contract and its functionalities.

## Contract Variables

1. `_tokenName`: A public string variable representing the name of the token. In this example, it's set to "Pankaj."

2. `_tokenAbbrv`: A public string variable representing the token's abbreviation. In this example, it's set to "Sharma."

3. `_totalSupply`: A public uint variable representing the total supply of the token. It's initialized to 0.

4. `bal`: A public mapping variable that associates Ethereum addresses with token balances. This mapping is used to keep track of the token balances for various addresses.

## Functions

1. `mint(address Addr, uint Value)`: This function allows the minting (creation) of new tokens and assigns them to a specified address. It increases the total supply (`_totalSupply`) and updates the balance in the `bal` mapping for the specified address.

2. `burn(address Addr, uint Value)`: This function allows for the burning (destruction) of tokens from a specified address. It checks if the address has a sufficient balance to burn the specified number of tokens and then updates the total supply and balance accordingly.


```
