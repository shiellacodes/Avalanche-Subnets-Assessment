# Avalanche-Subnets-Assessment
Project: Defi Empire, A Simple DeFI Kingdom Clone

## Description
This repository contains two smart contracts written in Solidity:

ERC20.sol: An implementation of the ERC-20 token standard.
Vault.sol: A vault contract that interacts with an ERC-20 token, allowing deposit and withdrawal of tokens in exchange for shares.

## Getting Started
### Executing Program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:
[https://github.com/shiellacodes/DegenToken.git](https://github.com/shiellacodes/Avalanche-Subnets-Assessment.git)

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile ERC20.sol" button first, then Vault.sol.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Enter your owner's account and an Initial token value from the dropdown menu, and then click on the "Deploy" button.

-----------------------------------------------------------------------------------------------------------------------------------

Contract Functions
1. ERC20 Contract
   Functions
   - transfer(address recipient, uint amount) external returns (bool)
   - approve(address spender, uint amount) external returns (bool)
   - transferFrom(address sender, address recipient, uint amount) external returns (bool)
   - mint(uint amount) external
   - burn(uint amount) external
  
  Events
  - Transfer(address indexed from, address indexed to, uint value)
  - Approval(address indexed owner, address indexed spender, uint value)
     
2. Vault Contract
   Functions
   - deposit(uint _amount)
   - withdraw(uint _shares)

  
-----------------------------------------------------------------------------------------------------------------------------------

Deployment
To deploy these contracts, follow the steps below:

Deploy the ERC20.sol contract:

Compile and deploy the ERC20 contract on your preferred Ethereum network.
Deploy the Vault.sol contract:

After deploying the ERC20 contract, pass the address of the deployed ERC-20 token to the constructor of the Vault contract.
Interact with the Vault:

Users can interact with the vault by depositing and withdrawing tokens, receiving and burning shares in return.

## Authors

Shiella Marie P. Umali
202010956@fit.edu.ph


## License

This project is licensed under the MIT License License - see the LICENSE.md file for details
