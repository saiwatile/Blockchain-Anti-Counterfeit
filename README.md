# 📦 FPISMF – Blockchain-Based Anti-Counterfeit System

### 🔐 Fake Product Identification for Small & Medium Firms

Using Blockchain + AES Encryption + Smart Contracts

---

## 🚀 Project Overview

FPISMF is a scalable, secure, and cost-effective blockchain-based anti-counterfeit system designed specifically for Small and Medium Enterprises (SMEs).

The system ensures product authenticity across the supply chain by combining:

* Blockchain immutability
* AES-256 encryption
* SHA-256 hashing
* Smart contracts
* Dynamic QR codes
* Ownership state tracking

Consumers can verify product authenticity using a mobile application by scanning a secure QR code.

---

## 🎯 Problem Statement

Counterfeit products:

* Damage brand reputation
* Cause financial losses
* Pose safety risks to consumers
* Are difficult to detect using traditional barcode systems

Static QR codes and centralized databases are vulnerable to duplication and tampering.

This project introduces a decentralized and tamper-proof authentication framework.

---

## 🧠 Proposed Solution

The system follows a hybrid blockchain architecture:

1. Manufacturer encrypts product data using AES-256.
2. SHA-256 hash of encrypted data is stored on blockchain.
3. Encrypted data stored off-chain (IPFS / Database).
4. Dynamic QR code generated.
5. Ownership transferred using smart contracts.
6. Consumer scans QR and verifies authenticity.

---

## 🏗 System Architecture

```
Manufacturer
     ↓
Backend (AES Encryption)
     ↓
Off-chain Storage (IPFS / Database)
     ↓
SHA-256 Hash → Blockchain (Smart Contract)
     ↓
QR Code Generated
     ↓
Supplier Updates Ownership
     ↓
Consumer Verification App
```

---

## 🔐 Security Features

* AES-256 encryption for product data
* SHA-256 hashing for blockchain verification
* Smart contract-based ownership state machine
* Dynamic QR regeneration after ownership transfer
* Geo-location validation
* Tamper detection mechanism
* Private key-based authentication

---

## 🛠 Tech Stack

### Blockchain Layer

* Solidity
* Hardhat
* Polygon / Ethereum Testnet

### Backend

* Node.js
* Express.js
* Ethers.js
* Crypto-js (AES)
* MongoDB

### Frontend

* React.js

### Mobile

* Android QR Verification App

---

## 📂 Project Structure

```
fpismf-blockchain-anti-counterfeit/
│
├── blockchain/        → Smart contracts & Hardhat config
├── backend/           → API + AES encryption logic
├── frontend/          → React user interface
├── docs/              → Technical documentation
├── .gitignore
└── README.md
```

---

## 🔄 System Roles

### 🏭 Manufacturer

* Register product
* Encrypt product data
* Generate secure QR
* Push hash to blockchain

### 🚚 Supplier

* Update shipment status
* Transfer ownership via smart contract

### 🛍 Consumer

* Scan QR code
* Validate blockchain record
* Receive authenticity result

---

## 📊 Future Enhancements

* AI-based anomaly detection
* NFT-based product identity
* Graph Neural Network fraud detection
* Zero-Knowledge Proof privacy layer
* IoT integration (RFID/NFC)

---

## 📅 Development Phases

Phase 1 – Smart Contract Development
Phase 2 – Backend Integration
Phase 3 – QR Generation & Verification
Phase 4 – Security Optimization
Phase 5 – Research-Level Enhancements

---

## 📖 Research Scope

This system can be extended into:

* IEEE Conference Paper
* Patent Submission
* Startup Prototype
* Scalable SaaS Model for SMEs

---

## ⚡ Current Status

Project Initialization Phase
Repository Structure Setup

---

## 👨‍💻 Author

Sai Watile and Shivani Danwe
Blockchain & AI Security Research

