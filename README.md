# Business-Financial-Data-Analytics-with-SQL-and-Power-BI
This project showcases **professional financial data analysis** using a synthetic dataset of bank customers, accounts, and transactions. The dataset simulates real-world financial operations and is analyzed using **PostgreSQL** and visualized in **Power BI**.
---

## 📂 Project Structure

```
📁 finance-data-analytics/
│
├── data/
│   ├── customers.csv
│   ├── accounts.csv
│   └── transactions.csv
│
├── sql/
│   ├── create_tables.sql
│   ├── load_data.sql
│   └── analysis_queries.sql
│
├── powerbi/
│   └── Finance_Insights_Dashboard.pbix
│
├── README.md
```

---

## 📊 Dataset Overview

### 1. `customers.csv`  
Contains basic customer demographics.

| Column       | Description         |
|--------------|---------------------|
| CustomerID   | Unique ID           |
| Name         | Full name           |
| Age          | Age in years        |
| Gender       | Male/Female         |
| Region       | Customer location   |

### 2. `accounts.csv`  
Contains details about customer accounts.

| Column         | Description                |
|----------------|----------------------------|
| AccountID      | Unique account ID          |
| CustomerID     | Linked to customers        |
| AccountType    | Savings, Current, Business |
| OpeningBalance | Initial balance            |
| OpeningDate    | Date the account was opened|

### 3. `transactions.csv`  
Contains transaction logs per account.

| Column         | Description                |
|----------------|----------------------------|
| TransactionID  | Unique transaction ID      |
| AccountID      | Linked to accounts         |
| Date           | Transaction date & time    |
| TransactionType| Debit or Credit            |
| Amount         | Transaction value          |
| Channel        | POS, ATM, Online, Branch   |

---

## 🔍 Analysis Questions (SQL)

- Customers per region
- Average account balance by type
- Multi-account customers
- Debit/Credit volume by channel
- Top debit accounts
- Monthly trends and averages

---

## 📈 Power BI Visualizations

- KPI cards (customers, accounts, transactions)
- Monthly debit vs credit trend
- Region-wise transaction heatmap
- Top customers by transaction amount
- Transaction channel distribution
- Account type balance comparison

---

## 🛠 How to Use

1. Import CSVs into PostgreSQL (`\COPY` or pgAdmin)
2. Run SQL scripts to create schema and analyze
3. Open Power BI file and connect to database or CSVs

---

## 🚀 Technologies Used

- PostgreSQL
- Power BI
- Python (for data generation)
- SQL

---

## 📬 Contact

For feedback, improvements, or questions, feel free to reach out.
