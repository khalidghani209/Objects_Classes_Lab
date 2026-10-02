# BankAccount Class

A C++ class for simulating basic banking operations and managing account data within a Bank Account Management System.

## Data Dictionary

| Attribute           | Data Type     | Description                                      |
|---------------------|---------------|--------------------------------------------------|
| `accountNumber`     | `std::string` | The unique identifier for the bank account.      |
| `accountHolderName` | `std::string` | The full name of the individual holding the account. |
| `balance`           | `double`      | The current financial balance of the account.    |

## Methods List

| Method Signature                                  | Return Type   | Description                                                                 |
|---------------------------------------------------|---------------|-----------------------------------------------------------------------------|
| `BankAccount()`                                   | (Constructor) | Default constructor. Initializes empty strings and a `0.0` balance.         |
| `BankAccount(accountNumber, accountHolderName, balance)` | (Constructor) | Parameterized constructor. Initializes the object with specific account data. |
| `getAccountNumber() const`                        | `std::string` | Gets the account's unique identification number.                            |
| `getAccountHolderName() const`                    | `std::string` | Gets the name of the account holder.                                        |
| `getBalance() const`                              | `double`      | Gets the current available balance.                                         |
| `setAccountHolderName(newName)`                   | `void`        | Updates the account holder's name.                                          |
| `deposit(amount)`                                 | `void`        | Adds a specified positive amount to the account balance.                    |
| `withdraw(amount)`                                | `void`        | Deducts a specified amount from the balance if sufficient funds exist.      |
