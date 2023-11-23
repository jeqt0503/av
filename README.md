# Functions and Error Smart Contract

## Overview

Functions and error is the solidity smart contract which implements the basic funtionalities of the minting and burning token. The public variables, mapping structure and events for the token's minting and burning are the features of the solidity smart contract.

## Contract Details

### Public Variables

- `n`: The name of the token.
- `s`: The symbol of the token.
- `tSupply`: The total supply of the token.

### Mapping

- `balances`: A mapping that associates addresses with token balances.

## Functions

### Constructor

The one that initializes the variables "name" and "symbol" is the constructor.


### Mint Function

The mint function allows the users to mint which means add new tokens. It also checks for positive amounts and should avoid overflow.

### Burn Function

The function burn is used for a burning which means subtracting the amount of tokens with a check for excessive amounts.
