# DataAnalyticsProject
## Analyzing Consumer Behavior in Online Retail: Insights from a UK E-Commerce Dataset
## Overview
This repository contains a comprehensive analysis of an e-commerce dataset as part of the requirements for the Professional Certificate in Data Analytics. The project involves data cleaning, exploratory data analysis, feature engineering, and predictive modeling to gain insights into the sales patterns and customer behavior.

## Dataset
The dataset used for this project contains transactional data from an e-commerce platform. It includes details such as the invoice number, stock code, description of the product, quantity sold, invoice date, unit price, customer ID, and country.

## Attributes

InvoiceNo: Invoice number, a unique identifier for each transaction
StockCode: Product code
Description: Product description
Quantity: The quantity of each product sold per transaction
InvoiceDate: Date and time of the transaction
UnitPrice: Price per unit of the product
CustomerID: Unique identifier for each customer
Country: Country of the customer

## Analysis Workflow
1. Data Cleaning:
- Handled missing values in 'Description' and 'CustomerID'.
- Removed outliers and negative values in 'Quantity' and 'UnitPrice'.

2. Feature Engineering:
- Created a new feature, TotalSales, calculated as the product of 'Quantity' and 'UnitPrice'.

3. Exploratory Data Analysis:
- Conducted exploratory data analysis to understand sales trends, customer behavior, and product performance.

4. Predictive Modeling:
- Implemented a simple linear regression model to predict TotalSales based on Quantity.
- Evaluated model performance using metrics such as Mean Squared Error (MSE) and $R^2$
  score.

## Files in the Repository

- Jupyter Notebook: Contains the code, visualizations, and detailed analysis.
- slide.md: Presentation slides summarizing key findings and insights.
- Dataset: Raw (data.csv) and cleaned data (cleaned_data.csv) used for the analysis.

## Tools and Technologies
- Python: Used for data cleaning, analysis, and modeling.
- Pandas: Employed for data manipulation and analysis.
- Matplotlib: Utilized for data visualization.
- Scikit-learn: Used for building and evaluating the predictive model.

## Conclusion
This project provides insights into e-commerce sales trends and patterns, contributing valuable information for decision-making and strategy formulation.
