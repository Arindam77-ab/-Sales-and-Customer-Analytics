 Sales Customer Analytics Dashboard
 
Objective:

To develop an interactive, multi-page Power BI dashboard for Adventure Works, aimed at providing key insights into sales performance, customer demographics, product profitability, and return rates to support strategic decision-making.

1. Data Sources:
2. 
Sales Data: Order quantity, revenue, cost, and profit across product categories and sub-categories.

Customer Demographics: Region, education level, gender, occupation, marital status.

Product Details: Product name, color, style, sub-category.

Returns Data: Return rates by category, sub-category, and individual products.

2. Data Preparation:
3. 
Imported data from multiple Excel/CSV sources using Power BI’s Get Data feature.

Performed data cleaning and transformation using Power Query:

Removed duplicates and nulls.

Standardized product and category names.

Merged related tables (e.g., customer and sales data).

Created calculated columns and measures using DAX:

Total Revenue, Total Profit, Return Rate %, Profit Margin.

3. Dashboard Design and Features:

1: Executive Summary

KPIs: Displayed Total Order Quantity (84K), Revenue (24.91M), Profit (10.46M), Cost (14.46M), Return Rate (2.17%).

Visuals:

Bar chart for Revenue by Category and Sub-Category.
Line chart showing Year-wise Revenue and Profit Trends.
Pie chart and bar chart for Return Rate by Category, Sub-Category, and Product.
Filters/Slicers: Region, Continent, Country, Category, Sub-Category, Order Date.

Page 2: Customer Summary
Demographic Insights:
Revenue segmented by Education Level, Gender, Marital Status, and Occupation.
Funnel chart for Profit by Education Level.

Visuals:

Combination of pie charts, bar charts, and funnel chart to highlight customer behavior and revenue contribution.

Filters/Slicers: Region, Education Level, Gender, Occupation, Marital Status.

Page 3: Product Summary
Product Analysis:
Profit and Revenue by Category, Sub-Category, Product Color, and Style.
Return rate analysis by Sub-Category.
Use of treemap and pie chart for comparative visuals.

Visuals:

Treemap, clustered bar, pie charts.

Filters/Slicers: Category, Sub-Category, Product Name, Product Color, Product Style.

4. Key Insights:
   
Bikes category dominates both revenue and profit.
Black and Blue products generate the highest revenue and profit.
Return rates are highest in Shorts and Vests sub-categories.
Customers with Bachelor’s degrees contribute the most to both revenue and profit.
Professionals and Skilled Manual Workers are top revenue-generating occupations.

6. Impact & Outcomes:
Enabled stakeholders to quickly identify top-performing products and customer segments.
Helped reduce return rates by focusing on high-return sub-categories.
Provided a basis for targeted marketing and inventory management strategies.

Tools & Skills Used:
Power BI: Dashboard creation, visualizations, data modeling.

Power Query: ETL operations.

DAX: Measures for custom KPIs.

Data Analysis & Storytelling: Translating data into actionable insights.

