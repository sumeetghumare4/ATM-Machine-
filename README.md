# Simple ATM Machine

This project is a simple simulation of an ATM machine using Python. It allows users to create a pin, deposit money, withdraw money, and check their balance. The code demonstrates basic concepts of object-oriented programming, including class methods and constructors.

## Class: `Atm`

### Methods

- `__init__(self)`: Initializes the ATM object with a pin and balance, and displays the menu.
- `menu(self)`: Displays the menu and prompts the user to choose an action.
- `create_pin(self)`: Prompts the user to create a pin.
- `deposit(self)`: Prompts the user to enter their pin and the amount to deposit.
- `withdraw(self)`: Prompts the user to enter their pin and the amount to withdraw.
- `check_balance(self)`: Prompts the user to enter their pin and displays the current balance.

### Usage

1. **Initialize the ATM Object**

   ```python
   atm = Atm()


**Functionality:**

* Users can create a PIN during their first interaction.
* The program validates user input for menu selection and PIN entry.
* Users can deposit and withdraw funds, with checks for sufficient balance.
* Users can check their current account balance.

**Running the Code:**

1. Save the code as `atm.py`.
2. Open a terminal or command prompt and navigate to the directory where you saved the file.
3. Run the script using the following command:

**Code Breakdown:**

* The `Atm` class represents the ATM machine.
* The constructor (`__init__`) initializes the object with a starting balance of 0 and prompts the user for an action.
* The `menu` function displays options for creating a PIN, depositing, withdrawing, checking balance, or exiting.
* User input is validated for each menu option.
* The `create_pin` function allows users to set a PIN.
* The `deposit` and `withdraw` functions validate user input for PIN and amount.
    * Deposits increase the balance.
    * Withdrawals are only successful with sufficient funds.
* The `check_balance` function allows users to view their current balance with a valid PIN.

**Limitations:**

* This is a simple simulation and does not connect to a real bank account.
* Security features are limited for educational purposes.

**Further Development:**

* Implement error handling for invalid user input.
* Add features like transaction history or account details.
* Enhance security measures for real-world application.

I hope this README.md helps you understand the functionality and usage of the ATM machine code!
