# 💰 OpenBudget — Open Source Personal Finance Manager

**OpenBudget** is an open source web application to help you manage your personal finances, import and standardize bank statements, track multiple accounts, and view detailed financial transactions.

---

## 🚀 Core Features

### 📥 Import Bank Statements
- Support for `.csv` and `.xlsx` files
- Simple upload interface for importing your statements
- Automatic detection or manual selection of the bank format (e.g. ING, Boursorama, etc.)
- Preview imported data before confirmation

### 🧹 Standardize and Process Data
- Clean and map columns (date, amount, label, etc.)
- Detect duplicate entries
- Associate the uploaded statement with an existing account
- Insert transactions into a centralized database

### 🏦 Multi-Account Management
- Create, edit, and delete bank accounts
- Link imported statements to the correct account
- Overview of all accounts (total balance, number of transactions, last statement date)

### 📊 Transaction Viewer
- Display transactions per account
- Key details: date, amount, label
- Filter and sort by date, amount, keywords, etc.
- Grouped views by month or custom periods

---

## 🔐 Planned Features

- User authentication & multi-user support
- Automatic categorization of expenses
- Monthly budgeting
- Visual charts and analytics
- Data export


## Technic stack

| Component       | Technology                          |
|------------------|--------------------------------------|
| Frontend        | [Nuxt.js](https://nuxt.com/) (Vue 3) |
| Backend         | [Django](https://www.djangoproject.com/) + Django REST Framework |
| Database        | [PostgreSQL](https://www.postgresql.org/) |