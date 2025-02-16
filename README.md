# Sales Data Analysis Project

## Introduction
This project aims to analyze sales data to uncover insights about customer purchasing behavior, sales trends, and business performance. The dataset, sourced from Kaggle, contains 11 columns representing various attributes of sales transactions, such as product details, order quantities, prices, purchase addresses, and timestamps.

## Dataset Overview
The dataset consists of the following key attributes:
- **Order ID**: A unique identifier for each order
- **Product**: The item purchased
- **Quantity Ordered**: The number of units ordered
- **Price Each**: The price of a single unit
- **Order Date**: The timestamp when the order was placed
- **Purchase Address**: The location where the product was shipped
- **Derived Columns**: Additional attributes such as Month, Sales, City, and Hour have been generated for deeper analysis

## Objectives of the Analysis
1. **Data Cleaning**: Handling missing values, duplicates, and inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Understanding sales trends through visualizations.
3. **Outlier Detection & Feature Scaling**: Identifying and handling anomalies in sales and pricing.
4. **Business Insights**: Finding top-selling products, peak sales hours, and best-performing cities.
5. **Hypothesis Testing**: Investigating patterns, such as whether weekend sales are higher than weekday sales.

By the end of this analysis, we aim to derive actionable insights that can help businesses optimize their sales strategies.

## Technologies Used
- **Python** (pandas, seaborn, numpy, matplotlib, scipy, sklearn)
- **Jupyter Notebook** for data processing and visualization

## Steps Involved in Analysis
### 1. Load Dataset
- Load the dataset into a Pandas DataFrame.
- Display the first few rows and column names.

### 2. Data Cleaning
- Dropped unnecessary columns.
- Checked for missing values and duplicates.
- Converted `Order Date` into separate Date and Time columns.
- Saved the cleaned dataset.

### 3. Exploratory Data Analysis (EDA)
- Summary statistics and data distributions.
- Visualizations:
  - Histogram plot
  - Box plot for Sales
  - Correlation Heatmap
  - Scatter plot of Sales vs Quantity Ordered

### 4. Outlier Detection & Removal
- Used Interquartile Range (IQR) method to remove extreme values.
- Applied Winsorization to cap extreme values.
- Saved cleaned dataset after outlier removal.

### 5. Feature Scaling
- Applied **Min-Max Scaling** and **Standard Scaling** on numerical columns.
- Saved the final cleaned & scaled dataset.

### 6. Business Insights & KPI Analysis
- Identified **Top-Selling Products by Revenue**.
- Analyzed **Peak Sales Hours**.
- Determined **Best Performing Cities**.
- Investigated sales trends based on **Weekday vs Weekend Sales**.

## Visualizations
- **Histograms**: Displayed data distributions.
- **Box Plots**: Identified outliers in sales.
- **Heatmaps**: Showed correlations between numerical features.
- **Scatter Plots**: Explored relationships between sales and quantity ordered.

## Conclusion
This analysis provides valuable insights into sales trends, customer purchasing behavior, and business performance. The findings can help businesses optimize marketing strategies, inventory management, and sales operations.

## How to Run the Project
1. Clone this repository.
2. Install the required Python packages using:
   ```sh
   pip install pandas seaborn numpy matplotlib scipy scikit-learn
   ```
3. Run the Jupyter Notebook to explore the analysis step by step.

## Future Enhancements
- Implementing predictive models for sales forecasting.
- Developing an interactive dashboard for real-time data analysis.
- Analyzing customer segmentation for targeted marketing strategies.

---
### Author
Akshay Bhujbal

