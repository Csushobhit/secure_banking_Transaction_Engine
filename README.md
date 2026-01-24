# Secure Banking Transaction Engine (Java)

A **console-based Java banking system** that simulates real-world banking operations like **account creation, deposits, withdrawals, and balance checks**.  
Built using **Object-Oriented Programming (OOP)** with proper **security validation** and **exception handling**.

---

## ✅ Features

### 🏦 Account Management
- Create a new bank account
- Supports:
  - **Savings Account**
  - **Current Account**

### 💰 Transactions
- Deposit money
- Withdraw money (with balance validation)
- Check current balance

### 🔐 Security
- **PIN-based validation** for sensitive operations like:
  - Withdrawal
  - Balance enquiry

### ⚠ Error Handling
Custom exceptions are used for safe execution:
- `InvalidAmountException` → for invalid deposit / withdraw / initial balance input
- `InsufficientBalanceException` → when withdrawal exceeds available balance

Also handles:
- `InputMismatchException` → when incorrect input type is entered

---

## 📂 Project Structure

```text
secure_banking_Transaction_Engine/
│── BankPortal.java
│── BankAccount.java
│── SavingsAccount.java
│── CurrentAccount.java
│── InvalidAmountException.java
│── InsufficientBalanceException.java
