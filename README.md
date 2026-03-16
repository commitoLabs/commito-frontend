# Commito Frontend (`commito-frontend`)

Welcome to the **Frontend** repository for [Commito](https://github.com/commitoLabs), a commitment dApp built on the Stellar network! Stake your XLM, follow through on your habits, and earn your deposit back.

## About This Repository
This is the user-facing web application that enables users to:
- Connect their Stellar wallet (Freighter, Albedo, etc.).
- Browse their active, failed, and completed commitments.
- Create a new commitment and sign the transaction to deposit XLM into the Soroban contract.
- View real-time stats of their streak.

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
