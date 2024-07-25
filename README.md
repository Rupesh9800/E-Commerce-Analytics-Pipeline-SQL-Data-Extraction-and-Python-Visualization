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

- **Customer Distribution**: Analyzed the geographical distribution of customers, noting that São Paulo, Campinas, and Belo Horizonte are major hubs.
- **Order Trends**: Examined order volumes over time, identifying peak periods and seasonal trends.
- **Sales by Product Category**: Evaluated revenue contributions by different product categories, with high performance in "Bed Table Bath" and "Furniture Decoration."
- **Payment Preferences**: Found that nearly all orders were paid in installments, indicating a common payment preference.
- **Price vs. Frequency**: Investigated the relationship between product price and purchase frequency, finding a slight negative correlation.
- **Monthly Order Patterns**: Analyzed monthly order trends to forecast future demand.

## Key Insights

- **Geographical Distribution**: São Paulo and Minas Gerais have the highest customer counts, suggesting potential for targeted regional marketing.
- **Category Performance**: High revenue categories include "Bed Table Bath" and "Health Beauty," which should be prioritized in marketing strategies.
- **Payment Trends**: The predominant use of installment payments highlights a need for flexible payment options.
- **Order Trends**: Seasonal variations and monthly trends can guide inventory and promotional planning.
- **Customer Behavior**: High-value customers and frequent buyers provide opportunities for loyalty programs and personalized offers.

## Conclusion

The analysis provides a comprehensive understanding of e-commerce sales dynamics, customer behavior, and payment preferences. The insights derived from this study can help enhance marketing strategies, optimize inventory management, and improve overall business performance. The findings are valuable for e-commerce platforms looking to tailor their offerings and strategies to better meet customer needs and preferences.
