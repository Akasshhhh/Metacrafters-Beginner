
# **MyToken Solidity Contract**

## Overview
The MyToken Solidity contract is a simple token contract for Ethereum. It features minting and burning functionality along with balance tracking for addresses. The contract follows ERC-20 standards and provides fundamental token management features.

## Functionality

#### 1. Token Details:
Public variables store token information, including name, abbreviation, and total supply.

#### 2. Balances Mapping:
Addresses are linked to token balances via a public mapping for transparency.

#### 3. Mint Function:
The mint function creates tokens. It increases total supply and balances for an address.

#### 4. Burn Function:
The burn function destroys tokens. Total supply and address balance are reduced, respecting sender balance.

## Usage

### Deploy Contract:

Deploy the MyToken contract on Ethereum using Remix.

### Mint Tokens:

Call mint with an address and token value. Total supply and balance increase.

### Burn Tokens:

Utilize burn to destroy tokens. Provide address and value. Sender balance must be sufficient.

## License

This project is licensed under the MIT License.

