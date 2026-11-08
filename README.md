# India E-commerce Sales Analysis (2025)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sahilbharti1601/india-ecommerce-sales-analysis/blob/main/india_ecommerce_sales_analysis.ipynb)

Exploratory data analysis of 15,000 Amazon India orders from 2025 using Python, focusing on sales trends, product categories, payment methods, returns, and whether sales rise during the Diwali festive season.

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Google Colab

## Dataset
15,000 orders with 10 columns: order and customer IDs, date, product category and name, quantity, unit price, total sales (INR), payment method, and delivery status. Source: Kaggle (synthetic dataset — see findings below).

## What I Did
1. **Data cleaning & validation:** checked for missing values and duplicates, converted dates, and verified that Quantity × Unit Price matches Total Sales on every row.
2. **Business overview:** total revenue, orders, customers, and average order value.
3. **Monthly trend analysis:** tested whether sales spike around Diwali.
4. **Category, payment, and return analysis.**

## Key Findings
- ₹111.8 crore in revenue from 15,000 orders by 7,259 customers.
- Sales were flat all year (₹8.5–9.8 crore per month), with **no Diwali spike**.
- All five categories contributed almost equally (₹21.7–22.8 crore each).
- Each payment method had ~25% of orders; return rates were 31–34% in every category.

## Data Quality Finding
The perfectly even distributions, random product pricing, and absence of any seasonal pattern indicate this dataset is **synthetically generated**. Validating data before drawing business conclusions is a key analyst skill; in a real setting, I would flag this to the data owner before the results are used for decisions.

## Files
- `india_ecommerce_sales_analysis.ipynb` — full analysis notebook
- `amazon_sales_2025_INR-selected-columns.csv` — dataset

## How to Run
Click the **Open in Colab** button above, upload the CSV file to Colab, and run all cells.
