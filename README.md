# ukiyo Token (KXO)

## Overview

The ukiyo Token (KXO) is an Ethereum-based ERC-20 token with various features and functionalities. This repository contains the smart contract code for the KXO token, including details on tokenomics, ownership, and tax distribution.

## Token Details

- **Token Name**: Ukiyo Token
- **Token Symbol**: KXO
- **Decimals**: 8

## Features

### Token Distribution

The UKIYO token has a well-defined distribution strategy, including allocations to various stakeholders and team members. The distribution includes allocations for treasury, exchange, IDO sale, IDO partners, strategic partners and advisors, vault, PR wallet, and tax wallet.

### Tax Distribution

The token includes a tax mechanism that distributes a portion of each transaction to different destinations, including treasury, vault, PR wallet, and tax wallet. The tax rates are configurable.

### Vesting

The team members have vesting periods, and the contract includes mechanisms for team members to claim their vested tokens after a specified period.

### Max Transaction Amount

The contract enforces a maximum transaction amount to prevent large transactions that could impact the token's stability.

### Bot Protection

There is an option to enable/disable bot protection to safeguard against undesirable trading activities.

### Exemptions

Certain addresses can be exempted from taxes and other restrictions, allowing for flexibility in managing the token.

## Smart Contract Details

The smart contract code for the KXO token is available in this repository. It is implemented as an ERC-20 token with additional features.

## Deployment

This repository includes the smart contract code but does not contain deployment scripts or configurations. Deployment of the contract was handled separately.

## Security

The code has been reviewed for security, and no sensitive information or private keys are present in this repository. However, it is essential to follow best practices when deploying a clone of the KXO token contract and managing the contract to ensure its security.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This token contract is based on OpenZeppelin Contracts and follows best practices for creating secure and feature-rich ERC-20 tokens on the Ethereum blockchain.

