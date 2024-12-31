
# Decentralized File Sharing Project (D-FILE)

This repository hosts the code for **D-FILE**, a decentralized file-sharing platform akin to Google Drive, developed using **Hardhat**, **Solidity (Smart Contracts)**, and **React.js**. By leveraging blockchain technology, **D-FILE** ensures secure, transparent, and decentralized file storage and access control.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Architecture](#architecture)
- [Smart Contract Features](#smart-contract-features)
- [Frontend Features](#frontend-features)
- [Contributing](#contributing)
- [License](#license)

---

## Installation

Follow these steps to set up and run the **D-FILE** project on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/pushpakrai/Decentralized-Blockchain-File-Sharing-Application.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Decentralized-Blockchain-File-Sharing-Application
   ```

3. **Install dependencies for the smart contract**:
   ```bash
   npm install
   ```

4. **Set up the frontend**:
   - Navigate to the `client` directory:
     ```bash
     cd client
     ```
   - Install the Node.js dependencies:
     ```bash
     npm install
     ```

---

## Usage

1. **Start a local blockchain network**:
   ```bash
   npx hardhat node
   ```

2. **Deploy the smart contract**:
   - Compile and deploy the smart contract to the local network:
     ```bash
     npx hardhat run --network localhost scripts/deploy.js
     ```

3. **Launch the frontend application**:
   - Navigate to the `client` directory:
     ```bash
     cd client
     ```
   - Start the development server:
     ```bash
     npm start
     ```

4. **Access the application**:
   Open your browser and navigate to `http://localhost:3000`. Ensure MetaMask is connected to the local blockchain network.

---

## Architecture

The **D-FILE** platform employs the following technologies:

- **Hardhat**: Facilitates smart contract development, testing, and deployment.
- **Solidity**: Implements the business logic for file storage, access control, and ownership management on the blockchain.
- **React.js**: Provides an intuitive user interface for interacting with the decentralized file system.
- **Pinata**: Used for decentralized file storage, ensuring redundancy and security.

---

## Smart Contract Features

The Solidity smart contract handles core functionalities, including:

- **File Upload**: Links uploaded files to the blockchain and stores metadata securely.
- **Access Control**: Grants or revokes permissions for specific users.
- **Ownership Management**: Transfers file ownership securely between users.
- **Tamper-Proof Logs**: Maintains immutable records of all file-related transactions.

The contract code is in the `contracts` directory.

---

## Frontend Features

The **D-FILE** frontend, built with React.js, offers:

- **User Authentication**: Connect your wallet via MetaMask for secure access.
- **File Management**:
  - Upload and view files stored on the blockchain.
  - Download files directly from decentralized storage.
  - Delete or modify file permissions.
- **Access Permissions**: Enable or restrict other users' access to specific files.
- **Ownership Transfer**: Securely transfer file ownership to designated users.

Frontend source code resides in the `client` directory.

---

## Contributing

We welcome contributions to enhance the **D-FILE** project! Here's how to get involved:

1. **Fork the repository**.
2. **Create a feature branch**:
   ```bash
   git checkout -b feature-name
   ```
3. **Implement changes** and commit:
   ```bash
   git commit -m "Add feature description"
   ```
4. **Push changes** to your forked repository:
   ```bash
   git push origin feature-name
   ```
5. **Open a pull request**, detailing your enhancements or fixes.

---

## License

This project is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.
