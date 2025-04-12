
# 🧑‍💻 Freelance Connect

Freelance Connect is a decentralized freelancing platform that connects clients with freelancers through a smart contract-based system. Built using **Next.js** for the frontend and **Solidity (Forge)** for secure, transparent contracts, this platform enables milestone-based payments, project bidding, and student contributions to real-world tasks.

---

## 🚀 Project Structure

```
freelance-connect/
│
├── frontend/           # Next.js app
│   └── ...             # Pages, components, hooks
│
├── contract/           # Solidity smart contracts (Forge)
│   ├── src/
│   ├── script/
│   └── test/
│
└── README.md
```

---

## ✨ Features

- 🛠️ Post & Bid on Freelance Projects
- 💸 Milestone-based Payments via Smart Contract
- 🔐 Escrow System for Safe Transactions
- 🧑‍🎓 Student Contribution System with Rating & Reviews
- 🪪 Aadhaar-based User Verification
- 📊 Dashboard for Clients and Freelancers
- ⚡ Fast and responsive UI (Tailwind + Next.js)

---

## 💻 Tech Stack

### Frontend
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Axios](https://axios-http.com/) – for API calls
- [Framer Motion](https://www.framer.com/motion/) – animations

### Smart Contracts
- [Solidity](https://soliditylang.org/)
- [Foundry (Forge)](https://book.getfoundry.sh/)
- [Hardhat (optional)] – for testing and development
- [Chainlink](https://chain.link/) – (if used for price feeds / randomness)

---

## 📷 Preview

### Landing Page
![Landing Page](./landing-preview.png)

### Dashboard
![Dashboard](./dashboard-preview.png)


> 📁 Add your screenshots inside an `/assets` folder in the root directory.

---

## 🛠️ Installation

### Frontend (Next.js)

```bash
cd frontend
npm install
npm run dev
```

### Contracts (Forge)

```bash
cd contract
forge install
forge build
forge test
```

> ✅ Make sure you have `foundry` installed. You can install it via:
```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

---

## 📝 Smart Contract Overview

Contracts include:

- `FreelanceContract.sol`: Handles project creation, bidding, milestone payments.
- `Escrow.sol`: Manages locked funds and release based on milestones.
- `Rating.sol`: Manages client/freelancer reviews & ratings.

---

## ✅ Coming Soon

- GitHub-style contribution system for students
- Project recommendation system via AI
- IP & Aadhaar-based verification to prevent spam/fraud

---

## 🙌 Contributors

- **Hitesh Suthar** – Full Stack & Web3 Developer

---

