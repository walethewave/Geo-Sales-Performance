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

# Store Sales Data Analysis: Key Business Challenges and Solutions

In this project, I conducted a thorough analysis of store sales data to address key business challenges and uncover actionable insights. Here's a breakdown of the problem I tackled and the solution I provided:

### Sales and Profitability Analysis
I identified the key drivers behind the company's sales and profitability by analyzing trends across time (yearly and monthly), customer segments, and product categories. This helped the business understand which factors were contributing the most to overall performance, enabling better financial planning and strategic decisions.

### Customer Segmentation Insights
By grouping sales data by customer segments (e.g., Consumer, Corporate, Home Office), I revealed which segments contributed the most to sales and profit. This allowed the business to focus its marketing efforts on the highest revenue-generating segments and optimize engagement strategies accordingly.

### Product Performance Optimization
I analyzed product categories to identify top-performing products in terms of sales per unit. This helped the business determine which products to focus on for future sales efforts and which may need discontinuation or improvement, optimizing the product mix for profitability.

### Geographical Sales Focus
By grouping sales data by regions and cities, I pinpointed the most profitable areas (e.g., South and West regions in the U.S., cities like Los Angeles and Fort Lauderdale). This enabled the business to focus its sales expansion efforts in regions with the highest growth potential.

---

### Problem:
The business needed to understand the key factors driving sales and profit, identify its best customers, optimize its product offerings, and determine which geographical regions to prioritize for growth.

### Solution:
My analysis provided actionable insights into these areas, allowing the business to make data-driven decisions to enhance sales performance, increase profitability, and guide targeted marketing and product strategies.


# Store Sales Performance Story
# Power bi Insight
![image](https://github.com/user-attachments/assets/76829ca6-87e1-47a9-a664-91cfbcacc5a3)

Imagine you are the owner of a retail business, and you've been running operations for several years. Your business is growing, but you're uncertain about which products, customer segments, or regions are contributing the most to your success. To gain better clarity, you've decided to analyze the sales data, and the dashboard in front of you provides a wealth of insights to guide your future decisions.

## 1. Overall Performance:
The top section of the dashboard quickly sums up the key metrics:

- **Total Sales:** ₦742,000  
- **Total Profit:** ₦18,450  
- **Quantity Sold:** 8,028 units  

This gives you a clear picture of the business’s overall scale. While the sales figure is substantial, the lower profit margin suggests that there may be room for improvement in terms of profitability.

---

## 2. Sales Distribution Across Customer Segments:
The **"Sales Distribution"** chart breaks down sales across three major customer segments: **Consumer**, **Corporate**, and **Home Office**. What immediately stands out is that the **Consumer segment** consistently contributes the most in sales across all regions (Central, East, South, West). This suggests that your business is highly consumer-focused.

However, the **Corporate segment**, while generating slightly less sales, appears to be an area of potential, especially in the **West** region, where sales for this group remain strong. The **Home Office** segment lags behind in all regions, indicating a potential area for improvement or a possible niche focus.

---

## 3. Profit by Segment:
The profit story gets even more interesting. Despite the Consumer segment driving the highest sales, the **Corporate segment** emerges as the most profitable. It generates the highest profit, with over ₦8,000. This finding shows that while consumers are important for volume, the Corporate customers provide the highest margins.

This discovery can influence your strategy: focusing on corporate accounts may increase overall profitability without necessarily increasing the volume of sales.

---

## 4. Regional Performance:
The **"Profit by Region"** pie chart indicates that the **West** region is dominating, with over 53% of the total profit share. Other regions, such as the **South**, contribute around 31%, while the **Central** and **East** regions lag behind.

This reveals that expanding further in the West and South may bring the highest returns on investment. Perhaps these regions have more affluent customers or better market conditions.

---

## 5. Geographical Sales Insights:
When drilling down to the city level in the **"Sales and Profit by City"** chart, some clear frontrunners emerge:

- **New York**, **Los Angeles**, and **San Francisco** lead the pack in terms of sales.
  
Cities such as **Fresno** and **Aurora** appear on the lower end of the spectrum, meaning that focusing marketing efforts on higher-performing cities may yield better results than trying to improve performance in weaker ones.

---

## 6. Product Sales Performance:
Lastly, the **"Total Sales by Product"** chart highlights which products are performing best. Some of the top products include:

- **HON 5400 Series Chair**  
- **Bretford CR4500 Series Mobile Cabinet**  
- **Global Troy Office Chair**  

These products are clearly driving a significant portion of your sales, particularly in the furniture category. On the other hand, there are products further down the list that may require attention—either through improved marketing or discontinuation.

---

## Key Takeaways:

1. **Focus on Corporate Clients for Profit:** Although the Consumer segment brings in the most sales, the Corporate segment is the real profit driver. Consider enhancing your B2B sales efforts.

2. **Maximize Regional Opportunities:** The West and South regions offer the highest profitability. Prioritizing growth in these regions should lead to higher returns.

3. **Leverage Top Cities for Expansion:** New York, Los Angeles, and San Francisco are leading the way in sales. These cities represent key markets for expansion and targeted marketing.

4. **Product Focus:** High-performing products like the **HON Chair Series** and **Bretford Cabinet** should be at the center of your product offerings. Conversely, underperforming products may need reevaluation.

5. **Profit Optimization Strategy:** While discounting boosts sales, it appears to lower overall profit margins. The optimal approach may be to find a balance between offering discounts and maintaining profitability.

## Conclusion
This project delivers a comprehensive analysis of store sales data, offering key insights to guide decision-making on product offerings, pricing strategies, and customer engagement. By leveraging the insights derived from this analysis, businesses can optimize
