# Adventure-Works-Sales-Performance-Analysis (Interactive Dashboard created using Power BI)
## Project objective
- Analyze sales performance across products, customers, time, and sales territories.
- Identify the best-performing customers and products to help increase market share.
- Analyze sales trends and profitability to understand overall business performance.
- Analyze production costs and identify opportunities to reduce the cost of sales.
- Support data-driven decision-making through an interactive Power BI dashboard.

## dataset used
- <a href="https://github.com/vishalmainale3-star/Adventureworks-sales-dashboard/blob/main/Adventure%20works%20datasets.xlsx.ods">adventure works datasets</a>

## Questions
- Union the Fact Internet Sales and Fact Internet Sales New tables.
- Lookup Product Name from the Product table into the Sales table.
- Lookup Customer Full Name from the Customer table into the Sales table.
- Create Date fields from the Order Date Key:
  Year,
  Month Number,
  Month Name,
  Quarter (Q1, Q2, Q3, Q4),
  Year-Month (YYYY-MM),
  Weekday Number,
  Weekday Name,
  Financial Month,
  Financial Quarter,
- Calculate Sales Amount using Unit Price, Order Quantity, and Unit Discount.
- Calculate Production Cost using Unit Cost and Order Quantity.
- Calculate Profit.
- Create a Pivot Table for Month and Sales, with Year as a filter.
- Create a Bar Chart to show Year-wise Sales.
- Create a Line Chart to show Month-wise Sales.
- Create a Pie Chart to show Quarter-wise Sales.
- Create a Combination Chart (Bar + Line) to show Sales Amount and Production Cost together.
- Build additional KPIs/Charts for performance by Product, Customer, and Region.
- Create an additional Dashboard based on the business requirements.

- dashboard interaction <a href="https://github.com/vishalmainale3-star/Adventureworks-sales-dashboard/blob/main/Dashboard%20of%20av.png">View dashboard</a>

## Process
- Data Loading – Loaded the Adventure Works datasets into Power BI.
- Data Cleaning & Transformation – Cleaned and transformed the data using Power Query.
- Fact Table Preparation – Combined the required sales tables using Union.
- Dimension Tables – Prepared Customer, Product, Date, and Sales Territory dimension tables.
- Data Modelling – Created relationships between the Sales fact table and dimension tables using appropriate keys.
- DAX Calculations – Created measures for Total Sales, Production Cost, Profit, Orders, and other required KPIs.
- Visualizations – Created charts and KPIs to analyze sales by month, year, quarter, product, customer, and territory.
- Dashboard Creation – Combined the visuals into an interactive Power BI dashboard with slicers and filters.
- Insights & Analysis – Analyzed sales trends, profitability, product performance, customer performance, and regional performance.


