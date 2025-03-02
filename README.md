# FundMe Solidity Smart Contract

## Overview
This is my **first Solidity project**, and I was able to build this thanks to **Cyfrin and Patrick Collins**. Through this journey, I learned a lot about smart contracts, Foundry, and Solidity development. This project is a crowdfunding smart contract that allows users to donate cryptocurrency, with built-in price conversion functionality to ensure accurate transactions.

## 🚀 What We Did
- Built a **crowdfunding smart contract** where users can send ETH donations.
- Integrated **price conversion functionality** to determine real-world values.
- Used **Foundry** for testing, debugging, and deployment automation.
- Wrote unit and integration tests to ensure contract reliability.
- Created deployment scripts to simplify contract deployment.

## 🔧 Important Commands
These are the essential commands you need to work with this project:

### **Installation**
1. Install Foundry (if not installed):
   ```sh
   curl -L https://foundry.paradigm.xyz | bash
   foundryup
   ```

### **Build the Contracts**
```sh
forge build
```

### **Run Tests**
```sh
forge test -vv
```

### **Deploy the Contract**
```sh
forge script script/DeployFundMe.s.sol --rpc-url <your_rpc_url> --private-key <your_private_key> --broadcast
```

## 🌟 What I Learned
- Writing and deploying Solidity smart contracts
- Using Foundry for testing and deployment automation
- Understanding gas optimization and best practices
- Working with external data (like price feeds)

## 🛠️ How to Contribute
1. Fork the repo
2. Create a new branch
3. Make changes and test them
4. Submit a pull request (PR)

## 📜 License
This project is licensed under the MIT License.

