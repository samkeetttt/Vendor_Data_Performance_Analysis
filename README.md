Vendor_Data_Performance_Analysis
Vendor Data Analytics Project Showcasing Vendor sales analysis using Python, SQL and PowerBI

Vendor Performance Report - Data Analytics Project

## Overview  
This project analyzes vendor performance to help a retail or wholesale business improve inventory management, pricing, and profitability.  
The main goals were to identify underperforming brands, evaluate top vendors, analyze the impact of bulk purchasing on unit costs, measure inventory turnover, and compare profitability between high and low-performing vendors.

The project covers the complete data analytics workflow: loading and cleaning data in Python, performing EDA, using SQL for deeper insights, building a Power BI dashboard, and presenting the results in a report and presentation.

---

## Dataset  
The dataset contains detailed information about vendors, sales transactions, and inventory performance.  

Key columns include vendor name, purchase quantity and price, sales quantity and sales dollars, gross profit, profit margin, freight cost, and stock turnover.

Data cleaning involved removing transactions with:
- Gross Profit ≤ 0  
- Profit Margin ≤ 0  
- Total Sales Quantity = 0  
- Missing or duplicate entries  

---

## Tools and Technologies  
Python (Pandas, NumPy, Matplotlib, Seaborn) - for data cleaning and exploratory data analysis  
MySQL - for running queries and generating insights  
Power BI - for creating an interactive dashboard  
Microsoft PowerPoint and Word - for preparing the final report and presentation  

---

## Steps Followed  

### 1. Data Loading and Cleaning  
- Loaded the dataset using Pandas  
- Checked for missing and duplicate values  
- Removed unprofitable and zero-sales transactions  

### 2. Exploratory Data Analysis  
- Calculated summary statistics such as mean, minimum, maximum, and standard deviation  
- Identified outliers in purchase price, freight cost, and stock turnover  
- Visualized data distributions using Matplotlib and Seaborn  
- Explored correlations between sales, profit, and inventory metrics  

### 3. SQL Analysis  
- Used MySQL to identify top and low-performing vendors  
- Compared purchase and sales contributions  
- Analyzed the impact of bulk purchases on unit costs  
- Measured inventory turnover efficiency  

### 4. Power BI Dashboard  
Created an interactive dashboard showing:
- Top vendors by sales and profit  
- Profit margin distribution  
- Inventory turnover trends  
- Cost savings from bulk purchasing  
- Brand performance overview  

### 5. Report and Presentation  
Summarized findings, created visuals, and presented key insights and recommendations in a structured report and PowerPoint presentation.

---

## Key Insights  
- The top 10 vendors contribute 65.7% of total purchases, indicating over-reliance on a few suppliers.  
- Vendors purchasing in bulk enjoy around 72% lower unit costs, confirming economies of scale.  
- Approximately $2.71 million is tied up in unsold inventory, suggesting inefficient stock management.  
- High-margin vendors show lower sales volumes, highlighting a need for price or marketing adjustments.  
- Hypothesis testing confirmed a significant difference in profit margins between top and low-performing vendors.  

---

## Dashboard Overview  
The Power BI dashboard provides a visual summary of sales and profit performance, vendor comparisons, and inventory efficiency.  
It allows users to filter data by vendor, category, or time period to explore specific insights interactively.

(You can add a screenshot of the dashboard here if available.)

---

## How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/vendor-performance-analysis.git
   cd vendor-performance-analysis
   
2. Run the Python notebook
   Open data_analysis.ipynb
   Execute all code cells to clean the data, perform EDA, and export the cleaned dataset

3. Run MySQL queries
   Import the cleaned dataset into MySQL
   Execute the queries provided in vendor_queries.sql

4. View the Power BI dashboard
   Open Vendor_Performance_Dashboard.pbix
   Refresh the data source to update the visuals

5. Review the deliverables
   Vendor Performance Report.pdf
   Vendor_Performance_Dashboard.pbix
