## Ferns and Petals Sales Analysis

This project aims to analyze the sales data of Ferns and Petals (FNP), a company specializing in sending gifts for various occasions such as Diwali, Raksha Bandhan, Holi, Valentine's Day, Birthdays, and Anniversaries. The objective is to uncover key insights related to sales trends, customer behavior, and product performance to help improve the company’s sales strategy and optimize customer satisfaction.

## Problem Statement

The given dataset contains details about products, orders, customers, and relevant dates. Based on this data, the following business questions are addressed:

1. **Total Revenue**: Identify the overall revenue.
2. **Average Order and Delivery Time**: Evaluate the time taken for orders to be delivered.
3. **Monthly Sales Performance**: Examine how sales fluctuate across the months of 2023.
4. **Top Products by Revenue**: Determine which products are the top revenue generators.
5. **Customer Spending Analysis**: Understand how much customers are spending on average.
6. **Sales Performance by Top 5 Products**: Track the sales performance of top 5 products.
7. **Top 10 Cities by Number of Orders**: Find out which cities are placing the highest number of orders.
8. **Revenue Comparison Between Occasions**: Compare revenue generated across different occasions.
9. **Product Popularity by Occasion**: Identify which products are most popular during specific occasions.

## Steps Taken

### 1. Checked the Datasets
- Analyzed the provided datasets to understand their structure and content.

### 2. Data Extraction
- Extracted relevant data from the datasets into Excel.

### 3. Data Transformation
- **Used Power Query Editor** to clean and transform data:
  - Extracted order months from the order date.
  - Extracted hour of delivery and calculated the difference between the order date and delivery date in days.
  - Calculated the difference between order time and delivery time in hours.
  - Merged data from multiple queries to bring the price column from the products table into the orders table.

### 4. Data Loading
- Loaded the cleaned data into Excel for further analysis.

### 5. Star Schema Model
- Created a star schema model using Power Pivot to organize the data for analysis.

### 6. Calculated KPIs
- Created a new column for **Revenue**.
- Extracted the name of the days using DAX functions in Power Pivot.

### 7. KPI Calculations
- Calculated all the required KPIs as mentioned in the problem statement using Pivot Tables.

### 8. Dashboard Creation
- Created an interactive dashboard using the insights from the Pivot Tables to visualize and present the analysis.

## Tools & Techniques Used

- **Excel**: Data extraction, transformation, and analysis.
- **Power Query Editor**: Data cleaning and transformation.
- **Power Pivot**: Star schema model and DAX functions for advanced calculations.
- **Pivot Tables**: To calculate and summarize KPIs.
- **Interactive Dashboard**: To visualize sales trends, product performance, and customer behavior.

## Outcome

The project provides a comprehensive view of Ferns and Petals' sales performance. The interactive dashboard helps the company identify key trends, track top-selling products, evaluate customer spending patterns, and compare performance across different occasions. These insights are crucial for optimizing the company’s sales strategy and improving customer satisfaction.
