# 💰 Personal Expense Tracker (Python Backend)

**Author:** Prabudh Sharma  
🔗 **GitHub Profile:** https://github.com/sharmaprabudh  
📂 **Project Repository:** https://github.com/sharmaprabudh/PERSONAL-EXPENSE-TRACKER-PYTHON-BACKEND  
💼 **LinkedIn:** https://www.linkedin.com/in/prabudh-sharma-680235205/

---

## 📌 Project Overview
This project is a **Python backend-based Personal Expense Tracker** that helps users log, categorize, and monitor their daily expenses. It provides a **menu-driven command-line interface (CLI)** for easy interaction and supports **monthly budget tracking with CSV-based persistent file storage**.

The application allows users to:
- Add daily expenses
- Categorize transactions
- Track monthly spending
- Compare expenses with budget
- Save and reload expense history
- Continue tracking across multiple sessions

---

## 🎯 Objectives
- Build a Python backend expense management system
- Categorize daily expenses
- Track monthly budget limits
- Implement CSV file handling
- Create a menu-driven CLI interface
- Ensure persistent expense storage

---

## 🏗️ Core Features

### ✅ Add Expense
Users can add:
- Date (`YYYY-MM-DD`)
- Category (Food, Travel, Shopping, etc.)
- Amount spent
- Expense description

Stored format:
```python
{
    "date": "2024-09-18",
    "category": "Food",
    "amount": 15.50,
    "description": "Lunch with friends"
}
```

---

### ✅ View Expenses
Displays all stored expenses with:
- Date
- Category
- Amount
- Description

Includes:
- Data validation
- Incomplete record skipping
- Clean formatted display

---

### ✅ Budget Tracking
Users can:
- Set monthly budget
- Track total spending
- Compare expenses with budget

System alerts:
- ⚠️ Budget exceeded warning
- ✅ Remaining balance display

Example:
```text
You have 150 left for the month
```

---

### ✅ Save & Load Expenses
Implemented using **CSV file handling**:
- Save all expenses to CSV
- Load expenses automatically on startup
- Continue previous session data

CSV columns:
- Date
- Category
- Amount
- Description

---

### ✅ Interactive CLI Menu
Menu options:
```text
1. Add Expense
2. View Expenses
3. Track Budget
4. Save Expenses
5. Exit
```

The program runs in a loop until the user exits.

---

## 🔄 Project Workflow
```text
Start Program
     ↓
Load Previous CSV Data
     ↓
Show CLI Menu
     ↓
Add / View / Track Budget
     ↓
Save Data to CSV
     ↓
Exit Program
```

---

## 📂 Tech Stack
- Python
- CSV File Handling
- CLI (Command Line Interface)
- Dictionaries
- Lists
- Functions
- Conditional Statements
- Loops

---

## 🚀 Business / User Value
- Better personal finance management
- Daily spending awareness
- Prevents overspending
- Budget discipline
- Easy local data persistence
- Beginner-friendly Python backend logic

---

## 📈 Future Enhancements
- Add SQLite database integration
- Create Flask/Django API backend
- Add expense visualization charts
- Add monthly report generation
- Convert CLI into web dashboard
- Add user authentication

---

## ▶️ How to Run
```bash
python expense_tracker.py
```

---

## 👨‍💻 Author
**Prabudh Sharma**  
🔗 GitHub: https://github.com/sharmaprabudh  
📂 Repository: https://github.com/sharmaprabudh/PERSONAL-EXPENSE-TRACKER-PYTHON-BACKEND  
💼 LinkedIn: https://www.linkedin.com/in/prabudh-sharma-680235205/

---

## ⭐ Project Outcome
Successfully built a **Python backend CLI-based personal finance tracker** with expense logging, budget monitoring, CSV persistence, and a user-friendly interactive menu system for daily financial management.
