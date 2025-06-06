# Expense_Tracker
Demonstration of how you can use Lambda Functions for efficient, streamlined operations.

# 🧾 Expense Tracker CLI

A simple command-line interface (CLI) tool in Python to track personal expenses by amount and category.

---

## 🚀 Features

- 📥 Add new expenses
- 📋 List all recorded expenses
- 📊 Display the total sum of expenses
- 🔍 Filter expenses by category
- ❌ Exit the program

---

## 🛠 How It Works

This script maintains an in-memory list of expenses. Each expense is stored as a dictionary with `amount` and `category`.

### Main Functions:

- `add_expense(expenses, amount, category)`: Adds a new expense.
- `print_expenses(expenses)`: Prints all expenses in a readable format.
- `total_expenses(expenses)`: Returns the sum of all expenses.
- `filter_expenses_by_category(expenses, category)`: Filters and returns expenses of a specified category.

The script uses a simple menu-driven loop in the `main()` function to interact with the user.

---

## 💻 Usage

1. **Run the script**:

   ```bash
   python expense_tracker.py

   
2. **Follow the on-screen prompts**:
``` pgsql
Expense Tracker
1. Add an expense
2. List all expenses
3. Show total expenses
4. Filter expenses by category
5. Exit
```

## 📦 Example
``` text
Enter your choice: 1
Enter amount: 25.5
Enter category: Food

Enter your choice: 2

All Expenses:
Amount: 25.5, Category: Food
```

## 📝 Notes
This is a basic in-memory tracker; data is not persisted between runs.

Suitable for educational purposes or as a base for a more advanced expense manager (e.g., with file/database storage or GUI).

## 📌 Future Improvements
Add file/database persistence.

Export expenses to CSV.

Add date/time to expense entries.

Use a GUI framework (e.g., Tkinter, PyQt).

``` rust
Let me know if you'd like me to save or upload this as a file (`README.md`) as well.
```








