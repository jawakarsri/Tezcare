# TezCare: A Decentralized Healthcare Management System Using Tezos Blockchain



## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)

---

## Project Overview
**TezCare** is a decentralized healthcare management system powered by the **Tezos blockchain**. It enables secure storage and sharing of health records while granting patients complete control over their data. With **AES** and **RSA encryption**, combined with **IPFS** for decentralized file storage, TezCare prioritizes privacy, transparency, and interoperability.

---

## Features
- **Tezos Blockchain Integration**: Ensures decentralized, immutable, and tamper-proof storage of patient and doctor data.
- **AES and RSA Encryption**: Provides secure data storage and key sharing using industry-standard encryption.
- **IPFS Storage**: Decentralized storage for handling large medical documents like PDFs and images.
- **Patient-Centric Data Sharing**: Empowers patients to securely share health records with authorized doctors using public/private key pairs.

---

## Tech Stack
- **Backend**: Node.js, Express.js
- **Blockchain**: Tezos Blockchain
- **Encryption**: AES & RSA
- **Decentralized Storage**: IPFS (InterPlanetary File System)
- **Frontend**: React.js with Chakra UI
- **Authentication**: JWT, bcrypt (for user authentication)

---

## Usage
1. **Registration**:
   - Patients and doctors can register on the platform.
2. **Login**:
   - After registration, users can log in to manage or access health records.
3. **Data Encryption**:
   - Health data is encrypted using AES, and keys are shared securely via RSA encryption.
4. **Document Storage**:
   - Diagnosis documents are stored in IPFS and linked to blockchain transactions for decentralized, secure access.

---

## API Endpoints
Here are some key API routes in TezCare:

### **POST /api/register**
Register a new patient or doctor.

#### Request Example:
```json
{
  "name": "Jane Doe",
  "aadhar": "987654321098",
  "age": 28,
  "sex": "Female"
}
