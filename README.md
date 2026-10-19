# DA70--Mini-Project
Product and Customer Insights
Project Overview
The Product and Customer Insights Dashboard is a Power BI report designed to help users explore sales performance, product trends, customer behavior, and order patterns. It brings key metrics and interactive visuals together to support data-driven analysis.
Project Objectives
- Monitor overall sales performance using KPI cards.
- Compare sales and profit across products, brands, and categories.
- Explore customer performance and geographic distribution where customer fields are available.
- Identify monthly trends and potential seasonal patterns.
- Enable interactive analysis through slicers, drill-down, drill-through, and page-navigation buttons.
Tools and Technologies
- Microsoft Power BI Desktop report development and visualization.
- Power Query data inspection, cleaning, and transformation, if used.
- DAX (Data Analysis Expressions) calculated measures and calculations.
- Excel / source data files** â€” source data, depending on the model configuration.


Page 1  - Executive Overview
Provides a high-level summary of business performance.

visuals:
- KPI cards: Total Sales, Total Profit, Total Orders, Total Customers, and Profit Margin.
- Monthly sales or profit trend.
- Sales by product category.
- Sales by country or another available location field.
- Slicers for date, country, brand, and category.

Page 2 - Product Insights
Supports product and category performance analysis.

visuals:
- Sales by product category.
- Sales by subcategory.
- Top 10 products by sales.
- Sales and profit comparison by product.
- Product hierarchy drill-down: Category â†’ Subcategory â†’ Product, where these fields exist.

Page 3 - Customer Insights
Supports customer-level analysis where the dataset contains suitable customer fields.

visuals:
- Distinct customer count.
- Top customers by sales.
- Sales by customer location or segment.
- Customer details, where supported.

Page 4 - Sales Trends and Operations
Explores changes over time and operational performance.

visuals:
- Monthly sales and profit trends.
- Order volume over time.
- Delivery-time analysis, if order and delivery dates are available.
- Online versus in-store Average Order Value (AOV), if a sales-channel field is available.

Page 5 - Detailed Analysis
Provides a detailed table of available order, product, and customer attributes. This page can be used as a drill-through destination.

