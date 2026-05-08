# Walmart Sales Data Analysis using SQL and Python

![Python](https://img.shields.io/badge/Python-3.8-blue)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-darkblue)
![License](https://img.shields.io/badge/License-MIT-green)

---

# Project Overview

![Project Pipeline](https://github.com/najirh/Walmart_SQL_Python/blob/main/walmart_project-piplelines.png)

This project focuses on end-to-end sales data analysis using SQL and Python. The workflow includes data cleaning, feature engineering, database integration, and business insight generation from Walmart sales data.

The primary objective of this project is to strengthen practical SQL skills by solving real-world business problems using structured queries and analytical thinking.

---

# Objectives

- Perform data cleaning and preprocessing using Python
- Load structured data into MySQL and PostgreSQL
- Write SQL queries to solve business problems
- Analyze sales trends and customer behavior
- Generate meaningful business insights from transactional data

---

# Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Data preprocessing |
| Pandas | Data manipulation |
| MySQL | SQL analysis |
| PostgreSQL | Database management |
| SQLAlchemy | Database connection |
| Kaggle API | Dataset download |
| VS Code | Development environment |

---

# Dataset

Dataset Source:  
https://www.kaggle.com/najir0123/walmart-10k-sales-datasets

The dataset contains transactional sales records including:
- Branch
- City
- Product category
- Quantity
- Revenue
- Payment methods
- Ratings
- Profit margins

---

# Project Workflow

## 1. Environment Setup

Tools Used:
- Python
- VS Code
- MySQL
- PostgreSQL

Install required libraries:

```bash
pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
```

---

## 2. Dataset Collection

Download the dataset using Kaggle API:

```bash
kaggle datasets download -d <dataset-path>
```

---

## 3. Data Cleaning

Tasks performed:
- Removed duplicate records
- Handled missing values
- Corrected data types
- Formatted currency values
- Validated cleaned data

---

## 4. Feature Engineering

Created additional calculated columns such as:

```python
df["Total Amount"] = df["unit_price"] * df["quantity"]
```

---

## 5. Database Integration

- Connected Python with MySQL and PostgreSQL using SQLAlchemy
- Created database tables
- Imported cleaned data into SQL databases
- Verified successful data loading

---

## 6. SQL Analysis

Performed SQL analysis to answer business questions related to:
- Revenue trends
- Best-selling product categories
- Branch performance
- Peak sales periods
- Customer purchasing behavior
- Payment method analysis
- Profitability analysis

---

# Sample Business Questions

```sql
Which branch generated the highest revenue?

Which product category has the highest sales?

What are the peak shopping hours?

Which payment method is most preferred by customers?

Which city has the highest profit margin?
```

---

# Project Structure

```plaintext
├── data/
├── sql_queries/
├── notebooks/
├── README.md
├── requirements.txt
└── main.py
```

---

# Key Insights

- Identified top-performing branches and product categories
- Analyzed customer payment preferences
- Determined peak shopping periods
- Compared revenue and profitability across cities
- Evaluated customer purchasing patterns

---

# License

This project is licensed under the MIT License.

---

# Acknowledgments

- Walmart Sales Dataset from Kaggle
- Retail analytics and business intelligence case studies
