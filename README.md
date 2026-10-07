# TechMart SQL Analysis

## Project Overview

This project analyzes TechMart retail data using SQL and Python to identify employee performance patterns, product sales trends, customer purchasing behavior, and store-category revenue performance.

The analysis covers four related tables:

- `Employee_Records`
- `Product_Details`
- `Customer_Demographics`
- `Sales_Transactions`

## Business Objectives

The project focuses on four key business questions:

1. Analyze employee performance by location.
2. Identify top-selling products by category.
3. Analyze customer purchasing behavior.
4. Analyze Electronics and Accessories sales by employee, store, and customer loyalty status, while calculating total revenue by store-category pair for ranking and comparison.

## Data Preparation

The data was reviewed and cleaned for:

- Missing values
- Inconsistent data formats
- Duplicate identifiers
- Unmatched relationships between related tables

The analysis also validated relationships between employees, products, customers, and sales transactions.

## SQL Skills Demonstrated

- Filtering with `WHERE`
- Aggregation with `SUM()`, `AVG()`, and `COUNT()`
- `GROUP BY` and `HAVING`
- `JOIN` and `LEFT JOIN`
- Common Table Expressions (CTEs)
- Window functions with `RANK()` and `PARTITION BY`
- Data cleaning using `UPDATE` and `CASE`
- Data validation and relationship checks

## Key Insights

### Employee Performance

- Phoenix generated the highest total employee sales performance at 53,000.
- Chicago had the highest average employee performance at 3,875 despite having only 8 employees.

### Product Sales

- Keyboard was the top-selling Accessories product with 111 units sold.
- Mouse and Tablet tied as the top-selling Electronics products with 74 units each.

### Customer Purchasing Behavior

- Customer 13 was the highest-spending customer, with 440 in total spending across 8 transactions.
- Customer 12 was the second-highest spender at 400 across 6 transactions and was enrolled in the loyalty program.

### Store-Category Revenue

- Los Angeles Electronics generated the highest store-category revenue at 5,510.
- Los Angeles Accessories ranked second at 4,190.
- London Accessories had the lowest revenue at 960.

## Business Recommendations

- Benchmark high-performing locations and identify practices that can be applied to lower-performing stores.
- Monitor inventory for high-demand products.
- Recognize and learn from high-performing employees.
- Develop targeted retention strategies for high-spending customers.
- Investigate lower-performing store-category combinations.
- Improve customer data quality, particularly loyalty-program information.

## Tools

- SQL
- SQLite
- Python
- Pandas
- Jupyter Notebook

## Conclusion

This project demonstrates how SQL and Python can be used to clean relational retail data, perform multi-table analysis, identify business patterns, and translate analytical findings into actionable recommendations.
