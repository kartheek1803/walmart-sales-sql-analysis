# Walmart Sales SQL Analysis

A complete SQL analysis project using the Walmart Sales dataset.  
This project demonstrates SQL skills used in real business analytics: revenue analysis, customer behavior, product performance, and time-series insights.

---

# 📂 Project Structure
```
walmart-sales-sql-analysis/
│
├── 01_Dataset/
│     └── walmart_sales.csv
│
├── 02_Database_Schema/
│     └── create_tables.sql
│
├── 03_Data_Load/
│     └── load_data.sql
│
├── 04_Analysis_Queries/
│     ├── revenue_analysis.sql
│     ├── customer_behavior.sql
│     ├── product_performance.sql
│     └── time_series_analysis.sql
│
├── 05_ER_Diagram/
│     └── er_diagram.png
│
└── README.md
```

---

# 🏗️ Database Schema

### Table: `walmart_sales`

| Column | Type | Description |
|--------|------|-------------|
| invoice_id | VARCHAR | Primary Key |
| branch | VARCHAR | Store branch |
| city | VARCHAR | City of branch |
| customer_type | VARCHAR | Normal / Member |
| gender | VARCHAR | Male / Female |
| product_line | VARCHAR | Category of product |
| unit_price | DECIMAL | Price per product |
| quantity | INT | Items purchased |
| tax | DECIMAL | Tax on purchase |
| total | DECIMAL | Total cost |
| date | DATE | Purchase date |
| time | TIME | Purchase time |
| payment_method | VARCHAR | Cash / Card |
| cogs | DECIMAL | Cost of goods sold |
| gross_margin_pct | DECIMAL | Profit margin |
| gross_income | DECIMAL | Profit earned |
| rating | DECIMAL | Customer rating |

---

# 📊 Key SQL Analyses Included

### 1️⃣ Revenue Analysis
- Total revenue  
- Revenue per product line  
- Revenue per city  
- Revenue per month  

### 2️⃣ Customer Behavior
- Average rating by gender  
- Payment method trends  
- Customer type distribution  

### 3️⃣ Product Performance
- Top-selling products  
- Best rated product lines  
- Most profitable categories  

### 4️⃣ Time-Series Analysis
- Monthly sales trends  
- Hourly peak purchase times  
- Day-of-week performance  

---

# 🖼️ ER Diagram

Place your image here:

```
05_ER_Diagram/er_diagram.png
```

To display it in GitHub:

```md
![ER Diagram](05_ER_Diagram/er_diagram.png)
```

---

# 🚀 How to Run This Project

### 1. Create Database & Table
Run:
```
02_Database_Schema/create_tables.sql
```

### 2. Load the Dataset
Run:
```
03_Data_Load/load_data.sql
```

### 3. Run SQL Analysis Queries
Open files in:
```
04_Analysis_Queries/
```

---

# 🛠️ Tech Stack
- MySQL
- SQL Aggregations
- Joins & Grouping
- Window Functions
- CSV Dataset
- Time-series SQL

---

# 👤 Author
**Kartheek — SQL Developer | Data Analyst**
