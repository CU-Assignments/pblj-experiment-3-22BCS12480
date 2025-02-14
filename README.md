1. Square Root Calculator
This program takes a number as input from the user and calculates its square root.
It uses exception handling to manage invalid inputs:
If the input is non-numeric, an InputMismatchException is thrown.
If the input is negative, an IllegalArgumentException is thrown.
The program ensures a graceful exit by handling errors and always closing the scanner.
2. ATM Withdrawal System
This program simulates an ATM withdrawal process.
The user must enter a PIN to access their account. If incorrect, an InvalidPINException is thrown.
After entering a valid PIN, the user inputs the withdrawal amount:
If the amount is greater than the balance, an InsufficientBalanceException is thrown.
If the amount is negative or zero, an IllegalArgumentException is thrown.
The program ensures the remaining balance is always displayed, even in case of an error.
Uses custom exceptions for better clarity and error handling.
