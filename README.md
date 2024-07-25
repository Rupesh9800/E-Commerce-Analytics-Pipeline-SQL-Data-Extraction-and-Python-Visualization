# E-Commerce Analytics Pipeline: SQL Data Extraction and Python Visualization

This repository contains a comprehensive analysis pipeline for e-commerce data, focusing on extracting data from SQL databases and visualizing insights using Python. The goal is to understand customer behavior, sales trends, and performance across various product categories to inform strategic decisions and improve business performance.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Overview](#data-overview)
3. [Data Extraction](#data-extraction)
4. [Data Cleaning](#data-cleaning)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Key Insights](#key-insights)
7. [Conclusion](#conclusion)

## Introduction

The project aims to:
- Understand customer behavior and sales patterns in the e-commerce domain.
- Analyze the impact of various factors on sales and payment preferences.
- Provide insights that can help in strategic decision-making for marketing and inventory management.

## Data Overview

The dataset includes the following files:
- **customers.csv**: Information about customers.
- **orders.csv**: Details of orders placed.
- **sellers.csv**: Information about sellers.
- **products.csv**: Details of products.
- **geolocation.csv**: Geographical location information.
- **payments.csv**: Payment details for orders.
- **order_items.csv**: Items included in each order.

Key columns in the dataset include:
- `customer_id`: Unique identifier for a customer.
- `order_id`: Unique identifier for an order.
- `product_id`: Unique identifier for a product.
- `price`: Price of the product.
- `quantity`: Number of units purchased.
- `payment_type`: Method of payment (e.g., installment, credit card).
- `state`: Geographical location of the customer.
- `order_date`: Date when the order was placed.

## Data Extraction

Data is extracted from SQL databases and stored in CSV files for analysis. The extraction involves:
- Connecting to the SQL database.
- Running SQL queries to retrieve relevant data.
- Saving the extracted data into CSV files for further analysis.

## Data Cleaning

The data cleaning process includes:
- Removing redundant columns that do not contribute to the analysis.
- Handling missing values by imputing or removing incomplete records.
- Standardizing date formats and normalizing categorical variables.

## Exploratory Data Analysis (EDA)

- **Customer Distribution by City**: São Paulo, Rio de Janeiro, and Belo Horizonte have the highest number of customers.
- **Order Trends in 2017**: A total of 315,707 orders were placed, indicating high engagement.
- **Sales Performance by Category**: 
  - Furniture and Decoration: $114,414,100
  - Bed, Table, and Bath: $137,004,300
  - Telephony: $38,950,560
- **Payment Installments**: 99.9981% of orders were paid in installments.
- **Customer Distribution by State**: São Paulo leads in customer count, followed by Rio de Janeiro and Minas Gerais.
- **Monthly Order Count for 2018**: Peaks in May and November suggest increased purchasing activity during these months.
- **Average Number of Products per Order by City**: High average numbers in Padre Carvalho, Celso Ramos, and Datas.
- **Correlation between Product Price and Purchase Frequency**: Weak negative correlation (-0.106).
- **Revenue Contribution by Sellers**: Identified top-performing sellers.
- **Cumulative Sales per Month**: Revealed steady growth with significant spikes.
- **Year-Over-Year Growth Rate**: Notable growth rates of 12112.70% from 2016 to 2017 and 20.00% from 2017 to 2018.
- **Customer Retention Rate**: Significant percentage of customers made another purchase within six months.
- **Top Customers by Spending**: Insights into high-value customers for personalized marketing.

## Key Insights

- **Customer Distribution by City**: Major customer bases in São Paulo, Rio de Janeiro, and Belo Horizonte.
- **Order Trends in 2017**: High order volume indicates strong customer engagement.
- **Sales Performance by Category**: High revenue from categories like Furniture and Decoration, and Bed, Table, and Bath.
- **Payment Installments**: Predominant use of installment payments.
- **Customer Distribution by State**: São Paulo, Rio de Janeiro, and Minas Gerais are key states.
- **Monthly Order Count for 2018**: Peaks in certain months suggest seasonal trends.
- **Average Number of Products per Order by City**: High values in specific cities indicate substantial purchasing behavior.
- **Correlation between Product Price and Purchase Frequency**: Slight negative correlation.
- **Revenue Contribution by Sellers**: Identified key sellers for optimization.
- **Cumulative Sales per Month**: Steady growth with periodic spikes.
- **Year-Over-Year Growth Rate**: Rapid market expansion and increasing customer base.
- **Customer Retention Rate**: High retention rate suggests effective customer engagement strategies.
- **Top Customers by Spending**: Insights for targeted marketing and loyalty programs.

## Conclusion

The analysis provides a comprehensive understanding of e-commerce sales dynamics, customer behavior, and payment preferences. The insights derived from this study can help enhance marketing strategies, optimize inventory management, and improve overall business performance. The findings are valuable for e-commerce platforms looking to tailor their offerings and strategies to better meet customer needs and preferences.
