# Automated-Sales-Reporting-Python
Automated sales reporting and data analysis using Python and Pandas.


## 📌 Project Overview

This project demonstrates a complete **Python + Pandas sales data analysis workflow** using Google Colab.

The project takes a raw sales CSV dataset through a structured pipeline:

**LOAD → INSPECT → CLEAN → TRANSFORM → CALCULATE → FILTER → GROUP → RANK → REPORT → EXPORT**

The goal is to practice Python fundamentals together with practical Pandas data-cleaning, analysis, KPI calculation, and reporting skills.

## 🎯 Objectives

- Load and inspect a sales dataset
- Understand rows, columns, data types, and statistics
- Clean column names and text values
- Handle missing values and duplicate records
- Convert dates and numeric values correctly
- Validate existing business fields
- Calculate sales, cost, profit, and profit margin
- Filter and sort important records
- Analyze performance by region, product, category, channel, and salesperson
- Rank top-performing orders and products
- Generate business insights
- Export cleaned data and a JSON summary

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- JSON
- CSV
- Google Colab
- GitHub

## 📊 Dataset

The sales dataset contains transaction-level information such as:

- Order ID
- Order Date
- Product
- Category
- Region
- Quantity
- Unit Price
- Unit Cost
- Sales Channel
- Payment Method
- Salesperson
- Sales
- Total Cost
- Profit
- Profit Margin

## 🔄 Project Workflow

### 1. Load
Import the raw CSV dataset into a Pandas DataFrame.

### 2. Inspect
Review the first and last rows, shape, columns, index, data types, dataset information, descriptive statistics, unique values, and value frequencies.

### 3. Clean
- Standardize column names
- Check and handle missing values
- Detect and remove duplicate records when appropriate
- Convert dates and numeric fields
- Clean text values

### 4. Transform & Validate

Core business relationships:

- **Sales = Quantity × Unit Price**
- **Total Cost = Quantity × Unit Cost**
- **Profit = Sales − Total Cost**
- **Profit Margin = (Profit ÷ Sales) × 100**

Useful date fields include Order Year, Order Month, and Order Day.

### 5. Calculate KPIs

- Total Sales
- Total Cost
- Total Profit
- Average Order Value
- Highest Order
- Lowest Order
- Total Orders
- Average Profit
- Average Profit Margin

### 6. Filter & Sort

The project analyzes high-value orders, low-profit orders, specific regions, products, categories, sales channels, and highest/lowest sales records.

### 7. Group Analysis

Using Pandas `groupby()`:

- Sales by Region
- Profit by Region
- Sales by Product
- Profit by Product
- Sales by Category
- Sales by Sales Channel
- Salesperson Performance

### 8. Ranking

- Top 10 orders by sales
- Top 5 products by sales
- Top salesperson
- Best region
- Best category
- Most profitable product

## 📈 Business Questions

The analysis is designed to answer:

- What are the total sales, cost, and profit?
- How many unique orders are there?
- Which region generates the most sales and profit?
- Which products sell the most?
- Which products are most profitable?
- Which category performs best?
- Which sales channel performs best?
- Who is the top salesperson?
- Are there high-value orders with low profit?
- What important business patterns or problems can be identified?

## 📁 Project Outputs

```text
cleaned_sales.csv
sales_summary.json
```

**cleaned_sales.csv** — cleaned version of the sales dataset.

**sales_summary.json** — structured summary containing key metrics such as total sales, total cost, total profit, total orders, average profit, and average profit margin.

## 📂 Repository Structure

```text
Automated-Sales-Reporting-Python/
│
├── README.md
├── python_week_1_project.ipynb
│
├── data/
│   └── sales_csv.csv
│
└── output/
    ├── cleaned_sales.csv
    └── sales_summary.json
```

## 🧹 Data Quality Practices

This project follows these data-cleaning practices:

- Preserve the original/raw dataset
- Inspect before making changes
- Handle missing values based on column meaning
- Validate data types
- Handle invalid conversions deliberately
- Check duplicate records
- Verify the dataset after cleaning
- Avoid recreating columns that are already correct

## 💡 Skills Demonstrated

- Python Programming
- Pandas Data Analysis
- Data Cleaning
- Data Transformation
- Functions
- Exception Handling
- CSV and JSON File Handling
- KPI Analysis
- GroupBy Analysis
- Filtering and Sorting
- Ranking
- Business Data Analysis
- Automated Reporting

## 🚀 Project Status

**Completed — Week 1 Python + Pandas Project**

Built and practiced in **Google Colab** as part of a structured Python learning roadmap.

---

### 🔑 Core Pipeline

**LOAD → INSPECT → CLEAN → TRANSFORM → CALCULATE → FILTER → GROUP → RANK → REPORT → EXPORT**

