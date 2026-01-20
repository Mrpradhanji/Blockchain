![IEEE](https://img.shields.io/badge/Published-IEEE-blue)

> 📘 **IEEE Published Research Project**  
> **Title:** *Decentralized Voting System Using Blockchain*  
> **Published In:** IEEE Xplore  
> **Domain:** Blockchain, Ethereum, Decentralized Applications (dApps)  
> **Type:** Peer-Reviewed Research Paper  
> **IEEE Link:** https://ieeexplore.ieee.org/document/11102754  
>
> This repository contains the **reference implementation** of the system proposed in the IEEE-published paper.  
> The project demonstrates the use of **Ethereum smart contracts** to ensure secure, transparent, and tamper-proof electronic voting.

# Decentralised Voting (dVoting)

A decentralised voting system based on [Ethereum blockchain](https://ethereum.org/dapps/) technology.

> This project started as a final year academic project and was later extended into a **research-oriented blockchain application**, resulting in an IEEE publication.

---

## 📌 System Workflow

The basic workflow of the application is as follows:

1. The **Admin** deploys the system on an Ethereum-compatible blockchain (EVM) and creates an election by providing election details and candidate information.
2. **Voters** connect to the same blockchain network and register themselves as eligible voters.
3. Registered voter details are displayed on the **Admin verification panel**.
4. The **Admin verifies** voter information (blockchain address, name, phone number) and approves eligible voters.
5. Approved voters **cast their vote** securely using the voting interface.
6. Once the election duration ends, the **Admin closes the election**, and results are automatically calculated and displayed, announcing the winner.

---

## 🧠 Key Features

- Decentralized and tamper-proof voting process  
- Smart contract–based election management  
- Secure voter registration and approval  
- Anonymous and immutable vote casting  
- Transparent and real-time result computation  

---

## 🛠️ Tech Stack

| Component | Technology |
|---------|------------|
| Blockchain | Ethereum |
| Smart Contracts | Solidity |
| Framework | Truffle |
| Local Blockchain | Ganache CLI |
| Frontend | Web3.js / React |
| Wallet | MetaMask |

---

## 🚀 Setting Up the Development Environment

### 🔧 Requirements

- [Node.js](https://nodejs.org)
- [Truffle](https://www.trufflesuite.com/truffle)
- [Ganache CLI](https://github.com/trufflesuite/ganache-cli)
- [MetaMask](https://metamask.io/) (Browser Extension)

---

### 📥 Installing Dependencies

1. Install **Node.js**  
   https://nodejs.org/en/download/

2. Install **Truffle** and **Ganache CLI**
   ```bash
   npm install -g truffle
   npm install -g ganache-cli
3. Install MetaMask browser extension
   https://metamask.io/download

⚙️ Project Configuration
1. Clone the repository:
   git clone https://github.com/Mrpradhanji/Blockchain
   cd dVoting
2. Run local Ethereum blockchain:
   ganache-cl
   Keep this running during development.

3. Configure MetaMask:
   New RPC URL: http://127.0.0.1:8545
   (Use 7545 for Ganache GUI and update truffle-config.js accordingly)

   Chain ID: 1337

4. Import Ganache accounts into MetaMask using private keys.

   Deploy smart contracts:
   truffle migrate
   Use truffle migrate --reset for redeployment.

5. Start the frontend:
   cd client
   npm install
   npm start

📄 Research Publication

Title: Decentralized Voting System Using Blockchain
Publisher: IEEE Xplore
Link: https://ieeexplore.ieee.org/document/11102754

This project serves as the practical implementation of the published research work and validates the feasibility of blockchain-based voting systems for small to medium-scale elections.

📄 How to Cite This Work

If you use this project for academic or research purposes, please cite:

@INPROCEEDINGS{11102754,
  title={Decentralized Voting System Using Blockchain},
  booktitle={IEEE Conference Proceedings},
  publisher={IEEE},
  url={https://ieeexplore.ieee.org/document/11102754}
}

📌 To-Do List

Planned improvements and enhancements:

 Email / Phone verification using OTP

 Automated voter verification system

 Election result report generation (charts & statistics)

 Workflow and UI/UX improvements

 Support for multiple election instances without redeployment

🏷️ GitHub Topics
blockchain
ethereum
solidity
smart-contracts
decentralized-voting
ieee-publication
web3
dapp

📜 License

This project is intended for academic and research purposes.
Please provide appropriate credit when using or extending this work.


---

✅ This README is:
- IEEE-style  
- Recruiter-friendly  
- Academic + practical  
- Ready for **GitHub Releases & citations**

If you want next:
- 🔥 IEEE-style **GitHub Release text**
- 🧑‍💼 Resume bullets from this project
- 💼 LinkedIn post announcing your publication

Just tell me 👌
