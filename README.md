# Diwali Sales Data Analysis

## Project Overview

In this project, I performed an analysis of Diwali sales data using Python. By examining the sales data during this festive period, the goal was to gain insights into consumer behavior, popular products, purchasing patterns, and key sales trends. These insights can be useful for businesses to better understand their market and optimize their marketing strategies and product offerings during such high-sales seasons.

## Dataset

The dataset used in this analysis includes the following columns:
- **User_ID**: Unique identifier for the customer
- **Cust_name**: Customer name
- **Product_ID**: Unique identifier for the product
- **Gender**: Customer gender
- **Age**: Customer age
- **Marital_Status**: Indicates if the customer is married or not (0 = Not married, 1 = Married)
- **State**: The state where the purchase was made
- **Zone**: The geographical zone of the state
- **Occupation**: The occupation of the customer
- **Product_Category**: Category of the purchased product
- **Orders**: Number of orders placed by the customer
- **Amount**: Total amount spent on purchases

We also added an **Age_Group** column for easier analysis of different age brackets.

## Key Steps in the Analysis

1. **Data Cleaning**: We handled missing data, removed unrelated or blank columns, and ensured that the data types were consistent for analysis.
2. **Exploratory Data Analysis (EDA)**: We performed in-depth EDA using visualizations to identify trends, such as:
   - **Gender Analysis**: Which gender made more purchases and had higher spending power.
   - **Age Group Analysis**: Which age groups were the most active during the Diwali sales.
   - **State Analysis**: Top states in terms of the number of orders and sales.
3. **Handling Missing Values**: Missing values in the `Amount` column were replaced with the mean values within each product category.

## Insights

- **Gender**: The analysis showed that most buyers were females, and they also had higher purchasing power compared to males.
- **Age Group**: The 26-35 age group had the highest number of buyers, especially female buyers, during the Diwali sale.
- **State**: The top-performing states, in terms of orders and sales, included Maharashtra, Uttar Pradesh, and Karnataka.

## Instructions to View the Project

To view the detailed analysis and visualizations, click on **Diwali_Sales_Analysis.ipynb** to access the Jupyter Notebook.
