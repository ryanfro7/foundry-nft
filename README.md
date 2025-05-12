# My Solidity NFT Learning Project

This repository documents my journey learning Solidity and Foundry through the Cyfrin Updraft Advanced Foundry Course. Special thanks to [Patrick Collins](https://github.com/PatrickAlphaC) for creating an incredible learning resource, and to [Engrpips](https://github.com/Engrpips) for their invaluable help with test implementations.



## 🚀 My Learning Journey

In this project, I'm exploring the world of Non-Fungible Tokens (NFTs) by creating two different types of NFTs:

1. An IPFS Hosted NFT 
2. An SVG NFT (Hosted 100% on-chain)

## Prerequisites

To follow along with my learning path, you'll need:

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [foundry](https://getfoundry.sh/)

## Quick Start

```bash
git clone https://github.com/[YourUsername]/foundry-nft-learning
cd foundry-nft-learning
forge install
forge build
```

## Key Learning Objectives

- Understand NFT creation mechanisms
- Learn Solidity smart contract development
- Explore Foundry testing and deployment techniques
- Implement on-chain and IPFS-based NFT strategies

## Usage Commands

```bash
# Start a local blockchain node
make anvil

# Deploy contracts
make deploy

# Run tests
forge test

# Check test coverage
forge coverage
```

## Deployment to Testnet

1. Set up environment variables in `.env`
2. Get testnet ETH from [faucets.chain.link](https://faucets.chain.link/)
3. Deploy your NFTs:

```bash
# IPFS NFT Deployment
make deploy ARGS="--network sepolia"

# SVG NFT Deployment
make deploySvg ARGS="--network sepolia"
```

## Acknowledgments

A huge thank you to:
- [Patrick Collins](https://github.com/PatrickAlphaC) - Course Creator
  - [![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/PatrickAlphaC)
  - [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCn-3f8tw_E1jZvhuHatROwA)

- [Engrpips](https://github.com/Engrpips) - Test Implementation Support

## Support the Community

If you found this helpful, consider supporting the original creators:

ETH Address: 0x9680201d9c93d65a3603d2088d125e955c73BD65

## Learning Resources

- [Cyfrin Updraft](https://updraft.cyfrin.io/)
- [Foundry Documentation](https://book.getfoundry.sh/)

## 🌟 Happy Learning! 🌟
