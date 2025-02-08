# Foundry Simple Storage

## Introduction

Foundry Simple Storage is a basic project demonstrating the implementation of a simple storage contract using the Foundry framework. This project serves as an educational tool for understanding the basics of smart contract development, deployment, and interaction on the Ethereum blockchain.

## Features

- Simple storage contract to store and retrieve a single value.
- Deployment scripts for easy contract deployment.
- Interaction scripts to read and write data to the contract.
- Unit tests to ensure the contract functions correctly.

## Getting Started

### Prerequisites

- Node.js and npm installed
- Foundry framework installed

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/foundry-simple-storage.git
   cd foundry-simple-storage
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

### Usage

1. Compile the contract:
   ```sh
   forge build
   ```

2. Deploy the contract:
   ```sh
   forge script scripts/Deploy.s.sol
   ```

3. Interact with the contract:
   ```sh
   forge script scripts/Interact.s.sol
   ```

### Running Tests

Run the unit tests to ensure the contract works as expected:
```sh
forge test
```

## Project Structure

- `contracts/`: Contains the Solidity smart contract.
- `scripts/`: Contains deployment and interaction scripts.
- `test/`: Contains unit tests for the smart contract.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
