# Sales Performance Analysis 

## Project Overview

This Sales Performance Dashboard offers a clear view of a retail store's sales metrics, highlighting revenue, total transactions, top-selling products, and
regional sales performance. The analysis was done using Excel and SQL, with Power BI used for interactive visualization. 
This dashboard helps stakeholders pinpoint high-revenue products and regions, track seasonal trends, and make informed decisions to optimize inventory and marketing.

## Project Objectives
- Identify Top-Selling Products and High-Performing Regions: Determine which products and regions contribute most to revenue.
- Track Sales Trends Over Time: Analyze sales data to uncover seasonal trends and patterns.
- Support Data-Driven Decision-Making: Enable informed choices for inventory management and marketing strategy.


## Key Metrics
- Product Details (e.g., name, units sold, total revenue)
- Regional Information (e.g., sales by region: North, South, East, West)
- Sales Metrics (e.g., monthly sales figures, quarterly performance)

## Data Sources
The data used for this work is gotten from my project work.


## Data Collected

The dataset used for this analysis includes information on:
- Total Customers: The total number of unique customers who made purchases.
- Revenue: Total sales revenue generated.
- Average Sales: The average transaction value across all sales.
- Total Units Sold: The aggregate number of items sold.
- Total Transactions: The count of individual sales transactions

## Tools Used
- Excel: For data cleaning, exploration, and initial calculations using pivot tables. 
- SQL: For advanced data queries on sales by product, region, and time period.
- Power BI: To build an interactive dashboard with slicers and visuals for revenue, top products, and regional sales insights.

## Data Cleaning and Preparation
- Data Loading and Inspection (Duplicates information were removed)
- No Missing Variables
- Data Cleaning and Formatting
- Creation of Calculated columns and measures

## Data Analysis
The following are the Excel formulas, SQL codes, DAX Expressions used during my Analysis

```
=AVERAGEIF(SalesData!C:C,SalesData!C2,SalesData!H:H)
=SUMIF(SalesData!D:D,SalesData!D3,SalesData!H:H)

Average Sales = [Total Sales] / [Total Transactions]
Total Customers = DISTINCTCOUNT(SalesData[Customer Id])
Total Sales = SUM(SalesData[Total Sales ])
Total Transactions = COUNT(SalesData[OrderID])
Total Units Sold = SUM(SalesData[Quantity])
```


## Method Used in Microsoft Excel
![Pivot tables and Formulas for Sales Data](https://github.com/user-attachments/assets/883e6012-89f4-40c4-891c-2000ce53321a)
![Sales Performance Analysis View](https://github.com/user-attachments/assets/1fef5f3d-7da2-47a2-a7fc-4a6ae150fb98)

## PowerBI - Sales Performance Dashboard
![PowerBI - Sales Performance Visualization](https://github.com/user-attachments/assets/0d630d22-65d3-49f5-a7f2-fe6df34b84d4)


## Visual Analysis and Overall Insights

- High-Level Performance Overview: The retail store achieved total revenue of $2.1 million, selling 68,000 units across 9,921 transactions. The average transaction value is $212, indicating strong spending, possibly from premium pricing or bulk purchases. Meanwhile, the total customers is 500, this indicates a strong but relatively limited customer base, which could imply repeat purchases from loyal customers or a high acquisition cost for new customers.

- Regional Performance Analysis: In the Southern Region, the South Region leads with 928K transactions, highlighting its importance for the business while the
Northern and Eastern Regions had a moderate performance with 387K and 486K transactions, respectively, showing potential but lagging behind the South. Lastly, the Western Region had Lowest at 300K transactions, indicating either lower demand or untapped market potential. With this analysis, it shows that the business is heavily reliant on the South region, which is beneficial for regional-focused campaigns. However, the lower performance in other regions highlights potential areas for expansion or more targeted marketing.

- Product Performance: Top Products by Revenue: Shoes ($613,380), Shirts ($485,600), and Hats ($316,195). Shoes represent nearly 30% of total revenue.
Top Products by Units Sold: Consistent with revenue leaders, indicating strong demand across these items. Here, Shoes, Shirts, and Hats are the primary revenue drivers. These products resonate well with customers, making them ideal candidates for special promotions, bundling strategies, and enhanced inventory levels.

- Quarterly Product Sales Insights: Q3 Performance: Q3 Performance: A closer look at Q3 shows strong sales for Hat ($209,020), Shirt ($237,600), and Shoes ($67,080). This quarterly data is valuable for understanding seasonal patterns, as it highlights products that perform well at specific times of the year. This indicates that Q3 data suggests that certain products are seasonally popular. This can inform stock planning, as well as promotional campaigns that capitalize on high-demand periods within each quarter.

- Monthly Sales Trends: The sales trend peaks in March (504K) and August (275K), likely due to seasonal demand or promotional campaigns. There’s a noticeable dip in other months, which may indicate a pattern of seasonality. This suggests that targeted seasonal promotions in March and August could maximize revenue. Additionally, understanding low-demand periods (e.g., September and October) could help implement clearance sales or customer engagement strategies to sustain interest.

## Recommendations
- Focus on Regional Marketing and Expansion: Intensify marketing in the South while exploring growth in the North and East regions through targeted campaigns.
- West Region Development: Conduct market research to understand customer preferences and develop strategies to increase sales in this area.
- Inventory and Stocking Strategy: Prioritize stocking Shoes, Shirts, and Hats to prevent stockouts, particularly during peak seasons. Adjust stock levels based on quarterly trends.
- Seasonal Promotions: Launch promotions in March and August to leverage peak sales. Implement clearance sales or loyalty programs during slower months to maintain customer engagement.
- Product Diversification and Bundling: Bundle Shoes, Shirts, and Hats in promotions to boost average transaction values. Explore new product lines based on customer feedback to capture additional revenue.
- Customer Retention and Loyalty Programs: Establish loyalty programs to encourage repeat purchases and enhance customer experience with personalized marketing strategies.
- Data-Driven Seasonal Planning: Utilize monthly and quarterly performance insights for promotional strategies and inventory management, applying predictive analytics for demand forecasting.
- Explore E-commerce and Digital Marketing: Expand online presence and digital marketing efforts in both high-performing and underperforming regions to reach untapped markets and attract new customers.
