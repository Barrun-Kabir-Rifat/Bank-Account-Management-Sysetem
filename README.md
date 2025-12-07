# Bank-Account-Management-Sysetem
Bank Management System (C++ Program)

This is a simple console-based Bank Management System written in C++.
It demonstrates basic concepts of Object-Oriented Programming (OOP) such as classes, objects, encapsulation, and member functions.

The program allows a user to:

Create a bank account

Deposit money

Withdraw money

Display account information

Exit the program

📌 Features
1. Account Creation

When the program starts, the user is prompted to enter:

Name of depositor

Account number

Initial balance

2. Deposit Money

Users can deposit an amount into their bank account.
The balance is updated accordingly.

3. Withdraw Money

Allows the user to withdraw money.
If the withdrawal amount exceeds the balance, the program displays:

Insufficient balance

4. Display Account Information

Shows:

Depositor name

Account number

Current balance

5. Menu System

A simple menu allows users to repeatedly choose actions until they exit.
goto and system("cls") are used to refresh the screen.

📂 Code Structure
Class: Bank

Contains:

Private data members

name_of_depositor

account_name

balance

Public member functions

Constructor → Takes initial input

deposit()

withdraw()

display()

Main Function

Creates an object of class Bank

Displays menu using labels and goto

Handles user actions

▶️ Running the Program
1. Save the code as:
bank.cpp

2. Compile using g++
g++ bank.cpp -o bank

3. Run the program
./bank

📘 Example Output
____Bank Project____
Enter Name of the depositor: John
Enter Account number: 12345
Enter Initial balance: 5000

________Main Menu:________
1.Deposit Money
2.Withdraw money
3.Display Account Information
4.Exit
Choose an option:

⚠️ Notes

system("cls") and system("pause") are Windows-specific commands.

Using goto is generally discouraged; loops are recommended.

cin >> name_of_depositor will not accept full names with spaces.

💡 Future Improvements

Replace goto with a while loop

Use getline() to handle multi-word names

Add input validation

Support multiple accounts

Persist data using files
