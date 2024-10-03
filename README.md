

# Bank Account Management System

This project simulates a basic Bank Account Management System in Python. It allows users to create a bank account, deposit money, withdraw money, and check their account balance.

## Features

- **Create Account**: Users can create a bank account by entering their name and initial balance.
- **Deposit Money**: Deposits a specified amount into the account.
- **Withdraw Money**: Withdraws a specified amount from the account, provided sufficient funds are available.
- **Check Balance**: Displays the current balance of the account.
- **User Interface**: Simple text-based interface for interaction.

## Requirements

- Python 3.x

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/bank-account-management.git
   cd bank-account-management
   ```

2. **Run the script**:
   ```bash
   python bank_account.py
   ```

3. **Follow the prompts**:
   - Enter the account holder's name and initial balance.
   - Choose from options to deposit money, withdraw money, check balance, or exit.

## Usage

1. **Creating an Account**:
   - Enter the account holder's name and initial balance.
   - A bank account is created with the provided details.

2. **Deposit Money**:
   - Choose option 1 to deposit money.
   - Enter the amount to deposit. The new balance is displayed after successful deposit.

3. **Withdraw Money**:
   - Choose option 2 to withdraw money.
   - Enter the amount to withdraw. The new balance is displayed if the withdrawal is successful.

4. **Check Balance**:
   - Choose option 3 to check the current balance.
   - The current balance of the account holder is displayed.

5. **Exit**:
   - Choose option 4 to exit the program.
   - A farewell message is displayed, and the program terminates.

## Example

```
Welcome to the Bank Account Management System!

Enter account holder's name: John Doe
Enter initial balance: 1000

Options:
1. Deposit Money
2. Withdraw Money
3. Check Balance
4. Exit

Choose an option (1-4): 1
Enter amount to deposit: 500
Successfully deposited $500. New balance: $1500.

...

Thank you for using the Bank Account Management System!
```

## Notes

- Ensure Python 3.x is installed on your system.
- This project provides a basic example of managing bank accounts with simple functionalities.
- Feel free to expand the project by adding features such as transaction history, account numbers, or authentication mechanisms.

