
# Blockchain and Web3: Notes

## Blockchain and Bitcoin
Bitcoin is one of the earliest applications of blockchain technology. The original **Bitcoin Whitepaper**, authored by **Satoshi Nakamoto**, introduced a decentralized peer-to-peer transaction system that uses cryptography. Bitcoin’s fixed supply and resistance to censorship has led it to be referred to as *digital gold* and a secure store of value.

## Ethereum and Smart Contracts
Ethereum extends the utility of blockchain beyond digital currency. It enables decentralized applications (dApps) and organizations through **smart contracts**—self-executing programs that run on the blockchain without requiring intermediaries. Although the idea of smart contracts originated in 1994 (by Nick Szabo), Ethereum brought them into practical use.

Smart contracts execute logic in a decentralized and trust-minimized way. Unlike Bitcoin, Ethereum is **Turing complete**, meaning it supports full programming capabilities. Bitcoin also supports smart contracts, but in a **Turing-incomplete** manner, limiting their complexity for security purposes.

## The Oracle Problem
Smart contracts operate deterministically within the blockchain but lack native access to real-world data. This creates the **Oracle Problem**—a challenge in bringing external data into on-chain environments.

**Oracles** act as data bridges between the blockchain and external systems. Centralized oracles can reintroduce trust and single points of failure, so **decentralized oracle networks** are preferred for maintaining trust minimization. This structure gives rise to **hybrid smart contracts**, which combine on-chain logic with off-chain data.

## Chainlink
Chainlink is a decentralized oracle network that facilitates secure external data feeds and computation for smart contracts. It is **blockchain-agnostic**, meaning it can serve multiple chains beyond Ethereum.

## Layer 2 Scaling Solutions
As network usage grows, scalability becomes a major concern. **Layer 2 (L2)** solutions are secondary frameworks or protocols that operate on top of Layer 1 blockchains to improve throughput and reduce fees. Two common types are:

- **Optimistic Rollups**: e.g., Optimism, Arbitrum  
- **Zero-Knowledge (ZK) Rollups**: e.g., ZKsync, Polygon zkEVM

These solutions bundle transactions off-chain and settle the results back on-chain.

## Terminology Overview
- **Blockchain**: A distributed ledger system that records transactions in an immutable, decentralized way.  
- **Oracle**: A bridge that feeds external data to smart contracts.  
- **Layer 2**: Scaling systems built atop base-layer blockchains.  
- **Dapp**: A decentralized application running on a blockchain, governed by smart contracts.  
- **Smart Contract**: A self-executing code that enforces agreements on-chain without intermediaries.  
- **Hybrid Smart Contract**: Combines on-chain logic with off-chain data via oracles.  
- **Ethereum / EVM**: A blockchain platform and its virtual machine that enables smart contract execution and decentralized app development.

## Web3
Web3 represents a shift in internet architecture, transitioning from centralized control to decentralized, user-owned systems. It emphasizes permissionless access, censorship resistance, and composability.

- **Web1**: Static, open-source content  
- **Web2**: Centralized platforms with user-generated dynamic content  
- **Web3**: Decentralized, programmable internet where users interact with trust-minimized protocols and can own parts of the platforms they use

## Summary
Blockchain enables decentralized recordkeeping. Bitcoin introduced the concept of digital, censorship-resistant currency. Ethereum expanded blockchain capabilities with programmable smart contracts. While powerful, smart contracts require external data—hence the need for oracles. Layer 2 solutions help scale these ecosystems. Web3, built on these components, defines the emerging era of the decentralized internet.
