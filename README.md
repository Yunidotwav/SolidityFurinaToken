# Solidity: Furina Token

Solidity Code that I made, with the name Furina Token we can make this show to the go!

## Description

**Lights! Camera! Token!**

This Solidity Project, inspired by Fontaine's Hydro Archon, Furina, allows you to create and manage your own token, called Furina Token! Furina Token gives you the support to build a vibrant in-game economy and a loyal community reward system, all made by using Furina's Heart and Mind.

## Let the Show Begin

### Installing or Online Compiler

* Download the Contract: Clone or download this repository to your local development environment.
  
* Solidity Compiler: Ensure you have a compatible Solidity compiler installed (version >= 0.8.0 recommended). Popular choices include command-line tools like solc or IDE plugins.

* Online Compiler on the other hand, go to https://remix.ethereum.org/ for compiling

### Executing program

How to run the program:

1. **Navigate to Remix:**
   - Open your web browser and go to Remix.

2. **Create a New File:**
   - If you haven't already, create a new file named `FurinaToken.sol` (or open your existing file containing the FurinaToken contract code).
   - Paste your FurinaToken contract code into the file.

3. **Compile the Contract:**
   - Click the "Compile" button in the left-hand sidebar.
   - Ensure there are no compilation errors displayed in the bottom panel.

4. **Deploy the Contract:**
   - Click the "Deploy & Run Transactions" button in the left-hand sidebar.

5. **Select the Contract:**
   - In the "Deploy" section of the "Deploy & Run Transactions" panel, make sure the contract selected is "FurinaToken".

6. **Deploy the Contract:**
   - Click the "Deploy" button.
   - If you connected a wallet, a confirmation window will appear in your wallet. Approve the transaction to deploy the contract.
   - Remix will display the transaction details and the deployed contract address once the deployment is successful.

7. **Interact with the Contract:**
   - Once deployed, you can interact with the contract's functions (e.g., mint, burn) using the "Deploy & Run Transactions" panel.

## Functionality

The FurinaToken contract offers the following core functionalities:

* **`mint(address _to, uint256 _value)`:** Mints a specified number of tokens (`_value`) and assigns them to the provided address (`_to`).
* **`burn(address _from, uint256 _value)`:** Burns a specified number of tokens (`_value`) from the address (`_from`). This requires the address to have sufficient balance.


## Help

Common Problems

* Double-check your Solidity compiler version and syntax for any errors.
* If using a deployment tool, verify its configuration and connection to the blockchain network.
* Deployment: Funded account, syntax errors, tool configuration.
* Interaction: Function arguments, insufficient balance, network congestion.

## Author

Yunie Ramirez
@yunidotwav

## License

This project is licensed under the Yunie N. Ramirez License - see the LICENSE.md file for details
