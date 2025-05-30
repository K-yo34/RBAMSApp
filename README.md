# 💰 Rural Bank Account Management System (RBAMS)

This is a simple **Java console-based application** that simulates a basic banking system for the **Rural Bank of Nepal**. It allows users to perform basic banking operations like deposit, withdraw, and interest calculation.

---

## 📦 What This Project Includes

This project uses the following Java classes:

- `RBAMSApp.java`  
  → The main application. It interacts with the user and performs banking operations.

- `BankAccount.java`  
  → An abstract class that contains common properties and methods for all accounts.

- `SavingsAccount.java`  
  → Inherits from `BankAccount`. It allows adding interest to the balance.

- `CurrentAccount.java`  
  → Inherits from `BankAccount`. Allows overdraft withdrawals up to Rs. 5000.

- `Customer.java`  
  → Stores customer name and their multiple bank accounts.

- `InsufficientBalanceException.java`  
  → A custom exception that is thrown when withdrawal exceeds the allowed balance or overdraft.

---

## ▶️ How to Run This Project

1. Make sure you have **Java (JDK)** installed.
2. **Clone** this repository or download the `.java` files.
3. Open a terminal in the project directory.
4. Compile all the files:
   ```bash
   javac *.java
