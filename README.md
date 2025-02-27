# Sales and Profit Analysis

# Description 
This project focuses on analyzing E-Commerce sales and profit data using Python, Pandas, and Plotly to gain insights into monthly sales trends, product category performance, profit analysis, and customer segmentation. The analysis helps in identifying sales patterns and optimizing business strategies.

# Objectives
1. Calculate monthly sales and identify the highest and lowest sales months.
2. Analyze sales by product category and sub-category to determine performance trends.
3. Compute monthly profit trends and identify the most profitable months.
4. Perform profit analysis by category and sub-category.
5. Evaluate sales and profit by customer segment.
6. Compute sales-to-profit ratio to assess business efficiency.
7. Develop interactive visualizations using Plotly for effective data storytelling.

# Tools
1. Anaconda Navigator
2. Jupyter Notebook

# Questions of E- Commerce Sales and Profit Analysis:

1. You need to calculate the monthly sales of the store and identify which month had the highest sales and which month had the lowest sales.
2. You need to analyze sales based on product categories and determine which category has the lowest sales and which category has the highest sales.
3. The sales analysis needs to be done based on sub-categories
4. You need to analyze the monthly profit from sales and determine which month had the highest profit.
5. Analyze the profit by category and sub-category.
6. Analyze the sales and profit by customer segment
7. Analyze the sales to profit ratio

# Installation

![E-Commerce_Project_1](https://github.com/user-attachments/assets/3aaf36e8-b7a0-43b5-b955-924fdd62abff)

1. import pandas as pd → Data manipulation (e.g., reading CSV, filtering, aggregating).
2. import plotly.express as px → Simple, high-level interactive visualizations.
3. import plotly.graph_objects as go → Custom, detailed plotly charts.
4. import plotly.io as pio → Managing figure input/output (saving, loading, templates).
5. import plotly.colors as colors → Accessing color scales for custom styling.
6. pio.templates.default = "plotly_white" → Sets a clean white background for all plots. 

# Data Importing

![image](https://github.com/user-attachments/assets/c0f0868f-d2e2-411a-aff8-e77ab13e041c)

Breakdown:
* pd.read_csv("Store_Data.csv") → Reads the CSV file into a DataFrame.
* encoding='latin-1' → Specifies the character encoding to handle special characters (useful for non-UTF-8 files).

data = pd.read_csv("Store_Data.csv", encoding = 'latin-1')
Data Analysis Using Python:
