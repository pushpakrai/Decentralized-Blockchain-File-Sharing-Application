
# Decentralized File Sharing Project (D-FILE)

This repository contains the code for the **D-FILE** project, a decentralized file storage solution similar to Google Drive, built using **Hardhat**, **Solidity (Smart Contracts)**, and **React.js**. The application leverages blockchain technology to ensure secure and transparent storage and access control for files.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Architecture](#architecture)
- [Smart Contract](#smart-contract)
- [Frontend](#frontend)
- [Contributing](#contributing)

## Installation

To set up and run the D-FILE project on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/decentralized-gdrive.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd decentralized-gdrive
   ```

3. **Install dependencies for the smart contract**:
   - Ensure you have [Node.js](https://nodejs.org) installed.
   - Install Hardhat:
     ```bash
     npm install hardhat
     ```

4. **Install dependencies for the frontend**:
   - Navigate to the `frontend` directory:
     ```bash
     cd frontend
     ```
   - Install the Node.js dependencies:
     ```bash
     npm install
     ```

## Usage

1. **Start a local blockchain network** using Hardhat:
   ```bash
   npx hardhat node
   ```

2. **Deploy the smart contract** to the local network:
   - Navigate to the project directory:
     ```bash
     cd decentralized-gdrive
     ```
   - Compile and deploy the smart contract:
     ```bash
     npx hardhat run --network localhost scripts/deploy.js
     ```

3. **Start the frontend development server**:
   - Navigate to the `client` directory:
     ```bash
     cd client
     ```
   - Run the development server:
     ```bash
     npm start
     ```

4. **Open your browser** and go to `http://localhost:3000` to access the decentralized GDrive application.

5. **Connect the frontend** to your local blockchain using MetaMask.

## Architecture

The **D-FILE** project is structured with the following key technologies:

- **Hardhat**: A development environment for Ethereum smart contracts that facilitates testing, deployment, and contract interaction.
- **Solidity (Smart Contract)**: The smart contract manages file storage, access control, and ownership directly on the blockchain.
- **React.js**: The frontend is built using React.js, providing a responsive, user-friendly interface for interacting with the blockchain.
- **Pinata**: Pinata is utilized as a decentralized file storage solution to securely store files.

## Smart Contract

The smart contract, written in Solidity, handles the following functionality:

- **File Upload**: Files are uploaded to decentralized storage and linked to the blockchain.
- **Access Control**: Ensures only authorized users can access, modify, or delete files.
- **File Ownership**: Allows users to transfer file ownership securely through blockchain transactions.

The smart contract code can be found in the `contracts` directory.

## Frontend

The frontend of **D-FILE** is built with React.js and communicates with the smart contract to provide the following features:

- **File Upload**: Users can upload files to decentralized storage.
- **File Access**: Users can view and download files stored on the blockchain.
- **Access Permissions**: Manage permissions to allow or restrict file access.
- **Ownership Transfer**: Securely transfer file ownership to other users.

The frontend code is located in the `client` directory.

## Contributing

We welcome contributions to the **D-FILE** project! To contribute:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b my-feature
   ```
3. **Make the necessary changes** and commit your code:
   ```bash
   git commit -am 'Add new feature'
   ```
4. **Push the changes** to your forked repository:
   ```bash
   git push origin my-feature
   ```
5. **Submit a pull request** with a description of your changes.
