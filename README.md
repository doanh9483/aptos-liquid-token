
# Aptos Liquid Token

## Overview

Aptos Liquid Token is a decentralized liquid staking solution built on the Aptos blockchain. It enables users to stake their tokens while maintaining liquidity through a wrapped token representation. This project allows users to earn staking rewards without locking their assets, improving capital efficiency and usability.

## Features

-   **Liquid Staking**: Stake Aptos tokens and receive a liquid staking token (LST) in return.
    
-   **Decentralized and Secure**: Utilizes Aptos' secure and scalable blockchain infrastructure.
    
-   **Interoperability**: Easily use LST tokens in DeFi applications.
    
-   **Automated Rewards**: Users receive staking rewards directly in their wallets.
    

## Installation

### Prerequisites

Ensure you have the following installed:

-   Rust
    
-   Move CLI
    
-   Aptos CLI
    

### Setup

1.  Clone the repository:
    
    ```
    git clone https://github.com/doanh9483/aptos-liquid-token.git
    cd aptos-liquid-token
    ```
    
2.  Install dependencies:
    
    ```
    aptos move compile
    ```
    
3.  Deploy the contract:
    
    ```
    aptos move publish --profile default
    ```
    

## Usage

### Staking Tokens

1.  Deposit Aptos tokens into the liquid staking contract.
    
2.  Receive LST tokens representing staked assets.
    

### Unstaking

1.  Redeem LST tokens to unstake Aptos tokens.
    
2.  Withdraw staked assets along with earned rewards.
    

## Contribution

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
    
2.  Create a feature branch.
    
3.  Submit a pull request.
    

## License

This project is licensed under the MIT License.
