# ⚙️ Solidity Smart Contracts

This repository contains several smart contracts written in Solidity. Each contract demonstrates a core concept in Ethereum development and smart contract design. These projects are part of my learning journey in blockchain and smart contract development.

---

## 📄 Projects Included

### 🔹 1. Simple Storage
A basic contract to store and retrieve a number on the blockchain.

- Learnings: data types, state variables, functions, memory vs storage.

### 🔹 2. Storage Factory
Creates and manages multiple instances of the `SimpleStorage` contract using factory design pattern.

- Learnings: contract interactions, arrays of contracts, modularity.

### 🔹 3. Fund Me
A crowdfunding smart contract that allows users to fund and only allows the owner to withdraw the funds.

- Learnings: `msg.value`, `require`, `payable`, ETH to USD conversion (via Chainlink price feeds).

### 🔹 4. Voting System
A basic voting contract that allows registration of candidates, casting votes, and tallying results.

- Learnings: mappings, structs, access control, loops.

---

## 🛠 Tools & Technologies

- **Solidity** (v0.8.x)
- **Remix IDE** for testing
- **MetaMask** for transaction signing
- **Chainlink** (used in Fund Me for price feeds)

---

## 🚀 How to Run

1. Clone this repository.
2. Open any contract in [Remix IDE](https://remix.ethereum.org).
3. Compile the contract using the Solidity compiler.
4. Deploy using the JavaScript VM, Injected Web3 (MetaMask), or any connected wallet.
5. Interact with the deployed contract functions.

---

## 🧠 What I’m Learning

- Smart contract patterns and security
- Gas optimization
- Real-world use cases (payments, voting, storage)
- Frontend integration with Web3

---

## 📌 Notes

These contracts are for educational purposes. Always test thoroughly before deploying to a live network.

---

## 📃 License

This project is open-source and free to use or modify for learning and experimentation.
