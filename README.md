# 🏦 Banking System in C

A console-based banking system written in C that implements account management, transaction processing, and file-based data persistence with a rollback mechanism.

---

## 🚀 Features

- Account creation with auto-generated account number  
- Secure PIN setup and authentication  
- File handling for persistent data storage  
- Transaction operations:
  - Deposit  
  - Withdrawal  
  - Fund transfer  
- Rollback mechanism to maintain data consistency  
- Menu-driven console interface  

---

## 🛠️ Tech Stack

- C Programming  
- File Handling (fopen, fread, fwrite, etc.)  

---

## 📌 What This Project Does

This project simulates a basic banking system where users can:
- Create and manage accounts  
- Perform transactions like deposit, withdrawal, and transfer  
- Store account data securely using files  
- Ensure safe transactions using a rollback mechanism  

---

## 📂 Project Structure
banking-system/
│── data/ # Stored account data files
│── src/ # Source code
│── main.c # Entry point
│── README.md

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
2. Navigate to the folder:

cd banking-system

3. Compile the program:

gcc main.c -o bank

4. Run the executable:

./bank
