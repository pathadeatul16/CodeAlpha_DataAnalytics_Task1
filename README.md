# CodeAlpha_DataAnalytics

# E-Commerce Sales Data Analysis using Exploratory Data Analysis (EDA)

## Overview

This project performs **Exploratory Data Analysis (EDA)** on an E-commerce Sales dataset to uncover meaningful business insights, identify trends and anomalies, validate assumptions, and detect data quality issues.

The analysis includes:

* Data cleaning and preprocessing
* Statistical summaries
* Trend and pattern identification
* Correlation analysis
* Hypothesis testing
* Outlier detection
* Data visualization


# Objectives

The primary objectives of this project are:

* Understand the structure of the dataset
* Explore variables and their data types
* Identify trends, patterns, and anomalies
* Test business hypotheses using statistics and visualization
* Detect potential data quality issues
* Generate actionable business insights


# Dataset Information

The dataset contains E-commerce sales records including:

| Column Name      | Description                  |
| ---------------- | ---------------------------- |
| order_id         | Unique order identifier      |
| order_date       | Date of order                |
| customer_id      | Unique customer ID           |
| product_category | Product category             |
| region           | Customer region              |
| quantity         | Quantity purchased           |
| unit_price       | Price per unit               |
| discount         | Discount applied             |
| payment_method   | Mode of payment              |
| delivery_days    | Delivery duration            |
| customer_rating  | Customer satisfaction rating |
| revenue          | Total order revenue          |



# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn


# Project Structure

```bash
├── Correlation_Analysis.png
├── Revenue_Distribution.png
├── Scatter_Plot.png
├── ecommerce_sales.csv
├── EDA_Analysis.ipynb
├── README.md
```

---

# Key EDA Tasks Performed

## 1. Data Exploration

* Dataset shape
* Column inspection
* Data types
* Descriptive statistics

## 2. Data Quality Checks

* Missing value detection
* Duplicate row detection
* Data consistency validation

## 3. Univariate Analysis

* Revenue distribution
* Quantity distribution
* Customer rating analysis

## 4. Bivariate Analysis

* Revenue vs Unit Price
* Revenue vs Discount
* Revenue vs Quantity
* Revenue vs Customer Rating

## 5. Correlation Analysis

* Correlation heatmap
* Revenue drivers identification

## 6. Hypothesis Testing

Examples:

* Higher product price increases revenue
* Discounts affect revenue
* Customer ratings influence sales

## 7. Outlier Detection

* Boxplots
* IQR method

## 8. Time-Series Analysis

* Monthly sales trends
* Seasonal patterns

---

# Visualizations Included

* Histograms
* Boxplots
* Scatter plots
* Bar charts
* Pie charts
* Heatmaps
* Line charts

---

# Key Insights

* Electronics category generates the highest revenue.
* Revenue strongly depends on:

  * Unit Price
  * Quantity Purchased
* Discounts show weak negative impact on revenue.
* Customer ratings have limited influence on revenue.
* Revenue contains several outliers.
* Dataset is clean with minimal missing values and duplicates.

---

# Statistical Analysis

The project includes:

* Correlation analysis
* ANOVA testing
* Outlier analysis
* Distribution analysis


# Sample Business Questions Answered

* Which product category generates highest revenue?
* Which region contributes most sales?
* Does discount affect revenue?
* Which payment method is most popular?
* Are there seasonal trends in sales?
* Are there abnormal revenue outliers?

---

# Future Improvements

Possible future enhancements:

* Predictive modeling
* Customer segmentation
* Sales forecasting
* Interactive dashboards
* Profitability analysis
* Recommendation systems

---

# Learning Outcomes

This project demonstrates:

* Practical EDA workflow
* Statistical thinking
* Data visualization techniques
* Business insight generation
* Data quality assessment
