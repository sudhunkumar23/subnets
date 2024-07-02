# ERC20 and Vault Contracts

## Overview

This repository contains smart contracts for an ERC20 token and a Vault contract. The ERC20 contract follows the standard ERC20 token interface, providing basic functionality for transferring and managing tokens. The Vault contract is designed to interact with the ERC20 contract, allowing users to deposit and withdraw tokens securely.

## Contracts

### ERC20 Token Contract

The ERC20 token contract implements the standard ERC20 interface, providing the following functionalities:

- **Minting:** Creating new tokens and assigning them to a specific address.
- **Burning:** Destroying tokens from a specific address, reducing the total supply.
- **Transfers:** Transferring tokens from one address to another.
- **Allowances:** Allowing a spender to transfer tokens on behalf of the owner.

### Vault Contract

The Vault contract allows users to deposit and withdraw ERC20 tokens. It is designed to securely manage the tokens and ensure that only authorized users can interact with their tokens. The main functionalities include:

- **Deposit:** Users can deposit a specified amount of ERC20 tokens into the vault.
- **Withdraw:** Users can withdraw a specified amount of ERC20 tokens from the vault.
- **Balance:** Users can check their token balance in the vault.

### ERC20 Token Contract

You can interact with the ERC20 token contract using various functions provided by the ERC20 interface, such as `transfer`, `approve`, `transferFrom`, etc.

### Vault Contract

The Vault contract provides functions for depositing and withdrawing tokens:

- **Deposit Tokens:**

```javascript
vault.deposit(amount);
```

- **Withdraw Tokens:**

```javascript
vault.withdraw(amount);
```

- **Check Balance:**

```javascript
vault.balanceOf(userAddress);
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or additions.
