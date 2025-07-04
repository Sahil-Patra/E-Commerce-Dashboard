# E-Commerce-Dashboard

An interactive and data-driven e-commerce dashboard built with **Power BI** to visualize key metrics like sales, customer demographics, product performance, and more. This project helps e-commerce businesses track their performance, identify trends, and make data-driven decisions.

## Table of Contents
- [About the Project](#About-the-Project)
- [Tools Used](#Tools-Used)
- [Data Source](#Data-Source)
- [Executive Summary](#Executive-Summary)
- [Dashboard](#Dashboard)
- [Contact](#Contact)

---

## About the Project
This e-commerce dashboard provides valuable insights into sales trends, customer behavior, and product performance. It is designed for e-commerce analysts, marketing teams, and managers who need to monitor and analyze key business metrics in real-time. 
The dashboard offers visualizations like revenue trends, top-selling products, customer demographics, and region-wise sales distribution. All insights are accessible through interactive charts and filters, allowing users to drill down into specific details.

## Tools Used
- **Power BI**: For creating interactive dashboards and visualizations.
- **Canvas**: For creating the background of pages.
- **Sample Dataset**: Sample sales data in CSV format or xslx format.

## Data Source
This project uses sample data that simulates typical e-commerce data:
- **Customers**: Contains customer demographic details like age, gender, and location.
- **Products**: Contains product details including category, price, and Model name.
- **Employee**: Contains Employee details, including supervisor, manager, channel.
- **Salesperson**: Contains Salespersons Id and merged with Employee table with power query.
- **Product category**: Contains category of products and merged with Product table with power query.
- **Product subcategory**: Contains subcategory of products and merged with Product table with power query
- **Returns**: Contains return quantity , including date, territory key and product key.
- **Sales**: Contains sales details like order date, order number, unit price, quantity and territory key from the year 2019 to 2023.
- **Location**: Contains region details including sales territory, country an continent .

## Executive summary

This Power BI dashboard was designed to help e-commerce businesses uncover performance insights, reduce inefficiencies, and make smarter decisions across sales, operations, and customer experience. By visualizing key metrics like revenue, returns, product performance, and customer value, the dashboard empowers teams to identify growth opportunities, reduce product return rates, and optimize sales channels. Forecasting features enable leadership to anticipate future revenue, while drill-through analysis reveals underperforming products and geographic gaps. Ultimately, this dashboard transforms raw data into strategic intelligence that supports revenue growth, customer retention, and operational efficiency.

## Dashboard

**Project** : [E-commerce_dashboard.pbix](https://app.powerbi.com/view?r=eyJrIjoiNjMyZGZiMGMtZTk3My00NThhLWFmOTEtNmU4MzNjNTBhNWMzIiwidCI6ImRiOThlOTIzLWQyZWEtNDY2MS1hZDE1LTI3YzUyNjA2MGEyYiJ9)

  **Overview Page**:  
    The Overview page provides a high-level summary of the business's performance through three key KPIs:
    - Total Orders
    - Total Revenue
    - Total Quantity Sold

   Why It Matters: These KPIs offer a snapshot of overall health, enabling stakeholders to quickly assess how the business is performing across core metrics.
  ![Overview-page](assets/images/Overview_page.png)

  **Sales Page**:  
   This page offers deeper insights into revenue trends, customer behavior, and regional performance, empowering strategic sales planning.

   Key Visuals:
      - Top 5 Customers by Revenue – Helps identify high-value customers for loyalty or upsell campaigns.
      - Total Returns by Year – Tracks product return trends, useful for quality control or policy updates.
      - Revenue Trend Line (2021–2023) + Forecast for 2024 – Includes drill-up/down navigation and interactive hover tooltips to project minimum, average, and maximum expected revenue.
      - Map-Based Revenue by Country – Highlights top-performing and underperforming regions, supporting targeted regional strategies.
      - Interactive Filters (hidden by design) – Allow users to slice data by year, country, category, etc.

   Why It Matters: This section helps executives monitor revenue growth, understand return impact, and make informed future revenue forecasts based on past performance.
   ![Sales-page](assets/images/Sales_page.png)

  **Product Page**: 
    This page is designed to evaluate product performance and help the business optimize inventory, marketing, and fulfillment operations.

   Key Visuals:
       - Top 5 and Bottom 5 Products by Revenue – Reveals best and worst performers.
       - Total Returns by Product Category – Identifies categories with high dissatisfaction or defect rates.
       - Total Orders by Sales Channel – Highlights which channels (e.g., online, retail) are driving the most orders.
       - Product Distribution by Subcategory – Shows breadth and depth of product offerings.
       
   Why It Matters: These insights enable teams to optimize product portfolios, scale distribution of high performers, and investigate poor-performing SKUs for improvement.
   ![Product-pge](assets/images/Product_page.png)

  **Employee Page**:  
    This section provides in-depth details about employees, including their reporting relationships and roles within the organization.

   Key Visuals:
        - Custom visuals display which employees work under which supervisor or manager, offering hierarchical clarity and performance alignment.

   Why It Matters: Supports HR and operations teams in resource planning, team structuring, and supervisory performance reviews.
  ![Employee-page](assets/images/Employee_page.png)

  **Drilldown Page**:  
    It's a drilldown page, that showcases products in a detailed manner, enabling you to assess their performance and understand their growth. 
   ![Drilldown-page](assets/images/Details_page.png)

  **Tooltip**:
    It's a Tooltip page, designed for interactive and engaging tooltips to enrich the dashboard's overall quality.
    ![Tooltip](assets/images/Tooltips_page.png)

## Contact
**Sahil Patra**  
GitHub: [Sahil-Patra](https://github.com/Sahil-Patra)  

Email: sahilpatra1004@gmail.com  

Ph no.: +91 7735367833
---

**Thank you for checking out this project!** 
Credit goes to Akshay Khamble Sir for teaching me how to create a dashboard. Thanks sir.


---
