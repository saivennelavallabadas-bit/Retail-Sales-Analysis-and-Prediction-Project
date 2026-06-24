# Retail Sales Analysis and Prediction

## Overview

This project analyzes real-world retail sales data to uncover business insights and predict future sales using machine learning. The analysis includes data exploration, trend identification, visualization, and sales prediction to support data-driven decision-making.

## Objectives

* Analyze retail sales performance.
* Identify trends and patterns in sales and profit.
* Compare performance across categories and regions.
* Visualize key business metrics.
* Build a machine learning model to predict sales.
* Evaluate model performance using regression metrics.

## Dataset

The project uses the Superstore Sales Dataset containing information about orders, products, sales, profit, discounts, and customer segments.

### Features

* Order Date
* Sales
* Profit
* Quantity
* Discount
* Category
* Sub-Category
* Region
* Segment

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

1. Data Loading and Inspection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Sales Trend Analysis
5. Category and Region Performance Analysis
6. Correlation Analysis
7. Machine Learning Model Development
8. Sales Prediction
9. Performance Evaluation
10. Business Insights and Conclusions

## Visualizations

* Monthly Sales Trend
* Sales by Category
* Profit by Category
* Sales by Region
* Correlation Heatmap
* Top Selling Sub-Categories
* Actual vs Predicted Sales
* Feature Importance Analysis

## Machine Learning

A Random Forest Regressor is used to predict sales based on:

* Quantity
* Discount
* Profit

### Evaluation Metrics

* Mean Absolute Error (MAE)
* R² Score

## Key Findings

* Identified the highest revenue-generating product categories.
* Analyzed regional sales performance.
* Discovered relationships between sales, profit, and discounts.
* Predicted future sales using machine learning.
* Determined the most influential factors affecting sales.

## Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Running the Project

```bash
python retail_sales_analysis.py
```

## Expected Outcome

This project demonstrates how data science techniques can be applied to real-world retail data to generate actionable insights and build predictive models for business decision-making.

## Project Structure

```text
Retail-Sales-Analysis/
│
├── SampleSuperstore.csv
├── retail_sales_analysis.py
├── README.md
└── requirements.txt
```

## Conclusion

This project combines exploratory data analysis and machine learning to provide a complete end-to-end retail analytics solution. It showcases practical applications of data science in understanding business performance and predicting sales outcomes.
