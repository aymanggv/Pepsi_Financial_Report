# PepsiCo Sales Performance Dashboard

This dashboard was created to analyze and provide actionable insights into PepsiCo's sales performance, enabling data-driven decision-making and enhancing the efficiency of sales operations. Below is a detailed description of the dashboard's components and their purpose:  
The live report can be viewed using the link on [Streamlit](https://aymang.streamlit.app/Pepsi_Financial_Dashboard) or directly at [Power BI Report](https://app.powerbi.com/groups/me/reports/97d39d5a-95a5-45c4-924d-0bf47f151f63/ReportSection3fa583ff48685abe5c72?experience=power-bi)

## Key Insights and Features

### Top 5 Products

Identifies the best-selling products in PepsiCo's portfolio, highlighting items with the highest revenue and market share. Year-over-year sales comparisons are visualized using clustered column and line charts, showing a 17% sales increase in July followed by a decline.

### Products and Sales by Location

Displays the distribution of sales across various regions using ArcGIS maps. Sales thresholds are color-coded (e.g., red for below-average sales, blue for above-average), enabling quick identification of regional patterns and areas needing marketing focus.

### Comparison of Sales for Popular Products (2014 vs. 2015)

Analyzes year-over-year sales trends for PepsiCo's top brands. Column charts with dynamic color coding (green for growth, red for decline) emphasize performance changes. Provides a clear view of market share and sales performance evolution.

### Discount Activity vs. Margin

Evaluates the impact of discounts on sales and profit margins. Features tables and scatter plots to highlight top and bottom-performing products based on margin percentage, discount activity, and sales. Interactive slicers enable detailed exploration of discount efficiency.

### Sales Performance of Directors and Managers

Tracks and compares the performance of PepsiCo's directors and managers over two years. Includes column charts and tables for detailed analysis of individual contributions and product performance, emphasizing Pepsi and Pepsi Max as key revenue drivers.

## Data Model and Technical Details

- Integrated two primary fact tables: **"Budget"** and **"Selling"**, with three dimensions: **"Product"**, **"Customer"**, and **"Salesforce"**.
- Utilized Power BI's `CALENDAR AUTO` function to create a hierarchical time dimension (days, months, quarters, years) for temporal analysis.
- Enhanced the data model by combining relevant metrics into a **"Measures Table"** and establishing relationships using keys such as **"EANCode"** for products and **"ClientCode"** for customers.
- Standardized naming conventions and incorporated brand-specific tables for more meaningful insights.

## Conclusion

This dashboard provides PepsiCo's sales department with robust tools to understand sales dynamics, optimize regional strategies, and improve profitability through targeted actions. With its interactive design and data-driven approach, it supports strategic decision-making and continuous performance improvement.
