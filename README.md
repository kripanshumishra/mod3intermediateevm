# OpenSkull (OSK) Token

## Overview

OpenSkull (OSK) is a simple ERC-20 token built on the Ethereum blockchain. It is designed to be burnable and has additional ownership functionalities.

## Features

- **ERC-20 Standard:** OpenSkull follows the ERC-20 token standard, making it compatible with various decentralized applications (DApps) and exchanges.
  
- **Burnable:** Users can burn (destroy) their tokens, reducing the total supply. This feature can be useful for deflationary mechanisms.

- **Ownership:** The token includes an ownership structure using the Ownable contract from OpenZeppelin, allowing the owner to perform administrative functions.

## Contracts

- `OpenSkull.sol`: Main contract file that inherits from `ERC20`, `ERC20Burnable`, and `Ownable` contracts.

## Deployment

The contract is deployed with an initial supply, and ownership is assigned to the specified address during deployment.

