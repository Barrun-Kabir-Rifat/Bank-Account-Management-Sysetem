# 🏦 Bank Management System (C++)

A simple console-based **Bank Management System** written in C++.  
This project demonstrates fundamental **Object-Oriented Programming (OOP)** concepts such as classes, objects, encapsulation, and member functions.

---

## 📌 Features

- Create a bank account with:
  - Depositor name  
  - Account number  
  - Initial balance  
- Deposit money  
- Withdraw money with balance check  
- Display account details  
- User-friendly menu loop  

---

## 🧱 Class Structure

### **Class: `Bank`**

| Type | Member | Description |
|------|--------|-------------|
| Private | `string name_of_depositor` | Depositor's name |
| Private | `string account_name` | Account number |
| Private | `int balance` | Current account balance |
| Public Method | `Bank()` | Constructor to initialize an account |
| Public Method | `deposit(int amount)` | Adds money to balance |
| Public Method | `withdraw(int amount)` | Deducts money with validation |
| Public Method | `display()` | Prints account information |

---
## 🚀 Program Flow
____Bank Project____
Enter Name of the depositor: John
Enter Account number: 12345
Enter Initial balance: 5000

________Main Menu:________
1. Deposit Money
2. Withdraw Money
3. Display Account Information
4. Exit
Choose an option:

