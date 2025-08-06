# 💰 Console-Based Budget Tracker

A simple Python-based command-line application to manage income and expenses. Built using Object-Oriented Programming principles, the app allows users to record transactions, filter them, and view summaries — all through a user-friendly CLI interface.

---

## 📌 Features

- Add income or expense transactions
- Add multiple entries in one go
- Optional notes for each transaction
- View all transactions in a clean format
- Filter by transaction type (income/expense) or category
- View financial summary: total income, total expenses & net balance
- Delete any transaction by its ID
- Data persistence using `transactions.txt`

---

## 🛠️ Technologies Used

- Python (built-in libraries only)
- File I/O
- OOP (Object-Oriented Programming)
- CLI (Command Line Interface)

---

## 🧾 File Format

Transactions are stored in `transactions.txt` using a pipe-separated format :

type|amount|category|note

Example : income|5000|Salary|July salary ; 
expense|1000|Groceries|Weekly grocery shopping


---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/budget-tracker.git
   cd budget-tracker

## Run the Script
python budget_tracker.py
