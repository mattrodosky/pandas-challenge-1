# Wholesale Data Analysis

## Description
This project involves analyzing a wholesale dataset to gain insights into client purchasing behavior, revenue generation, and profit margins. The analysis is performed using Python's Pandas library, focusing on data exploration, transformation, and summarization.

## Data Exploration
- The dataset is loaded from a CSV file and basic statistics are gathered using the `describe` function.
- The column names and data types are examined, along with the number of missing values.
- The analysis identifies the category with the most entries and the corresponding subcategory.
- The top 5 clients with the most entries are determined, and their IDs are stored for further analysis.

## Data Transformation
- New columns are created to calculate the subtotal for each line item based on unit price and quantity.
- Shipping prices are calculated based on weight, with different rates for orders over and under 50 pounds.
- A total price column is generated, including sales tax, along with columns for line costs and profits.

## Summary and Findings
- The analysis reveals that clients with the highest quantity of units ordered do not always correspond to the highest profits, indicating that shipping weights significantly impact overall costs.
