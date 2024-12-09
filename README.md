
# Customer Banking Application

This project implements a customer banking system in Python to manage and calculate interest for savings and Certificate of Deposit (CD) accounts.

## Overview

- **Savings Account Management**: Calculate interest earned and update balance for savings accounts.
- **CD Account Management**: Manage CD accounts, calculate interest, and update balances.
- **User-Friendly Interface**: Prompts users for input and displays updated balances and interest earned.

## File Structure

- `Account.py`: Defines the base `Account` class with methods for setting and managing account balances and interest.
- `savings_account.py`: Implements the `create_savings_account` function to handle savings account logic.
- `cd_account.py`: Implements the `create_cd_account` function to manage CD account functionality.
- `customer_banking.py`: Main script that integrates all modules and provides a user interface for the banking application.

## Installation
Note: These instructions assume an understanding of Git. Ensure you have Python 3.x installed on your machine.

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SegoviaJ/customer_banking.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd customer_banking
   ```

3. **Run the Application**:
   ```bash
   python customer_banking.py
   ```

## Usage

1. **Savings Account**:
   - Enter the savings account balance, APR, and duration in months.
   - The application calculates and displays the interest earned and updated balance.

2. **CD Account**:
   - Enter the CD account balance, APR, and duration in months.
   - The application calculates and displays the interest earned and updated balance.

## Modules and Their Functionality

- **Account.py**:
  - `Account` class with methods:
    - `set_balance`: Updates the account balance.
    - `set_interest`: Updates the interest earned.

- **savings_account.py**:
  - `create_savings_account` function:
    - Accepts balance, interest rate, and duration.
    - Calculates interest using the formula: `interest = balance * (interest_rate/100 * months/12)`.
    - Updates and returns the balance and interest earned.

- **cd_account.py**:
  - `create_cd_account` function:
    - Accepts balance, interest rate, and duration.
    - Calculates interest using the same formula as savings accounts.
    - Updates and returns the balance and interest earned.

- **customer_banking.py**:
  - Main script:
    - Handles user input for savings and CD accounts.
    - Calls respective functions and displays results.

## Example

When running the script:
```bash
Enter the current savings account balance: 6825.75
Enter the current savings account APR: 2.75
Enter the savings account term: 24
Savings Interest Earned: $375.42
New Savings Balance: $7201.17

Enter the current CD account balance: 10356.87
Enter the current CD account APR: 7.24
Enter the CD account term: 72
CD Interest Earned: $4499.02
New CD Balance: $14855.89
```


## Contact

For questions or feedback, please reach out to the repository owner.
