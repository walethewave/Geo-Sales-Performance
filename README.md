# Store Sales Forecasting Analysis

## Project Overview
In this project, I performed an in-depth analysis of a **Store Sales Dataset** to uncover critical business insights, trends, and patterns. The project focused on understanding sales, profit, and quantity trends across various dimensions such as time, customer segments, products, and regions. The dataset includes information on orders, shipping modes, customer segments, products, and financial metrics (sales, discounts, profit).

I applied various **data cleaning**, **feature engineering**, and **aggregation techniques** to transform the raw data into actionable insights. I also created visualizations to make the findings easier to interpret and to highlight key business metrics.

## Key Features and Highlights

### Data Cleaning
Cleaned the dataset by converting date columns to `datetime` format, removing duplicates, and handling missing values. This ensured the dataset was ready for accurate analysis.

### Feature Engineering
Created new features such as:
- `Order Year`, `Order Month`, and `Order Day` from the `Order Date`.
- `Sales_Per_Unit` to measure the performance of products on a per-unit basis.

### Aggregations
- **Sales and Profit Analysis by Region and City**: Grouped data by geographical location to determine which regions and cities contribute the most to sales and profit.
- **Customer Segment Performance**: Grouped data by customer segments (Consumer, Corporate, Home Office) to identify which segments drive the most sales and profits.
- **Product Performance**: Analyzed performance across categories like Bookcases, Chairs, Tables, etc., to find top-performing products in terms of sales per unit.
- **Discount Analysis**: Investigated the impact of discounts on both sales and profit.

### Time Series Analysis
- Trends in sales, profit, and quantity over time (yearly and monthly) to identify seasonality and growth patterns.

### Data Visualization
Created insightful visualizations using **Matplotlib** and **Seaborn** to illustrate trends, comparisons, and insights such as:
- Yearly trends in sales, profit, and quantity.
- Monthly trends to highlight seasonality.
- Performance of customer segments and product categories.
- Top cities by sales and geographical sales performance.

## Business Insights

### Total Performance
The total sales across all orders amounted to **₦741,999.79**, with a total profit of **₦18,451.27** and **8,028** units sold. This highlights the overall scale of the business and its profitability.

### Yearly Growth
Sales and profit steadily increased from **2014 to 2017**, with 2017 being the peak year. This indicates growth in business operations, with **2016 and 2017** showing substantial jumps in both sales and profit.

### Customer Segments
The **Consumer** segment generated the most revenue (₦391,049), followed by **Corporate** and **Home Office** segments. However, the **Corporate** segment had the highest profit margin (₦7,584.82).

### Product Insights
The **Tables** sub-category performed best in terms of sales per unit (₦165), followed by **Chairs** and **Bookcases**. This information can help the business focus on high-performing product categories.

### Discount Impact
While discounts increased sales, they had a mixed effect on profits. Understanding the optimal discount rates can help improve profitability while maintaining sales volume.

### Top Geographical Regions
The **South** and **West** regions in the United States emerged as the most profitable, with cities like **Los Angeles** and **Fort Lauderdale** leading in sales.

## Problem Solved
This project provided the business with actionable insights on:
- **Sales and Profitability**: Identified key drivers of sales and profitability across time, segments, and products.
- **Customer Segmentation**: Insights on which customer segments contributed the most to business growth, allowing for targeted marketing strategies.
- **Product Optimization**: Helped in recognizing top-performing products and those that may need discontinuation or improvement.
- **Geographical Focus**: Provided clarity on which regions and cities to focus on for sales expansion.

## Conclusion
This project delivers a comprehensive analysis of store sales data, offering key insights to guide decision-making on product offerings, pricing strategies, and customer engagement. By leveraging the insights derived from this analysis, businesses can optimize
