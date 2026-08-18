# ApexPlanet Internship — Task 2
## Exploratory Data Analysis, SQL Business Analysis & Dashboard

This project is completed as part of **Task 2 of the ApexPlanet Internship**, using a cleaned sales dataset from Task 1.

## Project Objectives

The project focuses on:

- Descriptive statistics and exploratory data analysis (EDA)
- Univariate and multivariate analysis
- Correlation analysis
- SQL-based business questions
- Filtering, aggregation, grouping, and multi-table joins
- Creating a static business dashboard
- Identifying meaningful business insights from sales data

## Dataset

The dataset contains **1,000 sales transactions** and the following fields:

- `Order_ID` — Unique order identifier
- `Order_Date` — Date when the order was placed
- `Customer_ID` — Customer identifier
- `Customer_Name` — Customer name
- `Age` — Customer age
- `Gender` — Customer gender
- `City` — Customer city
- `Product` — Product purchased
- `Category` — Product category
- `Quantity` — Number of units purchased
- `Unit_Price` — Price per unit
- `Total_Sales` — Total sales amount

## Exploratory Data Analysis

The EDA includes:

- Dataset shape and structure
- Data types
- Missing-value analysis
- Duplicate-value analysis
- Descriptive statistics
- Age distribution
- Sales distribution
- Sales by category
- Sales by city
- Sales by gender
- Monthly sales trend
- Top products by revenue
- Quantity vs. sales analysis
- Age vs. sales analysis
- Category vs. gender analysis
- Correlation heatmap

## SQL Business Analysis

SQL Server was used to answer business questions including:

1. What are the top 5 products by revenue?
2. Which category generates the highest revenue?
3. Which city generates the highest sales?
4. What is the monthly sales trend?
5. Which category has the highest average transaction value?
6. Which products generate more than the selected revenue threshold?
7. How do sales compare by gender?
8. How does product revenue compare when using a multi-table JOIN?
9. What is the overall business summary?
10. Which customers have the highest total spending?

The SQL analysis demonstrates:

- `SELECT`
- `WHERE`
- `SUM()`
- `AVG()`
- `COUNT()`
- `GROUP BY`
- `HAVING`
- `ORDER BY`
- `TOP`
- `INNER JOIN`

## Key Business Insights

Based on the analysis:

- **Total Sales:** 139,399,439.65
- **Total Orders:** 992
- **Total Customers:** 947
- **Total Quantity Sold:** 5,435
- **Average Transaction Value:** 139,399.44
- **Highest Transaction Value:** 493,677.50
- **Top Product by Revenue:** Laptop
- **Top Revenue Category:** Electronics
- **Top Sales City:** Patna
- **Highest Sales Contribution by Gender:** Male
- **Highest Monthly Sales:** March 2025

Electronics generated the highest category revenue, while Laptop was the highest-revenue individual product.

## Dashboard

A static Excel dashboard is included with:

- Total Sales KPI
- Total Orders KPI
- Customer count
- Quantity sold
- Average transaction value
- Highest transaction value
- Monthly sales trend
- Sales by category
- Top products by revenue
- Sales by city
- Supporting analysis sheets

## Project Structure

```text
ApexPlanet-Task2/
│
├── data/
│   └── Cleaned_Dataset.xlsx
│
├── notebooks/
│   └── Task2_EDA.ipynb
│
├── outputs/
│   ├── age_distribution.png
│   ├── age_vs_sales.png
│   ├── category_vs_gender.png
│   ├── correlation_heatmap.png
│   ├── monthly_sales.png
│   ├── sales_by_category.png
│   ├── sales_by_city.png
│   ├── sales_by_gender.png
│   ├── sales_distribution.png
│   ├── sales_vs_quantity.png
│   └── top_products.png
│
├── sql/
│   └── business_questions.sql
│
├── dashboard/
│   └── dashboard.xlsx
│
└── README.md
```

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft SQL Server
- Excel

## Conclusion

Task 2 provided practical experience in transforming a cleaned dataset into meaningful business insights through **EDA, SQL analysis, visualization, and dashboard design**.

The project demonstrates the complete flow from raw analytical data to business-oriented insights and visual reporting.
