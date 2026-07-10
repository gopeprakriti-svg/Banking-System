# 🏦 Bank Account Management System (C)

A simple Bank Account Management System developed in the C programming language. This project demonstrates file handling, structures, and basic banking operations using binary files.

---

## 📌 Features

- ✅ Create a New Account
- 💰 Deposit Money
- 💸 Withdraw Money
- 📄 Balance Enquiry
- 💾 Data Stored Permanently Using Binary File (`bank.dat`)

---

## 🛠 Technologies Used

- C Programming Language
- GCC / MinGW Compiler
- File Handling
- Structures
- VS Code (Recommended)

---

## 📂 Project Structure

```
Banking-System/
│
├── banking_system.c     # Main source code
├── bank.dat             # Binary database (created automatically)
└── README.md            # Project documentation
```

---

## ⚙️ How It Works

The program stores all account information inside a binary file named:

```
bank.dat
```

Each account contains:

- Account Number
- Account Holder Name
- Balance

Whenever you create, deposit, or withdraw money, the file is updated automatically.

---

## ▶️ How to Compile

Using GCC:

```bash
gcc banking_system.c -o banking_system
```

---

## ▶️ Run

### Windows

```bash
banking_system.exe
```

### Linux / macOS

```bash
./banking_system
```

---

## 📋 Menu

```
===== BANK ACCOUNT MANAGEMENT SYSTEM =====

1. Create Account
2. Deposit
3. Withdraw
4. Balance Enquiry
5. Exit
```

---

## 📖 Functions Used

### `createAccount()`

Creates a new bank account and stores it in `bank.dat`.

---

### `deposit()`

Searches an account by account number and deposits money.

---

### `withdraw()`

Withdraws money from an account after checking sufficient balance.

---

### `balanceEnquiry()`

Displays account holder information and current balance.

---

## 💾 Data Structure

```c
struct Account
{
    int accNo;
    char name[50];
    float balance;
};
```

---

## 📷 Sample Output

```
===== BANK ACCOUNT MANAGEMENT SYSTEM =====

1. Create Account
2. Deposit
3. Withdraw
4. Balance Enquiry
5. Exit

Enter your choice: 1

Enter Account Number: 1001
Enter Name: John Doe
Enter Initial Balance: 5000

Account Created Successfully!
```

---

## 📌 Concepts Covered

- Structures
- Functions
- File Handling
- Binary Files
- Loops
- Switch Case
- Conditional Statements
- Sequential File Search

---

## ⚠ Limitations

- No password protection
- Duplicate account numbers are not checked
- No account deletion feature
- No account update feature
- No transaction history
- Single-user application

---

## 🚀 Future Improvements

- Login System
- PIN Authentication
- Delete Account
- Update Account Details
- Transfer Money
- Transaction History
- Interest Calculation
- Admin Dashboard
- Search by Name
- Account Statement Generation

---

## 👨‍💻 Author

**PRAKRITI**

B.Tech Computer Science Student

---

## 📜 License

This project is free to use for educational and learning purposes.
