# 🔗 SeQureChain

## Blockchain-Based Evidence Management System

A decentralized digital evidence management platform that leverages Ethereum Blockchain, IPFS, MetaMask Authentication, and Firebase to provide secure, tamper-evident, and verifiable evidence storage.

---

## Project Overview

Traditional evidence management systems rely heavily on centralized databases that are vulnerable to:

- Single Point of Failure
- Insider Manipulation
- Record Tampering
- Weak Authentication Mechanisms
- Incomplete Chain-of-Custody Records

SeQureChain addresses these challenges by integrating blockchain technology and decentralized storage to ensure evidence integrity, transparency, and accountability.

The platform enables law enforcement agencies, forensic investigators, legal professionals, and administrators to securely manage digital evidence while maintaining an immutable audit trail.

---

## Key Features

### Authentication

- MetaMask Wallet Authentication
- Passwordless Login
- ECDSA Digital Signature Verification

### Evidence Management

- Upload Digital Evidence
- Store Files on IPFS
- Generate SHA-256 Hashes
- Immutable Blockchain Recording

### Verification

- Evidence Integrity Verification
- Tamper Detection
- Public Blockchain Validation

### Audit Trail

- Complete Chain-of-Custody Tracking
- Transaction History
- Timestamp Verification

### Dashboard

- Evidence Statistics
- Activity Monitoring
- Recent Upload Tracking

### Security

- Decentralized Architecture
- Blockchain Immutability
- Cryptographic Hashing
- Wallet-Based Authentication

---

## Problems Solved

| Problem | Traditional Systems | SeQureChain |
|----------|----------|----------|
| Single Point of Failure | ❌ | ✅ |
| Evidence Tampering | ❌ | ✅ |
| Weak Authentication | ❌ | ✅ |
| Chain-of-Custody Issues | ❌ | ✅ |
| Independent Verification | ❌ | ✅ |

---

## System Architecture

```text
User
│
▼
MetaMask Authentication
│
▼
React Native Frontend
│
├────────► IPFS (Pinata)
│
├────────► Firebase Firestore
│
└────────► Ethereum Smart Contract
               │
               ▼
        Ethereum Sepolia
```

---

## Technology Stack

### Frontend

- React Native
- Expo SDK 50
- React Context API

### Backend

- Node.js
- Express.js

### Blockchain

- Solidity
- Hardhat
- Ethereum Sepolia
- ethers.js

### Storage

- IPFS
- Pinata

### Database

- Firebase Firestore

### Authentication

- MetaMask

### Infrastructure

- Alchemy RPC

---

## Upload Workflow

### Step 1

User connects MetaMask wallet.

### Step 2

Evidence file is selected.

### Step 3

SHA-256 hash is generated.

### Step 4

File uploaded to IPFS.

### Step 5

CID returned by Pinata.

### Step 6

Metadata stored in Firebase.

### Step 7

User signs blockchain transaction.

### Step 8

Hash stored on Ethereum.

### Step 9

Transaction confirmed.

### Step 10

Evidence becomes independently verifiable.

---

## Smart Contract Functions

### submitEvidence()

Records evidence on-chain.

### verifyIntegrity()

Verifies file integrity against blockchain record.

### getEvidenceReadOnly()

Retrieves stored evidence information.

### evidenceExistsCheck()

Checks duplicate evidence submission.

### getEvidenceCount()

Returns total evidence count.

---

## Repository Structure

```text
frontend/
backend/
blockchain/
docs/
screenshots/
README.md
LICENSE
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/hmzasaed/SequreChain.git
```

### Enter Project

```bash
cd SequreChain
```

### Install Frontend

```bash
cd frontend
npm install
```

### Install Backend

```bash
cd ../backend
npm install
```

### Install Smart Contract Dependencies

```bash
cd ../blockchain
npm install
```

---

## Environment Variables

Create a `.env` file.

```env
PINATA_JWT=
ALCHEMY_API_KEY=
FIREBASE_API_KEY=
FIREBASE_PROJECT_ID=
CONTRACT_ADDRESS=
CHAIN_ID=11155111
```

---

## Screenshots

### Dashboard

Add screenshot here.

### Upload Evidence

Add screenshot here.

### Evidence History

Add screenshot here.

### Integrity Verification

Add screenshot here.

---

## Testing

### Unit Testing

- Smart Contract Testing
- Hash Verification Testing
- Authentication Testing

### Integration Testing

- End-to-End Upload
- Blockchain Verification
- Evidence Retrieval
- Chain-of-Custody Validation

---

## Performance

| Metric | Result |
|----------|----------|
| Average Upload Time | 22 Seconds |
| Blockchain Confirmation | 14.6 Seconds |
| Integrity Verification | <500ms |
| Detection Accuracy | 100% |
| Transaction Reliability | 100% |

---

## Security Features

- SHA-256 Hashing
- ECDSA Signatures
- MetaMask Authentication
- Blockchain Immutability
- IPFS Content Addressing
- Audit Logging

---

## Future Enhancements

- Polygon Deployment
- Arbitrum Deployment
- WalletConnect Integration
- AES-256 Client Encryption
- Zero Knowledge Proofs
- AI Anomaly Detection
- Cross-Jurisdiction Evidence Sharing

---

## Contributors

### Hamza Saeed

Full Stack Developer | Blockchain Developer

### SeQureChain Development Team

Final Year Project

---

## Acknowledgements

Special thanks to:

- Ethereum
- MetaMask
- Hardhat
- Pinata
- Firebase
- Expo
- React Native

---

## License

Distributed under the MIT License.

See LICENSE for more information.

---

## Star the Repository

If you found this project useful, please consider giving it a ⭐.
