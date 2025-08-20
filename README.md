# Blended APP

This is a demo app that shows how we can interact from solidity with rust contracts using Fluent.

For more details you can check the [Building a Blended App](https://docs.fluentlabs.xyz/learn/developer-guides/building-a-blended-app) tutorial.

# Fluent Blended Escrow & Reputation App

This project is a **Blended App** built with [Fluent](https://fluent.xyz), combining smart contracts and off-chain logic.  
It demonstrates how to integrate **escrow contracts** with a **reputation system**, allowing secure transactions and trust building between participants.

---

## 📂 Project Structure
- **contracts/** → Solidity smart contracts (Escrow, Greeting, Interfaces).
- **deploy/** → Deployment scripts.
- **greeting/** → Rust-based off-chain component.
- **tasks/** → Hardhat tasks for contract interaction.
- **hardhat.config.ts** → Hardhat configuration.
- **package.json** → Node.js dependencies.

---

## 🚀 Getting Started

### 1. Install dependencies
```bash
npm install
```
### 2. Compile contracts
```bash
npx hardhat compile
```
### 3. Run local node
```bash
npx hardhat node
```
### 4. Deploy contracts
```bash
npx hardhat run deploy/00_deploy_contracts.ts --network localhost
```
### Contribution
```bash
Feel free to fork this repository, open issues, and submit pull requests.
```
### License
```bash
This project is released under the MIT License.
```
