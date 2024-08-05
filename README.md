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
