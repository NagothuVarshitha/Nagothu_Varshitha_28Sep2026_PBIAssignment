Sales Performance Dashboard --- Power BI

Project Overview

This project presents an interactive Sales Performance Dashboard
developed in Microsoft Power BI.
The report analyzes sales performance across products, customers,
locations, salespeople, time periods, and budget performance.

The dashboard is designed to provide business users with a clear view of
key KPIs and interactive analysis.

Objectives

Analyze overall sales performance.

Track sales, orders, quantity, profit, and average order value.

Analyze sales trends across years, months, and quarters.

Identify top-performing products and customers.

Analyze salesperson performance.

Understand geographic sales distribution.

Compare actual sales with budget.

Provide interactive dashboards and business insights.

Data Model

The Power BI report uses a relational data model containing:

Fact_Sales --- central sales transaction table.

Products --- product information including cost, price,
discount, and product name.

Customers --- customer information.

Locations --- geographic information.

Sales People --- salesperson information.

DateTable --- date, year, month, quarter, and year-month
analysis.

Date Ranges --- time-range support.

Budgeting --- budget and monthly allocation information.

Relationships connect the central Fact_Sales table with the relevant
dimension tables.

Key DAX Measures

The report uses DAX measures for business calculations, including:

Total Sales

Total Quantity

Total Orders

Average Order Value

Total Cost

Total Profit

Profit Margin %

Budget

Actual Sales

Budget Variance

Budget Achievement %

Variance %

YoY Growth

YoY Growth %

YTD Sales

Previous Year Sales

Example

Total Profit =
[Total Sales] - [Total Cost]

Dashboard Phases

Phase 5 --- Executive Overview

Provides a high-level summary of business performance using KPI cards
and visuals.

Key areas include:

Total Sales

Total Quantity

Total Orders

Average Order Value

Total Profit

Profit Margin %

Budget Achievement %

YoY Growth %

Top Products

Top Customers

Sales by Location

Actual vs Budget

Interactive location filtering is also provided.

Phase 6 --- Sales Trend Analysis

Analyzes sales performance over time.

The dashboard includes:

YoY Growth %

YTD Sales

Sales by Year

Sales by Month

Sales by Quarter

Year filter

This phase helps identify changes and patterns in sales across different
time periods.

Phase 7 --- Product Performance

Analyzes product-level performance using:

Total Sales

Total Quantity

Total Orders

Sales by Product

Quantity Sold by Product

Profit by Product

Profit Margin % by Product

An interactive Product Name filter allows users to focus on
individual products.

Phase 8 --- Customer Analysis

Analyzes customer-level performance using:

Total Sales

Total Orders

Total Quantity

Top 10 Customers by Sales

Total Orders by Customer

Total Quantity by Customer

An interactive Customer Name filter supports customer-level
analysis.

Phase 9 --- Salesperson Performance

Evaluates salesperson performance through:

Total Sales by Salesperson

Total Orders by Salesperson

Total Quantity by Salesperson

Total Profit by Salesperson

An interactive Salesperson Name filter allows individual salesperson
analysis.

Phase 10 --- Geographic Analysis

Analyzes sales geographically using:

Total Sales by Location

Total Sales by State

Sales by Location Map

Total Sales

Total Orders

Total Quantity

Location/Name filter

The geographic visuals help identify differences in sales across
locations.

Phase 11 --- Budget vs Actual

Compares planned budget with actual sales.

Key metrics and visuals include:

Budget

Actual Sales

Budget Variance

Variance %

Budget Achievement %

Budget vs Actual by Location

Budget Variance by Location

Budget vs Actual by Month

Month filter

This phase helps assess performance against the planned budget.

Phase 12 --- Final Dashboard

The final dashboard combines important business KPIs and interactive
analysis in one view.

It includes:

Total Sales

Total Orders

Total Quantity

Average Order Value

YTD Sales

Total Profit

Profit Margin %

Budget Variance

Budget Achievement %

YoY Growth %

Sales by Year

Sales by Product

Sales by Month

Sales by State

Budget vs Actual

Top Customers

Product filter

Customer filter

Salesperson filter

Year filter

Month filter

State filter

Interactivity

The report contains interactive filters/slicers for areas such as:

Year

Month

State

Location

Product Name

Customer Name

Salesperson Name

Selecting a filter updates the related visuals and KPI values, allowing
users to explore the data dynamically.

Key Report Metrics

The completed dashboard displays the following overall values in the
current report view:

Metric                    Value

Total Sales                 26M
Total Orders                11K
Total Quantity              21K
Average Order Value       2.36K
Total Profit                 8M
Profit Margin            32.52%
YoY Growth               76.58%
YTD Sales                    2M
Budget                       4M
Actual Sales                26M
Budget Variance             21M
Budget Achievement      605.99%
Variance %              505.99%

Business Insights

The project also includes a separate Business Insights document
containing:

Top 5 Findings

Top 5 Business Problems Identified

Top 5 Recommendations

The insights are based on the metrics and visual analysis available in
the Power BI report.

Deliverables

The project submission contains:

1. Power BI Report

.pbix file containing:

Clean data

Data model

Relationships

DAX measures

Calculated columns where required

Interactive dashboards

2. Business Insights

A short document containing:

Top 5 findings

Top 5 business problems identified

Top 5 recommendations

3. Presentation

The dashboard can be presented by explaining:

Data preparation

Data model

DAX measures

Dashboard design

Key findings

Business recommendations

Tools & Technologies

Microsoft Power BI

Power Query

DAX

Data Modeling

Interactive Data Visualization

Project Structure

Sales Performance Dashboard/
│
├── Varshitha_Assignment_26Sep2026.pbix
├── Business Insights/
│   └── Varshitha_Business_Insights.docx
└── README.md

Conclusion

The Sales Performance Dashboard provides an interactive business
intelligence solution for analyzing sales, profitability, customers,
products, locations, salespeople, time trends, and budget performance.

It combines data modeling, DAX calculations, interactive visualizations,
and business insights into a single Power BI reporting solution.
