# 📊 Supermarket Sales Data Analysis (NumPy Project)

## 📌 Overview

This project performs exploratory data analysis on a supermarket sales
dataset using **NumPy**. The goal is to demonstrate core NumPy concepts
such as array operations, indexing, slicing, statistical analysis, and
vectorized computations while extracting meaningful business insights
from transaction data.

## 🎯 Objectives

-   Load and process CSV data using NumPy\
-   Perform array operations to calculate totals and averages\
-   Apply indexing and slicing to explore specific data segments\
-   Compute statistical metrics like mean, median, variance, and
    standard deviation\
-   Use broadcasting and vectorized operations for efficient
    calculations\
-   Interpret results to derive insights about sales performance

## 🗂️ Dataset

The project uses a dataset named: supermarket_sales.csv

It contains transaction-level details such as: - Product category\
- Unit price\
- Quantity sold\
- Total sales\
- Gross income

## ⚙️ Technologies Used

-   Python 🐍\
-   NumPy

## 🧠 Key Features

### Data Loading

The dataset is loaded using numpy.genfromtxt() while skipping the header
row.

### Array Operations

-   Calculates overall total sales\
-   Computes average transaction value

### Indexing & Slicing

-   Extracts subsets like first 5 records\
-   Filters high-volume transactions (quantity ≥ 8)

### Statistical Analysis

Analyzes gross income using: - Mean\
- Median\
- Variance\
- Standard deviation

### Vectorized Computation

Revenue = Quantity × Unit Price

### Insights Interpretation

Provides textual interpretation of statistical results.

## ▶️ How to Run

1.  Install Python (3.x recommended)\
2.  Install NumPy if not installed:

pip install numpy

3.  Place supermarket_sales.csv in the correct path\
4.  Run the notebook:

jupyter notebook Project_week_1.ipynb

## 🚀 Learning Outcomes

-   How NumPy handles real datasets\
-   Efficient numerical computation techniques\
-   Basic data analysis workflow\
-   Turning raw data into insights

## 📜 License

This project is for educational purposes.
