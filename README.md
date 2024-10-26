# Power-BI-Sales

**Overview :**
  This repository contains images of the Power BI dashboards I created. The dashboards offer insights into various performance metrics of companies over recent years. The data is sourced from an Oracle OLAP warehouse, built using Informatica ETL tools, and structured using a star schema in Power BI.

**Database Connection :**
The Power BI dashboards are connected to an Oracle OLAP warehouse, which serves as the primary data source. The data is picked and built using the star schema methodology.

**ETL Process :**
The OLAP warehouse is built using Informatica ETL tools and includes:

**Staging Area :** Raw data is loaded from OLTP systems to the staging database.

**Transformation Techniques :** Various transformation techniques are applied to clean and process the data.

**Core Area :** Cleaned and transformed data is moved to the core database, scheduled for regular updates.

**Star Schema Design :**
  **Fact Table :** Sales Data and Return Data

  **Dimension Tables :** Timestamp, Products, Customers, Salesman, Brand, Group, Division

**Images and Descriptions**

**Image 1: Sales Overview**
  The "Sales Overview" page provides key financial metrics for the years 2020, 2021, and 2022, with 2022 being highlighted as the current focus year.
  **Key Metrics :** Gross Sales, Discount, Return, Net Sales, COGS (Cost of Goods Sold), Bonus, Gross Profit, GP% (Gross Profit Percentage)

**Image 2: Detailed Sales Metrics**
  The "Detailed Sales Metrics" page provides a deep dive into various sales and performance metrics.
  **Key Metrics :** 
    1. Breakdown by Year
    2. Breakdown by Division 
    3. Gross Profit by Brand
    4. Gross Sales by Year / Month - A line graph shows monthly gross sales trends over a period of time, ranging from 0 to 2.0M.

**Image 3: Sales Dashboard with Sidebar Navigation**
  The "Sales Dashboard" page provides key performance indicators (KPIs) and metrics related to sales performance. It includes a sidebar menu with various navigation options
  ans allows easy navigation through various key areas, aiding stakeholders in making informed decisions.

**Image 4: Sales Dashboard for June 2022**
  The "Sales Dashboard" page provides a detailed breakdown of sales metrics for the month wise, specifically customized filter button is created to filter by the division, item wise and salesman wise.

**Image 5: Sales Returns Overview**
  The "Returns Overview" page provides a detailed analysis of returns for the years, segmented by month and brand. It includes graphical representations and tabular data to illustrate the return amounts and     return percentages. It helps in identifying trends, high return rates, and the performance of individual salesmen, which can be crucial for making informed business decisions.
