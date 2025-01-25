# PepsiCo Sales Performance Dashboard
<p>This dashboard was created to analyze and provide actionable insights into PepsiCo's sales performance, enabling data-driven decision-making and enhancing the efficiency of sales operations. Below is a detailed description of the dashboard's components and their purpose:</p>
The live report can be viewed using the link on [https://aymang.streamlit.app](https://aymang.streamlit.app/Pepsi_Financial_Dashboard) or <br/>
https://app.powerbi.com/groups/me/reports/97d39d5a-95a5-45c4-924d-0bf47f151f63/ReportSection3fa583ff48685abe5c72?experience=power-bi


<h2>Key Insights and Features</h2>

<ul>
  <li>
    <h3>Top 5 Products</h3>
    <p>Identifies the best-selling products in PepsiCo's portfolio, highlighting items with the highest revenue and market share. Year-over-year sales comparisons are visualized using clustered column and line charts, showing a 17% sales increase in July followed by a decline.</p>
  </li>
  <li>
    <h3>Products and Sales by Location</h3>
    <p>Displays the distribution of sales across various regions using ArcGIS maps. Sales thresholds are color-coded (e.g., red for below-average sales, blue for above-average), enabling quick identification of regional patterns and areas needing marketing focus.</p>
  </li>
  <li>
    <h3>Comparison of Sales for Popular Products (2014 vs. 2015)</h3>
    <p>Analyzes year-over-year sales trends for PepsiCo's top brands. Column charts with dynamic color coding (green for growth, red for decline) emphasize performance changes. Provides a clear view of market share and sales performance evolution.</p>
  </li>
  <li>
    <h3>Discount Activity vs. Margin</h3>
    <p>Evaluates the impact of discounts on sales and profit margins. Features tables and scatter plots to highlight top and bottom-performing products based on margin percentage, discount activity, and sales. Interactive slicers enable detailed exploration of discount efficiency.</p>
  </li>
  <li>
    <h3>Sales Performance of Directors and Managers</h3>
    <p>Tracks and compares the performance of PepsiCo's directors and managers over two years. Includes column charts and tables for detailed analysis of individual contributions and product performance, emphasizing Pepsi and Pepsi Max as key revenue drivers.</p>
  </li>
</ul>

<h2>Data Model and Technical Details</h2>
<ul>
  <li>
    <p>Integrated two primary fact tables: "Budget" and "Selling," with three dimensions: "Product," "Customer," and "Salesforce."</p>
  </li>
  <li>
    <p>Utilized Power BI's "CALENDAR AUTO" function to create a hierarchical time dimension (days, months, quarters, years) for temporal analysis.</p>
  </li>
  <li>
    <p>Enhanced the data model by combining relevant metrics into a "Measures Table" and establishing relationships using keys such as "EANCode" for products and "ClientCode" for customers.</p>
  </li>
  <li>
    <p>Standardized naming conventions and incorporated brand-specific tables for more meaningful insights.</p>
  </li>
</ul>

<h2>Conclusion</h2>
<p>This dashboard provides PepsiCo's sales department with robust tools to understand sales dynamics, optimize regional strategies, and improve profitability through targeted actions. With its interactive design and data-driven approach, it supports strategic decision-making and continuous performance improvement.</p>
