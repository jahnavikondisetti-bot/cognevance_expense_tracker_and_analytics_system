
# 💰 Cognevance Expense Tracker & Financial Analytics

A Python-based personal finance management application developed as part of my **Python Development Internship at Cognevance Technologies**.

This application helps users manage their income and expenses, generate monthly and yearly financial reports, and visualize financial performance using Matplotlib charts.

---

## 📌 Features

### 🔐 User Authentication
- User Registration
- User Login
- User-specific financial records
- Password security

### 💵 Income Management
- Add Income
- View Income Records
- Search Income
- Update Income
- Delete Income
- Calculate Total Income

### 💸 Expense Management
- Add Expenses
- View Expense Records
- Search Expenses
- Update Expenses
- Delete Expenses
- Category Validation
- Calculate Total Expenses
- Category-wise Expense Summary

### 📊 Financial Reports
- Monthly Financial Reports
- Yearly Financial Reports
- Monthly Income and Expense Comparison
- Overall Financial Summary
- Savings Calculation

### 📈 Data Visualization
- Monthly Income vs Expenses Bar Chart
- Expense Category Pie Chart
- Monthly Savings Trend Line Chart
- Yearly Financial Comparison Chart
- Automatic Chart Generation and Saving

---

## 🛠 Technologies Used

- Python 3
- SQLite
- Matplotlib
- SQL
- VS Code
- Git and GitHub

---

## 📂 Project Structure

```text
Cognevance_Expense_Tracker/
│
├── __pycache__/
│
├── charts/
│   ├── expense_category.png
│   ├── income_expense_2026.png
│   ├── savings_trend_2026.png
│   └── yearly_comparison.png
│
├── data/
│   └── expense_tracker.db
│
├── screenshots/
│   ├── Exit message.png
│   ├── Expense management.png
│   ├── Financial reports.png
│   ├── Income management.png
│   ├── Login page.png
│   ├── Main menu.png
│   └── registration.png
│
├── analytics.py
├── authentication.py
├── database.py
├── expenses.py
├── income.py
├── main.py
├── reports.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/jahnavikondisetti-bot/cognevance_expense_tracker_and_analytics_system.git
```

### 2. Navigate to the Project Folder

```bash
cd Cognevance_Expense_Tracker
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python main.py
```

The application initializes the SQLite database and required tables automatically.

---

## 📸 Application Screenshots

### 1. Main Menu

![Main Menu](<screenshots/Main menu.png>)

### 2. User Registration

![Registration](<screenshots/registration.png>)

### 3. User Login

![Login Page](<screenshots/Login page.png>)

### 4. Income Management

![Income Management](<screenshots/Income management.png>)

### 5. Expense Management

![Expense Management](<screenshots/Expense management.png>)

### 6. Financial Reports

![Financial Reports](<screenshots/Financial reports.png>)

### 7. Application Exit

![Exit Message](<screenshots/Exit message.png>)

---

## 📊 Financial Analytics Charts

### 1. Monthly Income vs Expenses

![Income Expense Chart](<charts/income_expense_2026.png>)

### 2. Expense Category Distribution

![Expense Category Chart](<charts/expense_category.png>)

### 3. Monthly Savings Trend

![Savings Trend Chart](<charts/savings_trend_2026.png>)

### 4. Yearly Financial Comparison

![Yearly Comparison Chart](<charts/yearly_comparison.png>)

---

## 🧮 Financial Calculation

The application calculates savings using:

```text
Total Savings = Total Income - Total Expenses
```

It also generates category-wise expense summaries and monthly and yearly financial comparisons.

---

## 🗄️ Database Management

SQLite is used to store application data.

The database maintains:
- User account information
- Income transactions
- Expense transactions
- Transaction categories
- User-specific financial records

The database is stored in the `data/` directory.

---

## 🎯 Project Objectives

- Develop a real-world Python application.
- Implement CRUD operations using SQLite.
- Understand database connectivity and SQL queries.
- Implement user authentication.
- Generate monthly and yearly financial reports.
- Perform financial calculations.
- Visualize financial data using Matplotlib.
- Apply modular programming concepts.

---

## 🚀 Future Enhancements

- Graphical User Interface (GUI).
- Export reports to PDF and Excel.
- Monthly budget management.
- Spending alerts and notifications.
- Advanced financial analytics.

---

## 👨‍💻 Internship Details

**Organization:** Cognevance Technologies

**Project:** Cognevance Expense Tracker

**Domain:** Python Development

**Level:** Level 2

---

## 👨‍💻 Author

**Kondisetty Jahnavi**

Python Development Intern

---

## 📜 License

This project is developed for educational and internship purposes.