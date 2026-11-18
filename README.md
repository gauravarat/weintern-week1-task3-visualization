# \# Olist E-Commerce Data Visualization

# \### WeIntern – Data Science Internship | Week 1 | Task 3

# 

# \## 1. Project Overview

# 

# This project focuses on visualizing the Brazilian Olist E-Commerce dataset to understand sales performance, product category revenue, monthly sales trends, and customer payment preferences.

# 

# The project uses Python-based data visualization techniques to convert cleaned e-commerce data into meaningful charts, business insights, and a consolidated sales dashboard.

# 

# \## 2. Project Objectives

# 

# \- Analyze delivered product revenue.

# \- Visualize the top 10 revenue-generating product categories.

# \- Understand monthly sales trends.

# \- Analyze payment method distribution.

# \- Create a consolidated sales dashboard.

# \- Present meaningful business observations through visualizations.

# 

# \## 3. Dataset

# 

# The project uses cleaned Olist E-Commerce datasets:

# 

# \- Customers

# \- Orders

# \- Order Items

# \- Payments

# \- Products

# \- Sellers

# \- Reviews

# \- Geolocation

# \- Product Category Translation

# 

# \## 4. Tools and Technologies

# 

# \- Python

# \- Pandas

# \- NumPy

# \- Matplotlib

# \- Jupyter Notebook

# 

# \## 5. Visualizations

# 

# \### 5.1 Bar Chart – Top 10 Product Categories

# 

# Compares the top 10 product categories based on delivered product revenue.

# 

# \### 5.2 Line Chart – Monthly Sales Trend

# 

# Shows changes in delivered product revenue over time and helps identify monthly sales peaks and declines.

# 

# \### 5.3 Donut Chart – Payment Method Distribution

# 

# Displays the contribution of different payment methods based on recorded payment value.

# 

# \### 5.4 Sales Dashboard

# 

# Combines key performance indicators, monthly revenue trends, category revenue, payment distribution, and business insights in one dashboard.

# 

# \## 6. Key Performance Indicators

# 

# \- Total Revenue

# \- Total Delivered Orders

# \- Average Order Value

# \- Total Order Items

# 

# \## 7. Business Insights

# 

# The analysis highlights:

# 

# \- Highest revenue-generating product category.

# \- Highest revenue-generating month.

# \- Leading payment method by recorded payment value.

# \- Revenue contribution of the top five product categories.

# \- Overall delivered sales performance.

# 

# \## 8. Project Structure

# 

# ```text

# Task-3\_Visualization/

# │

# ├── data/

# │   └── cleaned/

# │

# ├── notebook/

# │   └── task3\_visualization.ipynb

# │

# ├── outputs/

# │   ├── charts/

# │   ├── dashboard/

# │   └── reports/

# │

# ├── README.md

# ├── requirements.txt

# └── .gitignore

# ```

# 

# \## 9. How to Run the Project

# 

# 1\. Clone or download the repository.

# 2\. Install the required Python libraries.

# 3\. Ensure all cleaned CSV datasets are available inside `data/cleaned/`.

# 4\. Open `notebook/task3\_visualization.ipynb` using Jupyter Notebook.

# 5\. Execute the notebook cells sequentially.

# 6\. Find generated charts, dashboard images, and CSV reports inside the `outputs/` directory.

# 

# Install dependencies:

# 

# ```bash

# pip install -r requirements.txt

# ```

# 

# \## 10. Important Analytical Notes

# 

# \- Revenue represents delivered product prices and excludes freight charges.

# \- Average Order Value is calculated as delivered product revenue divided by distinct delivered orders.

# \- Total order items represents the number of order-item records, not a quantity column.

# \- Payment distribution uses all available payment records and is not restricted to delivered orders.

# \- The first and last months in the dataset may represent partial months.

# \- The dashboard is a static visualization created using Matplotlib.

# 

# \## 11. Author

# 

# \*\*Gaurav Varat\*\*

# 

# B.E. Artificial Intelligence and Data Science

# 

# GitHub: https://github.com/gauravarat

# 

# \## 12. Conclusion

# 

# This project demonstrates how cleaned e-commerce data can be transformed into meaningful visualizations and business insights using Python. The charts and dashboard provide an accessible overview of sales performance and payment patterns.

