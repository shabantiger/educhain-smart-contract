
# 🎓 EduChain Smart Contract

EduChain is a **blockchain-based academic certificate platform** that allows educational institutions to issue verifiable certificates as NFTs.  
This repository contains the **Solidity smart contract code** deployed on the **Base Network** (an Ethereum Layer 2 by Coinbase).

---

## 🚀 Overview

EduChain eliminates certificate fraud by minting each academic certificate as a **non-fungible token (NFT)**.  
These NFTs are **tamper-proof, globally verifiable**, and permanently stored on-chain with metadata hosted on **IPFS**.

**Core Features:**
- Mint academic certificates as ERC-721 NFTs  
- Bulk issuance for multiple students  
- On-chain verification using wallet address or certificate ID  
- Integration with IPFS for decentralized metadata storage  
- Role-based access for institutions and verifiers  

---

## 🧠 Smart Contract Details

**Language:** Solidity  
**Standard:** ERC-721  
**Network:** Base (Ethereum Layer 2)  
**Deployed Contract Address:** `0xBD4228241dc6BC14C027bF8B6A24f97bc9872068`  
**Compiler Version:** `^0.8.20`

---

## 📂 File Structure


---

## ⚙️ How It Works

1. **Institution Onboarding:**  
   Authorized institutions are added to the contract via an admin function.  

2. **Certificate Issuance:**  
   Institutions call the `mintCertificate()` function with metadata URI (stored on IPFS).  

3. **Verification:**  
   Employers or third parties can verify certificates by wallet address or token ID directly on-chain.  

4. **Bulk Minting:**  
   Institutions can issue multiple certificates in a single transaction, optimizing gas usage.  

---

## 🛠️ Technologies Used

- **Solidity** – Smart contract development  
- **Base Network** – Layer 2 deployment  
- **Ethers.js** – Frontend Web3 integration  
- **IPFS / Pinata** – Decentralized metadata storage  
- **Hardhat** – Local development and testing  
- **OpenZeppelin** – Security-audited ERC-721 standards  

---

## 🧪 Deployment & Testing

### Prerequisites
- Node.js >= 18.x  
- Hardhat installed globally (`npm install -g hardhat`)  
- MetaMask wallet connected to Base Testnet  

### Installation
```bash
git clone https://github.com/shabantiger/EduChain-smart-Contract.git
cd EduChain-Contract
npm install
