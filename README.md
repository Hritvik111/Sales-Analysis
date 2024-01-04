# US-Sales-Analysis with Python and Tableau

This repository contains Python code for analyzing sales data using the Pandas, Matplotlib, and Seaborn libraries. The code is designed to clean and visualize sales data from different sheets in an Excel file.

## Dataset Overview

The analysis is performed on three main datasets:
- **Orders DataFrame**: Contains information about sales orders.
- **People DataFrame**: Contains information about people involved in sales.
- **Returns DataFrame**: Contains information about product returns.

## Tableau Public Dashboard

Explore the interactive Sales Dashboard on Tableau Public: [Sales Dashboard](https://public.tableau.com/app/profile/hritvik.mahajan/viz/SalesDashboard_17038205355180/SalesDashboard)


## Data Cleaning

### Orders DataFrame
- Loaded the data from the Excel file.
- Checked for missing values in the Orders DataFrame and displayed the summary.
- Converted the 'Order Date' column to datetime format.
- Dropped duplicate rows.
- Reset the index after cleaning.

### People DataFrame
- Checked for missing values in the People DataFrame and displayed the summary.
- Dropped duplicate rows.
- Reset the index after cleaning.

### Returns DataFrame
- Checked for missing values in the Returns DataFrame and displayed the summary.
- Dropped duplicate rows.
- Reset the index after cleaning.

## Data Visualization

### Basic Statistics
- Displayed summary statistics for numerical columns in the Orders DataFrame.

### Distribution Visualization
- Plotted the distribution of the 'Order Date' column using a histogram.
- Visualized the distribution of the 'Category' column using a countplot.

### Correlation Matrix
- Calculated the correlation matrix for numerical columns in the Orders DataFrame.
- Visualized the correlation matrix using a heatmap.

### Time Series Analysis
- Plotted a time series analysis of sales over time.

### Geographical Distribution
- Identified the top 10 cities by total sales.
- Filtered the Orders DataFrame for the top 10 cities.
- Visualized the geographical distribution of sales using a scatter plot for the top 10 cities.

## How to Use

1. Ensure you have the necessary libraries installed (`pandas`, `matplotlib`, `seaborn`).
2. Load your sales data in Excel format with sheets named 'Orders', 'People', and 'Returns'.
3. Run the provided Python script to clean and visualize the data.

Feel free to customize and adapt the code according to your specific dataset and analysis needs.
