# Teacher Contract

## Vision

The Teacher Contract aims to streamline the process of fund distribution on the Aptos blockchain. By automating the splitting of coins among multiple accounts, it facilitates transparent and efficient financial transactions. This contract is designed to serve educational institutions, scholarship programs, and decentralized applications that require equal fund distribution.

## Features

- **Automated Fund Distribution**: The contract automatically splits a specified amount of Aptos coins into three predefined wallet addresses.
- **Remainder Handling**: If the total amount sent is not perfectly divisible by three, any remainder is allocated to the first account, ensuring no funds are lost.
- **Simple Interface**: The contract provides a straightforward entry function to manage fund splitting with minimal complexity.
- **Secure Transactions**: Leveraging Aptos's secure framework, the contract ensures that all transactions are executed safely and efficiently.

## Future Scope

- **Dynamic Account Management**: Future versions could allow for dynamic addition or removal of accounts for splitting funds, providing greater flexibility.
- **Enhanced Error Handling**: Implementing more robust error-checking mechanisms to ensure valid transactions and enhance user experience.
- **Integration with DApps**: Potential integration with decentralized applications to provide fund distribution services within broader ecosystems, such as crowdfunding or educational platforms.
- **User Interface**: Developing a front-end interface to facilitate user interactions with the contract without requiring technical knowledge.

## Contract Info

### Module Name
- `0x54d77b3b4f2e6938f6f08c8a428bdc048d3bbd14f82fa62c38e58f11c413caf9::Teacher`

### Predefined Accounts
The contract includes three predefined wallet addresses for fund distribution:

- **ACCOUNT_1**: `0x7a35834489c7872dbc6881268894021a41986b6a834e37bcd8d5f17597430dd1`
- **ACCOUNT_2**: `0x790cb3bad13332674b1415836bd5b20470386ec0607705575c7904c7a035d906`
- **ACCOUNT_3**: `0xc467623f6832ded56e1460614b8a0bc269660a3b96c739da899f9d0ed2949039`

### Main Functionality
- **Function**: `split_money(account: &signer, amount: u64)`
  - **Parameters**:
    - `account`: The signer’s account initiating the transaction.
    - `amount`: The total amount of Aptos coins to be split.

### Usage
- To split funds, call the `split_money` function with the desired amount to distribute.

## Installation

1. **Prerequisites**:
   - Aptos CLI installed.
   - A funded Aptos account.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/TeacherContract.git
   cd TeacherContract
**# Teacher Contract

## Vision

The Teacher Contract aims to streamline the process of fund distribution on the Aptos blockchain. By automating the splitting of coins among multiple accounts, it facilitates transparent and efficient financial transactions. This contract is designed to serve educational institutions, scholarship programs, and decentralized applications that require equal fund distribution.

## Features

- **Automated Fund Distribution**: The contract automatically splits a specified amount of Aptos coins into three predefined wallet addresses.
- **Remainder Handling**: If the total amount sent is not perfectly divisible by three, any remainder is allocated to the first account, ensuring no funds are lost.
- **Simple Interface**: The contract provides a straightforward entry function to manage fund splitting with minimal complexity.
- **Secure Transactions**: Leveraging Aptos's secure framework, the contract ensures that all transactions are executed safely and efficiently.

## Future Scope

- **Dynamic Account Management**: Future versions could allow for dynamic addition or removal of accounts for splitting funds, providing greater flexibility.
- **Enhanced Error Handling**: Implementing more robust error-checking mechanisms to ensure valid transactions and enhance user experience.
- **Integration with DApps**: Potential integration with decentralized applications to provide fund distribution services within broader ecosystems, such as crowdfunding or educational platforms.
- **User Interface**: Developing a front-end interface to facilitate user interactions with the contract without requiring technical knowledge.

## Contract Info

### Module Name
- `0x54d77b3b4f2e6938f6f08c8a428bdc048d3bbd14f82fa62c38e58f11c413caf9::Teacher`

### Predefined Accounts
The contract includes three predefined wallet addresses for fund distribution:

- **ACCOUNT_1**: `0x7a35834489c7872dbc6881268894021a41986b6a834e37bcd8d5f17597430dd1`
- **ACCOUNT_2**: `0x790cb3bad13332674b1415836bd5b20470386ec0607705575c7904c7a035d906`
- **ACCOUNT_3**: `0xc467623f6832ded56e1460614b8a0bc269660a3b96c739da899f9d0ed2949039`

### Main Functionality
- **Function**: `split_money(account: &signer, amount: u64)`
  - **Parameters**:
    - `account`: The signer’s account initiating the transaction.
    - `amount`: The total amount of Aptos coins to be split.

### Usage
- To split funds, call the `split_money` function with the desired amount to distribute.

## Installation

1. **Prerequisites**:
   - Aptos CLI installed.
   - A funded Aptos account.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/TeacherContract.git
   cd TeacherContract
##Deployment 
Contract Address :
