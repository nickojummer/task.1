Neon 1
Building Bridges: ERC-20 Wrapped SPL Tokens and Cross-Chain Experiments

We kicked off the week by setting up our tools and environment. MetaMask was linked to Neon’s Devnet, and we pulled NEON and SOL test tokens from the official faucets to allow interaction with both Neon and Solana networks.

Next, we scaffolded a new Hardhat project and added the necessary packages for seamless Ethereum–Solana communication. Configuration files were updated to target Neon Devnet deployments directly from Hardhat.

Leveraging Neon’s deployed factory contract, we issued a mintable ERC-20-wrapped SPL token. This process minted a native SPL asset on Solana, then exposed it via an ERC-20 layer for compatibility with EVM-based applications.

To explore Neon’s composability, we deployed TestDevBootcamp.sol, a helper contract that allowed us to send Solana-native instructions from Solidity. This showcased the power of triggering Solana operations within the EVM runtime.

We also tested the creation of associated token accounts (ATAs) on Solana and validated smooth token transfers between Solana accounts and Neon EVM wallets—all without leaving the Solidity environment.

Key Takeaways
This hands-on session revealed how Neon enables Solidity contracts to orchestrate Solana transactions. We successfully deployed and tested the ERC-20-wrapped SPL token and confirmed bi-directional token flow across the two ecosystems.

This experience demonstrated Neon’s potential for building powerful cross-chain dApps that unite Solana and Ethereum workflows.

