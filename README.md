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

![E-Commerce_Project_1](https://github.com/user-attachments/assets/004facb1-7248-497b-bcbb-193eec4b4d11)


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

# Converting Data Columns
Converting 'Order Date' and 'Ship Date' from object to datetime64[ns] allows efficient date-based analysis, sorting, and filtering. It enables operations like calculating delivery time, extracting year/month, and performing time-series analysis. Additionally, it optimizes memory usage and unlocks powerful date functions using .dt accessor. This conversion is essential for accurate and efficient data handling in analytics projects.

![E-Commerce_Project_2](https://github.com/user-attachments/assets/9de7376e-31f4-4d21-81c1-23444054a90b)

Extracting date-related features from 'Order Date' enables time-based analysis. 'Order Month', 'Order Year', and 'Order Day of Week' help identify trends, peak sales periods, and customer behavior patterns over time.

![E-Commerce_Project_3](https://github.com/user-attachments/assets/a84acfd0-7299-47ee-9d3a-ca50716b206d)

# Data Analysis Using Python:
Python scripts were executed using Jupyter Notebook, leveraging Pandas for data manipulation and Plotly for visualization.

1. Monthly Sales Analysis

![E-Commerce_Project_4](https://github.com/user-attachments/assets/241e00ca-1900-47b7-825f-480c9472312e)

Visualization: Line chart
Insight: 
* Identifies peak and slow sales months for better inventory and marketing planning.
* Displays sales variations over months.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. Sales Analysis by Product Category

![E-Commerce_Project_5](https://github.com/user-attachments/assets/6c695908-d01c-43ee-b6bb-ca984d255f01)

Visualization: Pie chart
Insight: Provides a detailed breakdown of sales performance within product categories.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3. Sales Analysis by Sub-Category

![E-Commerce_Project_6](https://github.com/user-attachments/assets/e226abfd-978e-4b9e-9b2d-e9d3c3f0c24b)

Visualization: Bar chart
Insight: Highlights best and worst-performing product categories.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. Monthly Profit Analysis

![E-Commerce_Project_7](https://github.com/user-attachments/assets/bcd472e4-79b7-40d8-b639-15e80e56a072)

Visualization: Bar chart
Insight: 
* Helps identify periods of maximum profitability.
* Identifies profit fluctuations over time.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

5. Profit Analysis by Category and Sub-Category

![E-Commerce_Project_8](https://github.com/user-attachments/assets/9a5a955c-5cdf-4fda-9367-9afb78c1a702)

![E-Commerce_Project_9](https://github.com/user-attachments/assets/9a065421-8009-4425-b2b9-5b1cea9d1cdb)

Visualization: Pie chart, Bar Chart
Insight: 
* Determines which product categories and sub-categories are the most profitable.
* Shows profit contribution by category.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

6. Sales and Profit Analysis by Customer Segment

![E-Commerce_Project_10](https://github.com/user-attachments/assets/bb98ff5e-3653-4842-b97a-0ad199d20d84)

Visualization: Bar chart
Insight: 
* Helps in understanding purchasing behavior across different customer groups.
* Helps in targeted marketing strategies.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

7. Sales-to-Profit Ratio Analysis

![E-Commerce_Project_11](https://github.com/user-attachments/assets/653f9813-2863-4907-836b-a3180250eb45)

Insight: Evaluates business efficiency and profitability.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Key Findings and Insights

1. Sales Trends: Monthly sales fluctuated, with the highest in X month and lowest in Y month.
2. Category Performance: Category A had the highest sales, while Category B had the lowest.
3. Profitability Trends: Profits peaked in X month and were lowest in Y month.
4. Customer Segments: Segment A contributed the most sales, while Segment B was less active.
5. Sales-to-Profit Ratio: The business maintained an average ratio of Z, indicating profitability.

# Conclusion

The E-Commerce Sales and Profit Analysis provided valuable insights into sales performance, customer behavior, and profit trends. The use of Pandas and Plotly allowed for efficient data manipulation and interactive visualizations, enhancing decision-making.
