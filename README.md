# Mixezs Frontend Project Overview

## Project Overview

This is a frontend application for interacting with the Mixezs smart contract. Mixezs is a decentralized privacy transfer platform based on Ethereum, designed to provide secure and anonymous token transfers. The frontend application is built using the Vue framework and the `@web3modal/ethers/vue` library, and it has been compiled. Users can deploy and access it directly without needing to compile or install dependencies themselves.

## Features

- **Privacy Transfers**: Mixezs ensures anonymity and security in the transfer process using stealth addresses and encrypted signatures.
- **Wallet Connection**: Users can connect various Ethereum wallets via `@web3modal`.
- **Deposit Functionality**: Users can deposit tokens (including WETH) into the contract discreetly.
- **Withdrawal Functionality**: Users can withdraw deposited tokens from the contract, ensuring privacy in the withdrawal process.
- **Real-time Feedback**: The application provides messages indicating success or failure of operations and offers clear status updates.

## Technology Stack

- **Vue**: Frontend framework used for building the user interface.
- **@web3modal/ethers/vue**: Library for interacting with the Ethereum network and managing wallets.
- **Ethers.js**: Ethereum JavaScript library used for interacting with smart contracts.

## Instructions

1. **Download the Source Code**
   - Visit the GitHub repository: [GitHub Repository](https://github.com/dexcpro/mixezs-ui.git).
   - Clone or download the compiled frontend code:
     ```bash
     git clone https://github.com/dexcpro/mixezs-ui.git
     ```

2. **Deploy on Render**

   1. **Register and Log In to Render**
      - Go to [Render](https://render.com/) and create an account, or log in with an existing account.

   2. **Create a New Web Service**
      - In the Render dashboard, click the “New” button and select “Static Site” to deploy a static website.

   3. **Upload Compiled Files**
      - Choose the “Deploy from Git” option.
      - Connect your GitHub account and select the repository containing the Mixezs frontend code (`https://github.com/dexcpro/mixezs-ui.git`).

   4. **Configure Deployment Settings**
      - Leave the “Build Command” field empty, as the project is already compiled.
      - Enter `/` (root directory) in the “Publish Directory” field because your project's access path is the root, not `dist`.

   5. **Deploy the Application**
      - Click the “Create Static Site” button, and Render will start deploying your application.

   6. **Access the Application**
      - Once deployment is complete, you will receive a publicly accessible URL. You can use this URL to access the deployed Mixezs application in your browser.

## Contributing

If you are interested in contributing to this project, please submit an issue or pull request. We welcome contributions in any form, including bug fixes, new features, or documentation improvements.

## Contact Information

If you have any questions or suggestions, please contact [hbniubi@gmail.com](mailto:hbniubi@gmail.com).
