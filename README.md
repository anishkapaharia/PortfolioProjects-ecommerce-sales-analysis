# PortfolioProjects-ecommerce-sales-analysis
End-to-end E-Commerce Sales Data Analysis with Python and Tableau


# E-Commerce Sales Analysis Dashboard

This project presents a comprehensive data analysis and visualization workflow on an e-commerce retail dataset. Using Python (pandas, matplotlib) and Tableau, it explores sales trends, customer behavior, product performance, and cancellation impacts.

---

## Dataset

The analysis is based on a transactional dataset with fields like:

- InvoiceNo (transaction identifier)
- StockCode (product code)
- Description (product description)
- Quantity (number of units sold, negative for cancellations)
- InvoiceDate (date and time of transaction)
- UnitPrice (price per unit)
- CustomerID (unique customer identifier)
- Country (customer country)

---

## Analysis Walkthrough (Based on `EcommerceProject.ipynb`)

### 1. Data Cleaning & Preparation
- Removed duplicates and handled missing CustomerIDs
- Separated valid orders (positive quantity) from cancelled orders (negative quantity)
- Extracted date components from InvoiceDate for time-based analysis

### 2. Sales Trends Over Time
- Calculated daily and monthly revenue using `Quantity * UnitPrice`
- Visualized revenue trends showing seasonal spikes and dips
- Tracked number of orders per month to analyze business volume changes over time

### 3. Product-Level Analysis
- Identified top-selling products by quantity and revenue
- Highlighted products with highest cancellation quantities
- Used this insight to understand inventory risks and popular products

### 4. Customer Analysis
- Found top 10 customers by total revenue
- Calculated average order value per customer
- Segmented repeat vs one-time customers to inform retention strategies

### 5. Cancellation Impact
- Quantified revenue loss due to cancellations
- Analyzed cancellation frequency by product and over time

---

## Interactive Dashboards (Tableau)

Two dashboards summarize these analyses for easier business consumption:

- **Dashboard 1: Sales Overview**
  - Monthly revenue bar chart
  - Number of orders line chart

- **Dashboard 2: Product & Customer Insights**
  - Top products by sales and cancellations
  - Customer revenue and order patterns

---

## How to Use This Project

1. Open `EcommerceProject.ipynb` for step-by-step data exploration.
2. Review the `valid_orders.csv` and `cancelled_orders.csv` for cleaned data snapshots.
3. Open Tableau dashboards (`.twbx` files) with Tableau Desktop or Reader to interact with visual insights.

---

## Skills & Tools Demonstrated

- Data cleaning and preprocessing with pandas
- Time series and aggregate analysis
- Visualization with Matplotlib and Seaborn
- Customer segmentation and product analysis
- Building interactive Tableau dashboards

---

## Contact

Connect with me on [LinkedIn](https://linkedin.com/in/anishkapaharia)

---

Thank you for reviewing my project!
