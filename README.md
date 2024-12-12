# React-Next-Lottery

A decentralized lottery application built with **Next.js**, **React**, and **Solidity** to enable fair and transparent lottery games on the blockchain. This project integrates a smart contract powered by Chainlink VRF for randomness and uses modern web technologies for an engaging user interface.

## Features

- **Blockchain-Powered:** Leverages Ethereum blockchain and smart contracts for secure and decentralized lotteries.
- **Chainlink VRF Integration:** Ensures verifiable randomness for selecting lottery winners.
- **Modern Frontend:** Built with Next.js and React, styled using TailwindCSS for a responsive design.
- **Wallet Integration:** Supports MetaMask for seamless user authentication and transaction handling.
- **Thirdweb Deployment:** Streamlines smart contract deployment and interaction.

## Tech Stack

- **Frontend:** React, Next.js, TailwindCSS
- **Blockchain:** Solidity, Chainlink VRF
- **Libraries:** ethers.js, thirdweb
- **Tools:** MetaMask, Yarn/NPM

## Prerequisites

- **Node.js** and **Yarn/NPM** installed.
- A Web3 wallet like **MetaMask**.
- Access to an Ethereum-compatible network (e.g., testnet or local blockchain).

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/junaid5598/react-next-lottery.git
cd react-next-lottery
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Configure the Environment

- Update the smart contract address in the application configuration (usually in a constants or environment file).
- Ensure your blockchain node or provider (e.g., Alchemy or Infura) is set up.

### 4. Run the Development Server

```bash
npm run dev
# or
yarn dev
```

Navigate to [http://localhost:3000](http://localhost:3000) in your browser to see the app.

## Usage

1. Connect your MetaMask wallet to the application.
2. Enter the lottery by paying the required entry fee in ETH.
3. Wait for the draw, powered by Chainlink VRF, to determine the winner.
4. If you're the winner, claim your prize directly through the application.

## Smart Contract

The smart contract used in this project ensures transparency and fairness. Key functionalities include:

- **Create Lottery:** Admins can create a new lottery with specific start and end times and an entry fee.
- **Enter Lottery:** Users can participate by paying the entry fee.
- **Draw Winner:** Calls Chainlink VRF for randomness to select a winner.
- **Withdraw Winnings:** The winner can claim their prize securely.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Acknowledgments

- [Chainlink VRF](https://chain.link/vrf)
- [Next.js](https://nextjs.org/)
- [Thirdweb](https://thirdweb.com/)
```

Let me know if additional sections or edits are needed!
