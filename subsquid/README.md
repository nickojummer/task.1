Neon Dev Bootcamp – Week 1
Exploring ERC-20-for-SPL Deployment and Cross-Chain Interaction
We started by preparing the development environment. MetaMask was configured to connect to the Neon Devnet, and test funds (NEON and SOL) were obtained from the official faucets to enable transactions on both Neon and Solana networks.

A new Hardhat project was initialized with all required libraries for Ethereum and Solana integration. Network settings were updated to allow deployment directly to Neon Devnet from Hardhat.

Using Neon’s pre-deployed factory contract, we created a Mintable ERC-20-for-SPL token. This step minted a fresh SPL token on Solana and wrapped it in an ERC-20 interface for seamless use in the EVM ecosystem.

To validate cross-chain functionality, we deployed the helper contract TestDevBootcamp.sol. This contract allowed us to build and send Solana-specific instructions directly from Solidity, demonstrating Neon’s composability features.

The workflow also included creating associated token accounts (ATAs) on Solana and testing token transfers between Neon EVM and Solana wallets without leaving the Solidity environment.

Outcome
By the end of this exercise, we gained a solid understanding of how Neon bridges Ethereum and Solana. The ERC-20-for-SPL token was successfully deployed and tested, and we confirmed that Solidity contracts can seamlessly trigger Solana operations.

This project provided hands-on experience with Neon’s composability layer and showed how to build dApps that leverage both ecosystems.