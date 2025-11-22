# E-commerce Data Analysis with SQL: Sales & Product Performance Insights

## Project Goals for SQL Analysis

The primary goal of this project is to perform a data analysis on e-commerce transactions using SQL to generate relevant business insights. This analysis will include evaluating sales performance over time, identifying high-performing products and categories, and understanding customer behavior. More specifically, the objectives of this project are as follows:
* Analyze Monthly Sales Performance: To identify the month with the highest total discounted transaction value in 2021 to pinpoint the most effective sales period in terms of discounts.
* Evaluate Top-Performing Product Categories: To find the product categories with the largest transaction value in 2022 to determine which market segments are the most profitable.
* Understand Long-Term Sales Trends: To compare transaction values across categories between 2021 and 2022 to identify which categories are experiencing sales growth and decline, providing insights into market trends.
* Identify Payment Method Preferences: To display the top five most popular payment methods in 2022 based on the total unique transaction value, which is useful for optimizing payment strategies.
* Analyze Specific Product Performance: To sort and compare five specific products (Samsung, Apple, Sony, Huawei, Lenovo) based on their total transaction value to understand the competitive position of each product.

* ## Data Source

* For this analysis, we leverage a simulated e-commerce dataset that mirrors two years of operations from a fictional company, Tokopedia. The data is specifically designed for analytical purposes, structured into four relational tables: order_detail for capturing every transaction, sku_detail for product information, customer_detail for customer data, and payment_detail for payment methods. This data architecture enables us to efficiently extract valuable business insights.

* ## Problem Statements

* Q: During the transactions that occurred in 2021, which month had the highest total transaction value (after_discount)? Use is_valid = 1 to filter the transaction data.
* Q: During transactions in 2022, which category generated the highest transaction value? Use is_valid = 1 to filter the transaction data.
* Q: Compare the transaction values of each category in 2021 with 2022. State which categories experienced an increase and which categories experienced a decrease in transaction value from 2021 to 2022. Use is_valid = 1 to filter the transaction data.
* Q: Display the top 5 most popular payment methods used during 2022 (based on the total number of unique orders). Use is_valid = 1 to filter the transaction data.
* Q: Rank these 5 products based on their transaction value:
  Samsung, 
  Apple, 
  Sony, 
  Huawei, 
  Lenovo. 

  Use is_valid = 1 to filter the transaction data.

## Monthly Performance Analysis for 2021

