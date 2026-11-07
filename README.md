# LandLedger

A blockchain-based land title registry designed to reduce land fraud in Nigeria.

## The problem
[2-3 sentences: land fraud, duplicate sales, forged documents.]

## The solution
Land parcels are recorded as ERC-721 tokens on the blockchain, with document hashes stored on IPFS so tampering can be detected.

## Key features
- Land parcel tokenisation (ERC-721)
- 5-of-5 multi-signature governance
- Smart contract escrow (deposits, instalment plans, multi-parcel bundles)
- Three account types with TOTP 2FA and JWT sessions
- Identity verification (NIN/BVN/liveness) and cNGN payments

## Security
Identified and addressed reentrancy risks, admin collusion risk and document tampering.

## Architecture
![Architecture diagram](<img width="1615" height="977" alt="17ff4120-755f-43d6-9805-8654f918bd10" src="https://github.com/user-attachments/assets/0de7de14-ea19-452e-ae49-abe2ebc3a6f6" />
)

## Screenshots
![Landing page](<img width="1365" height="682" alt="LandLedger Landing Page" src="https://github.com/user-attachments/assets/c7d8d74d-1043-4c44-9fdd-37f3f4401966" />
)

![Dashboard](<img width="1365" height="681" alt="LandLedger Dashboard" src="https://github.com/user-attachments/assets/ed8e351a-70f8-4c86-956f-f77cd2ae43c5" />
)

## Tech stack
Solidity, Node.js/Express, MongoDB Atlas, Hardhat, Polygon, HTML/CSS/JavaScript

## Status
Pre-launch. The full source code is private; available for review on request.

## Author
Odu, Stephen Anyaku: [https://linkedin.com/in/anyaku3] | [https://medium.com/@anyaku3]
