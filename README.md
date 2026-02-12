# Web3 DApp – Smart Contract + Frontend Integration (Monad)

## 📌 Project Overview
This project is a Web3 decentralized application (DApp) deployed on the **Monad Testnet**.  
It integrates a Solidity smart contract with a React-based frontend, enabling users to interact with on-chain data through a clean and minimal interface.

The application demonstrates **full-stack Web3 development**, including:
- Smart contract deployment
- Frontend integration
- Wallet connection
- Transaction handling

---

## 🛠️ Tech Stack
- **Smart Contract:** Solidity  
- **Deployment:** Monad Testnet RPC  
- **Frontend:** React + [Scaffold-ETH](https://github.com/scaffold-eth/scaffold-eth)  
- **Wallet Integration:** MetaMask / Privy / WalletConnect  
- **Libraries:** ethers.js, wagmi hooks  

---

## 🔗 Transaction Details
Monad testnet explorer: https://testnet.monadvision.com/myspace?type=Transactions
A transaction was successfully executed on Monad Testnet:

- **Transaction Hash:**  
  `0x329f448b2d640ba3d1e0078224c72a93617f507d3586dc61864f9523484f2ade`

To verify:
1. Open the Monad Testnet block explorer.  
2. Paste the transaction hash above.  
3. Confirm details such as:
   - Status (Success/Failed)  
   - Block number  
   - Gas used  
   - Contract address (if deployment) or recipient address (if interaction)  

---

## ⚙️ Project Architecture

| Layer              | Tools/Tech                | Purpose                                |
|--------------------|---------------------------|----------------------------------------|
| **Smart Contract** | Solidity + Hardhat/Foundry | Defines on-chain logic                 |
| **Deployment**     | Monad Testnet RPC          | Publishes contract                     |
| **Frontend**       | React + Scaffold-ETH       | User interface                         |
| **Wallet**         | MetaMask / Privy / WalletConnect | Connects users to blockchain   |
| **Transactions**   | ethers.js / wagmi hooks    | Sends and reads data from contract     |

---

## 🚀 Features
- Connect wallet and interact with deployed contract
- Execute transactions on Monad Testnet
- Minimal, clean UI for user-friendly interaction
- Real-time transaction feedback (pending/confirmed states)

Monad testnet explorer: https://testnet.monadvision.com/myspace?type=Transactions
Transaction hash: 0x329f448b2d640ba3d1e0078224c72a93617f507d3586dc61864f9523484f2ade
