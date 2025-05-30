# 💰 Rural Bank Account Management System (RBAMS)

This is a beginner-friendly Java console application that simulates a basic banking system for the **Rural Bank of Nepal**. It allows a customer to manage both **Savings** and **Current** accounts.

---

## 📌 What You Can Do

- Create a customer with Savings and Current accounts.
- Deposit money into either account.
- Withdraw money (with overdraft for Current accounts).
- Add interest to the Savings account.
- View account details.
- Handle errors when withdrawing too much money.

---

## 🧱 Class Design & OOP Concepts

This project is built using core **Object-Oriented Programming (OOP)** concepts:

### 🔹 Classes and Objects
- Each part of the system is modeled using classes (`Customer`, `BankAccount`, etc.).
- You create objects like `Customer`, `SavingsAccount`, and `CurrentAccount` in your main program.

### 🔹 Inheritance
- `SavingsAccount` and `CurrentAccount` **inherit** from the abstract class `BankAccount`.
- They reuse common features like account holder info and balance, but also define their own behavior.

### 🔹 Abstraction
- `BankAccount` is an **abstract class**. It hides common functionality and forces child classes to implement `deposit()` and `withdraw()` methods.

### 🔹 Polymorphism
- The program uses polymorphism when dealing with account types.
- You can treat `SavingsAccount` and `CurrentAccount` as `BankAccount` when adding them to the customer.

### 🔹 Encapsulation
- Data like account balance and customer name are kept **private** or **protected** and accessed through methods.

### 🔹 Exception Handling
- The program includes a custom exception class called `InsufficientBalanceException`.
- This helps handle errors when a withdrawal exceeds the allowed limit.

---

## ▶️ How to Run

1. Make sure you have Java installed (JDK 8 or higher).
2. Save all `.java` files in the same folder.
3. Open terminal or command prompt.
4. Compile the files:
   ```bash
   javac *.java

Screenshots

---![Screenshot 2025-05-30 163215](https://github.com/user-attachments/assets/047aa25e-ae44-4719-b503-50ebc46aab3e)
![Screenshot 2025-05-30 163144](https://github.com/user-attachments/assets/67683691-d26e-4c59-afd6-8881dec09af5)
![Screenshot 2025-05-30 163124](https://github.com/user-attachments/assets/b6bdefae-28c8-4cb2-bd98-93448d6ff91c)
![Screenshot 2025-05-30 163116](https://github.com/user-attachments/assets/d8a36f77-a521-421e-baeb-fa632c25a2b2)

