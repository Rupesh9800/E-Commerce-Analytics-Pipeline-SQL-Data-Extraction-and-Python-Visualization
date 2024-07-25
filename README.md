# E-Commerce Data Analysis

This repository contains an analysis of e-commerce data, focusing on customer behavior, sales trends, and performance across various product categories. The goal is to explore the data, identify key factors affecting sales and customer behavior, and provide actionable insights for business improvement.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Overview](#data-overview)
3. [Data Cleaning](#data-cleaning)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Key Insights](#key-insights)
6. [Conclusion](#conclusion)

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

## Data Cleaning

- Removed redundant columns that do not contribute to the analysis.
- Handled missing values by imputing or removing incomplete records.
- Standardized date formats and normalized categorical variables.

## Exploratory Data Analysis (EDA)

- **Customer Distribution**: Analyzed the geographical distribution of customers, noting that São Paulo, Rio de Janeiro, and Belo Horizonte have the highest number of customers.
- **Order Trends**: In 2017, a total of 315,707 orders were placed, indicating high engagement throughout the year.
- **Sales by Product Category**: Evaluated revenue contributions by different product categories:
  - Furniture and Decoration: $114,414,100
  - Bed, Table, and Bath: $137,004,300
  - Telephony: $38,950,560
  These categories significantly contribute to overall revenue, suggesting strong customer preference.
- **Payment Preferences**: An overwhelming majority (99.9981%) of orders were paid in installments, highlighting a common payment preference.
- **Customer Distribution by State**: São Paulo has the highest number of customers, followed by Rio de Janeiro and Minas Gerais. This information is useful for targeted marketing and inventory distribution.
- **Monthly Order Patterns**: Analyzed monthly order trends for 2018, noting peaks in May and November, suggesting possible promotional events or seasonal trends.
- **Average Number of Products per Order by City**: Cities such as Padre Carvalho, Celso Ramos, and Datas show a high average number of products per order, indicating substantial purchasing behavior.
- **Price vs. Frequency**: Found a weak negative correlation (-0.106) between product price and purchase frequency, suggesting higher-priced products are purchased less frequently.
- **Revenue Contribution by Sellers**: Identified top-performing sellers based on total revenue generated, helping recognize key sellers and optimize vendor relationships.
- **Cumulative Sales per Month**: Revealed steady growth in sales with significant monthly spikes, crucial for planning sales strategies and inventory management.
- **Year-Over-Year Growth Rate**: Showed substantial growth with a 12,112.70% increase from 2016 to 2017 and a 20.00% increase from 2017 to 2018, indicating a rapidly expanding market.
- **Customer Retention Rate**: Indicated a significant percentage of customers make another purchase within six months, reflecting customer loyalty and the effectiveness of retention strategies.
- **Top Customers by Spending**: Identified high-value customers each year, providing insights for personalized marketing and enhanced shopping experiences.

## Key Insights

- **Customer Distribution by City**: São Paulo, Rio de Janeiro, and Belo Horizonte are major customer hubs, offering opportunities for targeted regional marketing.
- **Order Trends in 2017**: High order volume in 2017 reflects strong customer engagement throughout the year.
- **Sales Performance by Category**: Prioritize high-revenue categories like Furniture and Decoration, Bed, Table, and Bath, and Telephony in marketing strategies.
- **Payment Installments**: The prevalent use of installment payments suggests a need for flexible payment options.
- **Customer Distribution by State**: São Paulo, Rio de Janeiro, and Minas Gerais are key regions for targeted marketing and inventory distribution.
- **Monthly Order Count for 2018**: Peaks in May and November indicate periods of high purchasing activity, useful for promotional planning.
- **Average Number of Products per Order by City**: Higher purchasing behavior in certain cities provides insights into regional purchasing trends.
- **Correlation between Product Price and Purchase Frequency**: Higher-priced products are less frequently purchased, suggesting price sensitivity.
- **Revenue Contribution by Sellers**: Identifying top sellers can help in optimizing vendor relationships and improving sales performance.
- **Cumulative Sales per Month**: Steady growth with notable spikes helps in strategic sales and inventory planning.
- **Year-Over-Year Growth Rate**: Significant growth rates highlight an expanding market and increasing customer base.
- **Customer Retention Rate**: High retention rates indicate successful customer engagement and loyalty programs.
- **Top Customers by Spending**: Focus on high-value customers for personalized marketing and enhanced customer experiences.

## Conclusion

The analysis of the e-commerce dataset has provided valuable insights into customer behavior, sales trends, and product performance. These findings can inform strategic decisions related to marketing, inventory management, and customer engagement, ultimately driving business growth and enhancing customer satisfaction.

