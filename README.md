# PepeBeanz Presale Smart Contract

## Overview
This project is a Solana smart contract built using the Anchor framework. It implements a presale mechanism for the PepeBeanz token, allowing users to buy tokens during a presale period and claim them later.

## Project Structure
- **programs/pepebeanz-presale/**: Contains the Rust smart contract code.
  - **src/**: Main source code.
    - **instructions/**: Contains the instruction handlers (buy, claim, deposit, withdraw, etc.).
    - **state/**: Defines the on-chain state structures.
    - **errors/**: Custom error definitions.
    - **constants/**: Reusable constants.
    - **lib.rs**: Main entrypoint for the smart contract.
  - **Cargo.toml**: Rust dependencies and configuration.
- **tests/**: Contains TypeScript tests for the smart contract.
- **migrations/**: Contains deployment scripts.
- **Anchor.toml**: Anchor configuration file.
- **package.json**: JavaScript/TypeScript dependencies.

## Setup
1. **Prerequisites**:
   - Rust and Cargo
   - Node.js and npm
   - Solana CLI
   - Anchor Framework

2. **Installation**:
   ```bash
   # Clone the repository
   git clone https://github.com/PepeBeanz/token-presale.git
   cd pepebeanz-presale

   # Install dependencies
   npm install
   ```

3. **Build the Smart Contract**:
   ```bash
   anchor build
   ```

4. **Deploy the Smart Contract**:
   ```bash
   anchor deploy
   ```

## Usage
- **Buy Tokens**: Use the `buy` instruction to purchase tokens during the presale.
- **Claim Tokens**: Use the `claim` instruction to claim tokens after the presale ends.
- **Deposit/Withdraw**: Use the `deposit` and `withdraw` instructions to manage funds.

## License
This project is licensed under the MIT License. See the LICENSE file for details. 