# BankApplication
Online Bank Account Management System
Project Overview:
This Online Bank Account Management System is a simple Java-based command-line application that allows users to perform various banking operations like creating an account, depositing money, withdrawing funds, and checking their account balance. The system is designed with robust exception handling to ensure smooth operation even in the event of invalid inputs, negative deposit/withdrawal amounts, or insufficient funds.

Features:
Account Creation: Users can create an account by entering their name.

Deposit: Users can deposit money into their account, with validation to ensure the amount is positive.

Withdraw: Users can withdraw money, with checks for sufficient funds and a positive withdrawal amount.

View Balance: Users can view their current account balance.

Exception Handling: The system uses custom exceptions to handle invalid amounts and insufficient funds gracefully.

Technologies Used:
Java: Core programming language for implementing the system logic.

Custom Exceptions: InvalidAmountException and InsufficientFundsException for handling specific error scenarios.

Scanner: For user input handling and menu navigation.
