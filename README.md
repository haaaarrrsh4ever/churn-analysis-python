
# 📊 Customer Churn Analysis Using Python

<p align="center">

  <b>Customer Analytics | Exploratory Data Analysis | Business Insights</b>

  <br><br>

  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange" />
  <img src="https://img.shields.io/badge/Seaborn-Visualization-4C72B0" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white" />

</p>

---

## 📌 Project Overview

This project focuses on analyzing customer churn behavior using Python, SQL (SQLite), and data visualization techniques.

The primary objective is to understand customer subscription patterns, identify churn-related factors, evaluate customer retention, and generate meaningful business insights from customer, subscription, and support data.

The project follows a structured data analytics workflow, starting from database extraction and data cleaning to exploratory data analysis, feature engineering, statistical analysis, and visualization.

---

## 🎯 Project Objectives

- Analyze customer churn and retention rates.
- Perform data cleaning and preprocessing.
- Extract data from SQLite databases using SQL queries.
- Integrate customer, subscription, and support datasets.
- Identify churn patterns across different subscription plans.
- Calculate important business performance metrics.
- Analyze customer support escalations and their relationship with churn.
- Create meaningful visualizations to communicate analytical findings.
- Generate actionable insights to understand customer behavior.

---

## 🛠️ Technologies & Tools Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations and feature engineering |
| SQLite | Database connectivity and SQL queries |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive development and analysis |

---

## 📂 Project Structure

```text
churn-analysis-python/
│
├── data/
│   └── customer_churn_data.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── reports/
│   └── churn_analysis_report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🔄 Project Workflow

### 1. Database Connection & Data Extraction

- Established a connection between Python and SQLite.
- Retrieved available database tables using SQL queries.
- Extracted customer, subscription, and support records.
- Loaded database tables into Pandas DataFrames.

### 2. Data Cleaning & Preprocessing

Performed data cleaning operations to improve data quality:

- Renamed columns for better readability.
- Removed unnecessary columns.
- Converted date columns into appropriate datetime formats.
- Standardized categorical values.
- Identified and handled missing values.
- Examined duplicate support records.

### 3. Data Integration & Feature Engineering

- Combined customer, subscription, and support datasets using Customer ID.
- Handled multiple support records for individual customers.
- Created a new `churn_flag` column.
- Calculated customer tenure in days.
- Created customer churn risk categories.
- Prepared data for further analysis.

### 4. Exploratory Data Analysis (EDA)

Analyzed important customer and business metrics:

- Customer Churn Rate
- Customer Retention Rate
- Churn by Subscription Plan
- Average Revenue Per User (ARPU)
- Average Customer Tenure
- Revenue at Risk
- Customer Support Escalation Rate
- Average Complaints Per User
- Correlation Between Escalations and Churn

### 5. Data Visualization

Used Matplotlib and Seaborn to explore patterns and relationships.

Visualizations included:

- Monthly Churn Trend
- Churn by Plan Type
- Churn by State
- Correlation Heatmap
- Pairplot
- Categorical Comparisons
- Statistical Relationships

### 6. SQL Operations Using Python

Practiced database operations using SQLite:

- Database creation.
- Table creation.
- Record insertion.
- Data retrieval using SELECT.
- Data aggregation using GROUP BY.
- Integration of SQL queries with Pandas.

---

## 📈 Key Performance Indicators (KPIs)

The following results were obtained from the current project dataset.

| KPI | Result |
|---|---:|
| Customer Churn Rate | 28.57% |
| Customer Retention Rate | 71.43% |
| Average Revenue Per User (ARPU) | 18.85 |
| Average Customer Tenure | 1,582 Days |
| Revenue at Risk | 73.94 |
| Escalation Rate | 19.05% |
| Average Complaints Per User | 0.43 |

**Note:** These metrics represent the current sample dataset and should not be interpreted as industry-wide statistics.

---

## 🔍 Key Analytical Findings

### 1. Customer Churn

The overall churn rate was 28.57%, while the retention rate was 71.43%.

### 2. Churn by Subscription Plan

| Subscription Plan | Churn Rate |
|---|---:|
| Basic | 60.00% |
| Premium | 14.29% |
| Standard | 22.22% |

The Basic subscription plan recorded the highest churn rate in the sample dataset.

### 3. Customer Support Analysis

The analysis explored customer support escalations and their relationship with customer churn.

A correlation value of approximately 0.77 was obtained in the current analysis. This indicates a positive association in the sample, not proof of causation.

### 4. Revenue Analysis

The average revenue per user was 18.85, and the calculated revenue at risk was 73.94 based on the monthly charges of churned customers.

---

## 📊 Visualizations

The project includes multiple visualizations to understand customer behavior, subscription patterns, and churn trends.

**Visual analysis performed using:**

- Matplotlib
- Seaborn
- Correlation Matrix
- Heatmaps
- Pairplots
- Bar Charts
- Time Series Visualization

---

## ⚙️ Installation & Setup

Follow these steps to run the project on your local machine.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/churn-analysis-python.git
```

### Step 2: Navigate to the Project Folder

```bash
cd churn-analysis-python
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Project Notebook

Navigate to:

```text
notebooks/churn_analysis.ipynb
```

Run the notebook cells sequentially.

**Important:** Ensure the required dataset and database connection paths are correctly configured before running the notebook.

---

## 📦 Python Libraries

The project uses the following Python libraries:

```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import sqlite3
```

---

## 📄 Project Deliverables

- Jupyter Notebook containing the complete analysis.
- Data cleaning and preprocessing workflow.
- SQL database operations.
- Exploratory data analysis.
- Feature engineering.
- Statistical analysis.
- Data visualizations.
- PDF project report.

---

## 🚀 Skills Demonstrated

- Python for Data Analytics
- Data Cleaning & Preprocessing
- SQL & SQLite
- Exploratory Data Analysis (EDA)
- Data Manipulation using Pandas
- Numerical Computing using NumPy
- Feature Engineering
- Data Visualization
- Statistical Analysis
- Business Intelligence & Analytical Thinking

---

## 👨‍💻 Author

**Harsh Yadav**

Aspiring Data Analyst

**Technical Skills:**

Python | SQL | Excel | Power BI | Tableau | Snowflake

📍 Navi Mumbai, Maharashtra, India

---

## ⭐ Acknowledgements

This project was developed as part of my practical learning and hands-on experience in Data Analytics.

The project helped me strengthen my understanding of Python, SQL, data preprocessing, exploratory data analysis, and business-oriented analytical techniques.

---

<p align="center">

  <b>Thank you for visiting this project!</b>

  <br>

  If you find this project useful, consider giving it a ⭐ on GitHub.

</p>
