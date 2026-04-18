# SmartExpenseTracker

A premium full-stack Expense Tracker web application built using **Flask, SQLite, HTML, CSS, JavaScript, and Chart.js**.  
This project helps users manage daily expenses, set budgets, analyze spending patterns, and export reports in **PDF** and **Excel** format.

---

## Features

- User Registration and Login
- Forgot Password with OTP verification
- Secure password hashing
- Add, Edit, Delete Expenses
- Budget Limit Setup
- Budget Warning and Overflow Alerts
- Interactive Dashboard
- Category-wise Expense Analysis
- Monthly Expense Graph
- Expense Trend Graph
- Search, Filter, Sort, and Pagination
- Dark Mode / Light Mode
- Responsive Premium UI
- Export Reports in PDF and Excel
- Filtered Report Export
- Email Integration for Reports and Alerts

---

## Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- Chart.js

### Backend
- Flask (Python)

### Database
- SQLite

### Libraries Used
- Flask
- Werkzeug
- Pandas
- Openpyxl
- ReportLab

---

## Project Structure

```text
SmartExpenseTracker/
│
├── app.py
├── init_db.py
├── requirements.txt
├── README.md
│
├── static/
│   ├── style.css
│   └── script.js
│
└── templates/
    ├── base.html
    ├── login.html
    ├── register.html
    ├── forgot_password.html
    ├── verify_otp.html
    ├── reset_password.html
    ├── dashboard.html
    └── edit_expense.html
