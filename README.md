# AdventureWorks Business Analytics

## 📊 Project Overview

This project is an end-to-end **Business Analytics project** using the AdventureWorks dataset.

The objective is to analyze sales performance, customers, products, and regional performance using **Python and Power BI**, and convert raw business data into meaningful insights and interactive dashboards.

The project follows a complete analytics workflow:

**Raw Data → Data Cleaning → Exploratory Data Analysis → Data Modeling → DAX → Visualization → Business Insights**

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
- **Power BI**
  - Power Query
  - DAX
  - Data Modeling
  - Interactive Visualizations
- **CSV**
- **Git & GitHub**

---

## 📁 Dataset

The project uses the AdventureWorks business dataset containing information related to:

- Sales
- Products
- Customers
- Territories/Regions
- Resellers
- Salespersons
- Salesperson Regions
- Targets

Sales data from **2020, 2021, and 2022** was used for the analysis.

---

# 🔄 Project Workflow

```text
                    AdventureWorks Raw Data
                              │
                              ▼
                     Data Loading in Python
                              │
                              ▼
                       Data Cleaning
                              │
                              ▼
                    Exploratory Data Analysis
                              │
                              ▼
                     Processed Data
                              │
                              ▼
                      Power BI Import
                              │
                              ▼
                       Data Modeling
                              │
                              ▼
                         DAX Measures
                              │
                              ▼
                    Interactive Dashboard
                              │
                              ▼
                     Business Insights
```

---

# 🐍 Python Analysis

Python was used for data preparation, cleaning, and exploratory data analysis.

### Data Cleaning

The following activities were performed:

- Loaded multiple CSV files using Pandas
- Combined yearly sales data
- Checked data types
- Converted date columns
- Identified missing values
- Handled errors and invalid records
- Removed problematic CustomerKey records
- Checked duplicate records
- Created calculated columns
- Prepared datasets for further analysis

### Feature Engineering

Additional columns were created, including:

- Year
- Month
- Month Name
- Quarter
- Customer Name
- Age
- Age Group
- Revenue

### Exploratory Data Analysis

The Python analysis explored:

- Revenue by year
- Revenue by month
- Product performance
- Customer performance
- Regional performance
- Order trends
- Quantity trends
- Customer-related metrics

### Python Notebook

```text
python/
└── AdventureWorks_Analysis.ipynb
```

---

# 📊 Power BI Dashboard

Power BI was used to transform the processed data into an interactive business intelligence dashboard.

### Power Query

Power Query was used for:

- Data transformation
- Data type correction
- Removing duplicates
- Handling errors
- Handling missing values
- Appending yearly sales data
- Preparing tables for the data model

### Data Model

The Power BI model contains tables related to:

- Sales
- Product
- Customer
- Territory
- Calendar

Relationships were created between the relevant tables to support analysis.

---

# 📐 DAX Measures

Several DAX measures were created for business analysis.

### Sales Metrics

- Total Revenue
- Total Orders
- Total Customers
- Total Quantity

### Average Metrics

- Average Order Value
- Average Quantity per Order
- Average Revenue per Customer
- Average Revenue per Product

### Time Intelligence

- Previous Year Revenue
- YoY Growth
- YoY Growth %
- YTD Revenue
- YTD Revenue Growth

---

# 📈 Dashboard Pages

## 1. Sales Overview

Provides an overall view of business performance.

Key metrics include:

- Total Revenue
- Total Orders
- Total Customers
- Total Quantity
- Average Order Value
- Revenue trends

## 2. Product Analysis

Analyzes product-level performance.

The page includes:

- Top products by revenue
- Product revenue performance
- Product quantity
- Product comparisons
- Top 10 products

## 3. Region Analysis

Analyzes sales performance across different regions and territories.

Key analysis includes:

- Revenue by region
- Orders by region
- Customer distribution
- Regional performance comparison

---

# 🎯 Business Questions

### Sales

- How is revenue changing over time?
- How many orders are being generated?
- What is the average order value?
- How does current revenue compare with the previous year?

### Products

- Which products generate the most revenue?
- Which products have the highest sales volume?
- Which products contribute most to overall business performance?

### Customers

- How many customers are purchasing?
- What is the average revenue generated per customer?
- How does customer activity change over time?

### Regions

- Which regions generate the highest revenue?
- Which regions have the highest number of customers?
- How does regional performance differ?

---

# 📂 Project Structure

```text
AdventureWorks-Business-Analytics/
│
├── README.md
├── .gitignore
│
├── data/
│   ├── raw/
│   │   ├── Sales_2020.csv
│   │   ├── Sales_2021.csv
│   │   ├── Sales_2022.csv
│   │   ├── Product.csv
│   │   ├── Customer.csv
│   │   ├── Territory.csv
│   │   └── ...
│   │
│   └── processed/
│       └── cleaned_data.csv
│
├── python/
│   └── AdventureWorks_Analysis.ipynb
│
├── powerbi/
│   └── AdventureWorks_Dashboard.pbix
│
└── outputs/
    ├── charts/
    └── dashboard/
```

---

# 💡 Key Skills Demonstrated

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Business Analytics
- Customer Analytics
- Product Analytics
- Regional Analytics
- Data Modeling
- Power Query
- DAX
- Time-Series Analysis
- KPI Development
- Dashboard Development
- Python/Pandas
- Power BI
- Git/GitHub

---

# 🚀 End-to-End Analytics

This project demonstrates how a Data Analyst can work with raw business data and take it through the complete analytics lifecycle:

```text
Raw Business Data
       ↓
Python / Pandas
       ↓
Cleaning & Transformation
       ↓
Exploratory Analysis
       ↓
Processed Dataset
       ↓
Power BI
       ↓
Data Model
       ↓
DAX Measures
       ↓
Interactive Dashboard
       ↓
Business Insights
```

---

# 📌 Conclusion

The AdventureWorks Business Analytics project demonstrates an end-to-end approach to data analysis by combining **Python for data preparation and exploratory analysis** with **Power BI for data modeling, DAX calculations, visualization, and business reporting**.

The project provides insights into sales, customers, products, and regional performance while demonstrating the practical application of data analytics tools in a business environment.

---

## 👤 Author

**Data Analyst**

Skills: Python | SQL | Excel | Power BI | Pandas | DAX | Data Analytics
