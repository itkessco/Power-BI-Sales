# Power-BI-Sales

<h3 style="text-decoration: underline; text-underline-offset: 8px;">Overview :</h3>
  <p>This repository contains images of the Power BI dashboards I created. The dashboards offer insights into various performance metrics of companies over recent years. The data is sourced from an Oracle OLAP warehouse, built using Informatica ETL tools, and structured using a star schema in Power BI.</p>

<h3 style="text-decoration: underline; text-underline-offset: 8px;">Database Connection :</h3>
  <p>The Power BI dashboards are connected to an Oracle OLAP warehouse, which serves as the primary data source. The data is picked and built using the star schema methodology.</p>

<h3 style="text-decoration: underline; text-underline-offset: 8px;">ETL Process :</h3>
  <p>The OLAP warehouse is built using Informatica ETL tools and includes: </p>

  <li><b>Staging Area :</b> Raw data is loaded from OLTP systems to the staging database.</li>
  
  <li><b>Transformation Techniques :</b> Various transformation techniques are applied to clean and process the data.</li>
  
  <li><b>Core Area :</b> Cleaned and transformed data is moved to the core database, scheduled for regular updates.</li>

<h3 style="text-decoration: underline; text-underline-offset: 8px;">Star Schema Design :</h3>

  <li><b>Fact Table :</b> Sales Data and Return Data</li>

  <li><b>Dimension Tables :</b> Timestamp, Products, Customers, Salesman, Brand, Group, Division</li>

<h2>Images and Descriptions</h2>

<h3 style="text-decoration: underline; text-underline-offset: 8px;">Image 1: Sales Overview</h3>
  <p>The "Sales Overview" page provides key financial metrics for the years 2020, 2021, and 2022, with 2022 being highlighted as the current focus year.
  <h4>Key Metrics : </h4> Gross Sales, Discount, Return, Net Sales, COGS (Cost of Goods Sold), Bonus, Gross Profit, GP% (Gross Profit Percentage)</p>

<h3 style="text-decoration: underline; text-underline-offset: 8px;">Image 2: Detailed Sales Metrics</h3>
  <p>The "Detailed Sales Metrics" page provides a deep dive into various sales and performance metrics.</p>
  <h4>Key Metrics : </h4>
  <ul>
    <li>Breakdown by Year </li>
    <li>Breakdown by Division </li>
    <li>Gross Profit by Brand</li>
    <li>Gross Sales by Year / Month - A line graph shows monthly gross sales trends over a period of time, ranging from 0 to 2.0M.</li>
  </ul> 

<h3 style="text-decoration: underline; text-underline-offset: 8px;">Image 3: Sales Dashboard with Sidebar Navigation</h3>
  <p>The "Sales Dashboard" page provides key performance indicators (KPIs) and metrics related to sales performance. It includes a sidebar menu with various navigation options
  ans allows easy navigation through various key areas, aiding stakeholders in making informed decisions.</p>

<h3 style="text-decoration: underline; text-underline-offset: 8px;">Image 4: Sales Dashboard for June 2022</h3>
  <p>The "Sales Dashboard" page provides a detailed breakdown of sales metrics for the month wise, specifically customized filter button is created to filter by the division, item wise and salesman wise.</p>

<h3 style="text-decoration: underline; text-underline-offset: 8px;">Image 5: Sales Returns Overview</h3>
  <p>The "Returns Overview" page provides a detailed analysis of returns for the years, segmented by month and brand. It includes graphical representations and tabular data to illustrate the return amounts and     return percentages. It helps in identifying trends, high return rates, and the performance of individual salesmen, which can be crucial for making informed business decisions.</p>
