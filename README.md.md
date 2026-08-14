# AdventureWorks Business Analytics Project

## Project Overview

This project analyzes AdventureWorks sales data using **Python and Pandas** to understand business performance, sales trends, customer behavior, product performance, and regional sales.

The project covers the complete data analysis workflow, including **data loading, data cleaning, transformation, exploratory data analysis (EDA), aggregation, ranking, and visualization**.

The goal is to turn raw sales data into meaningful business insights that can support better decision-making.

---

## Business Objectives

The analysis focuses on answering questions such as:

- How are sales performing across different years?
- Which product categories generate the most revenue?
- Which products are the best-selling?
- Who are the top customers?
- Which territories generate the highest sales?
- How does sales performance change over time?
- What customer characteristics are associated with sales performance?
- Which products and categories require further attention?

---

## Tools & Technologies

- **Python**
- **Pandas** – Data cleaning, transformation, and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Analysis and documentation
- **CSV** – Source data

---

## Project Structure

```text
AdventureWorks_Project/
│
├── data/
│   ├── Sales.csv
│   ├── calender.csv
│   ├── teritory.csv
│   ├── customer.csv
│   ├── products.csv
│   ├── prodcts category.csv
│   └── products subcategory.csv
│
├── outputs/
│   └── Charts and visualizations
│
├── python/
│   └── AdventureWorks_Analysis.ipynb
│
└── README.md
```

---

## Dataset

The project uses data from the AdventureWorks dataset.

The data contains information related to:

- Sales transactions
- Products
- Product categories
- Customers
- Regions and territories
- product sub categories
- calender


The datasets were cleaned and combined where required to create a suitable structure for analysis.

---

## Data Cleaning & Preparation

The following data preparation steps were performed:

- Loaded multiple CSV files using Pandas
- Inspected datasets using `head()`, `info()`, and descriptive statistics
- Checked for missing values
- Handled problematic records
- Converted date columns into appropriate datetime formats
- Standardized data types
- Combined datasets using `merge()` where relationships existed
- Combined similar datasets using `concat()` where required
- Created derived columns for analysis

### Derived Columns

Examples of calculated columns include:

- Year
- Month
- Month Name
- Quarter
- Customer Name
- Age
- Age Group
- Revenue

Revenue was calculated based on product price and order quantity.

---

## Exploratory Data Analysis

The analysis includes several business-focused aggregations and comparisons.

### Sales Trend Analysis

Sales were analyzed across different years and months to identify:

- Overall sales growth
- Yearly performance
- Monthly trends
- Changes in sales over time

### Product Analysis

Product performance was analyzed using:

- Quantity sold
- Revenue generated
- Product rankings
- Top-performing products
- Product performance by category

### Category Analysis

Sales were grouped by product category to identify the categories contributing the most to overall business performance.

### Customer Analysis

Customer-level analysis was performed to identify:

- Top customers
- Customer purchase quantity
- Customer revenue contribution

### Territory Analysis

Sales were analyzed across different territories to understand regional performance.

### Customer Demographic Analysis

Additional analysis was performed using customer attributes such as:

- Occupation
- Education
- Gender
- Age groups
- Income-related information

---

## Key Analyses Performed

Some of the major analyses included:

- Sales by year
- Monthly sales trends
- Sales by product category
- Top 10 products by quantity sold
- Top customers by quantity purchased
- Territory-wise sales
- Occupation-wise sales
- Education and income analysis
- Gender-wise sales
- Product ranking
- Top products within categories

---

## Visualizations

The project contains charts generated during the analysis and stored in the `outputs` folder.

Examples include:

- Sales trend by year
- Monthly sales trend
- Sales by category
- Top-selling products
- Customer performance
- Territory performance


These visualizations make it easier to identify patterns and communicate business insights.

---

## Key Insights

The analysis helps identify:

- The strongest-performing sales periods
- High-performing product categories
- Best-selling products
- High-value customers
- Strong and weak territories
- Customer segments contributing to sales
- Products that may require additional business attention

The detailed results and visualizations can be found in the Jupyter Notebook located in the `python` folder.

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone <repository-url>
```

### 2. Navigate to the project

```bash
cd AdventureWorks_Project
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Open the Jupyter Notebook

Navigate to the `python` folder and open:

```text
AdventureWorks_Analysis.ipynb
```

### 5. Run the notebook

Run the notebook cells sequentially to reproduce the analysis and visualizations.

---

## Project Skills Demonstrated

This project demonstrates practical skills in:

- Python for Data Analysis
- Pandas
- NumPy
- Data Cleaning
- Data Transformation
- Data Merging
- Data Aggregation
- GroupBy Analysis
- Pivot Tables
- Ranking
- Date & Time Analysis
- Exploratory Data Analysis
- Data Visualization
- Business Insight Generation

---

## Author

**Deekshith**

Data Analyst | Python | SQL | Excel | Power BI