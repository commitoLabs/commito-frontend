# Commito Frontend (`commito-frontend`)

Welcome to the **Frontend** repository for [Commito](https://github.com/commitoLabs), a decentralized commitment platform built on the Stellar network and Soroban smart contracts. Commito empowers users to build life-changing habits by putting their money where their mouth is. Stake your XLM, follow through on your daily or weekly habits, and earn your deposit back! If you slip up, your stake is slashed—giving you the ultimate financial accountability to achieve your goals.

##  About Commito

Consistency is hard, but financial incentives make it easier. **Commito** is a dApp designed to help users stick to their commitments (like exercising daily, reading, or learning to code) by leveraging the speed, security, and low fees of the Stellar network. 

Here is how the platform works:
1. **Commit & Stake**: A user defines a habit, sets a duration, and locks up (stakes) a specific amount of XLM via our Soroban smart contract.
2. **Prove & Progress**: Users check in daily or weekly by providing proof of their completion.
3. **Success or Slash**: If the user successfully completes their streak, they withdraw their full deposited XLM. If they miss a check-in, their staked funds are slashed.

##  About This Repository

This repository contains the **Next.js web application** that serves as the user-facing gateway to the Commito ecosystem. It provides a sleek, modern, and intuitive UI for users to:
- **Seamlessly Connect**: Safely connect their Stellar wallets (e.g., Freighter, Albedo) to the dApp.
- **Manage Commitments**: Browse their active streaks, review historical data of completed challenges, and see any failed commitments.
- **Create Stakes**: Use a dynamic 'Create Commitment' flow to define a new goal, specify the XLM amount, and seamlessly sign the Soroban transaction to deposit funds directly from the browser.
- **Track Progress**: View real-time analytics, including their current streak, total XLM staked, and days remaining on their dashboard.

## Tech Stack
- **Framework**: React / Next.js
- **Styling**: Tailwind CSS
- **Wallet Connection**: Stellar Wallet Kit / `@stellar/freighter-api`
- **Interactions**: `@stellar/stellar-sdk`

## Getting Started

### Prerequisites
- Node.js (v18+)
- A Stellar wallet extension installed in your browser (e.g., [Freighter](https://www.freighter.app/)).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/commitoLabs/commito-frontend.git
   cd commito-frontend
   ```
2. Install the necessary dependencies:
   ```bash
   npm install
   ```
3. Create your local environment file:
   ```bash
   cp .env.example .env.local
   # Ensure you point the API URLs to your local or staging backend servers.
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Contributing
Calling all frontend developers! We are taking part in the **Stellar Drips Waves**. 
Want to help build a beautiful user interface? Check the **[Issues](#)** tab for tasks labeled `frontend`, `ui/ux`, or `good first issue`. 

When you submit a PR, please include a before/after screenshot if you've made visual changes!

## License
Distributed under the MIT License. See `LICENSE` for more information.
