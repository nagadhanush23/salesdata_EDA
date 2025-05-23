# Sales Analytics Project

## Overview

This project performs exploratory data analysis (EDA) on a large sales dataset to extract valuable insights that can help improve business strategies. The dataset contains detailed order information including product details, quantities, pricing, order dates, and purchase locations.

## Dataset Description

The dataset consists of **186,850** rows and **6** columns, with the following fields:

| Column           | Description                             | Data Type | Non-Null Count |
| ---------------- | --------------------------------------- | --------- | -------------- |
| Order ID         | Unique identifier for each order        | Object    | 186,305        |
| Product          | Name of the product sold                | Object    | 186,305        |
| Quantity Ordered | Number of units ordered                 | Object    | 186,305        |
| Price Each       | Price per unit of the product           | Object    | 186,305        |
| Order Date       | Date and time when order was made       | Object    | 186,305        |
| Purchase Address | Address where the product was delivered | Object    | 186,305        |

> **Note:** The dataset contains some missing values in the `Order ID` column.

## Objectives

* Clean and preprocess the data (handle missing values, convert data types).
* Perform exploratory data analysis (EDA) to identify trends and patterns.
* Analyze sales performance by product, city, and time periods.
* Visualize key insights through graphs and charts.
* Provide actionable recommendations to improve sales and marketing strategies.

## Tools and Libraries

* Python
* Pandas
* Matplotlib / Seaborn
* Jupyter Notebook

## Getting Started

##Data Cleaning and Preprocessing
Missing Values: Rows with missing Order ID were removed to ensure data integrity.

Data Type Conversion: Quantity Ordered and Price Each columns converted from string to numeric for calculations.

Date Parsing: Order Date converted to datetime format to enable time-based analysis.

Address Parsing: Extracted city and state information from Purchase Address for geographical insights.

Duplicate and Invalid Data: Filtered out invalid entries such as cancelled orders or rows with inconsistent data.

##Exploratory Data Analysis (EDA)

The analysis includes, but is not limited to:

Sales by Month: Identifying peak sales months to inform inventory and marketing strategies.

Sales by City: Determining top cities by sales volume for regional marketing focus.

Product Performance: Analyzing the best-selling products and their price points.

Order Timing: Examining what time of day most orders are placed to optimize staffing.

Revenue Insights: Calculating total revenue generated per product and per city.

##Visualizations

The project features multiple charts and graphs such as:

Line plots for monthly sales trends.

Bar charts for product popularity.

Heatmaps for hourly sales distribution.

Pie charts for city-wise sales share.

##Key Insights

Certain products consistently outperform others in revenue.

Seasonal trends indicate higher sales during specific months.

Urban areas show higher sales volume compared to smaller towns.

Order peaks in late morning and early evening hours.

##Potential Future Enhancements

Implement predictive models to forecast future sales.

Integrate customer demographics to personalize marketing.

Perform sentiment analysis on product reviews for deeper insight.

Develop interactive dashboards for real-time sales monitoring.

##Tools and Technologies

Python (Pandas, NumPy)

Data Visualization (Matplotlib, Seaborn)

Jupyter Notebook for analysis and presentation

1. Clone the repository:

   ```bash
   git clone https://github.com/nagadhanush23/salesdata_EDA.git
   ```
2. Install required Python libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the Jupyter notebook to explore data and visualizations.

## Sample Analysis

* Total sales revenue and most profitable products.
* Sales trends over months and seasons.
* Best-performing cities by sales volume.
* Peak order hours for optimal staffing.

---
