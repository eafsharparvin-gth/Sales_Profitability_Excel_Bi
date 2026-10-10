Sales & Profitability Analysis | Excel BI Dashboard
Project Overview
This project is an interactive Sales & Profitability Analysis Dashboard built using Microsoft Excel, Power Query, Power Pivot, and DAX.

The goal is to analyze sales performance, profitability, product categories, customer locations, and monthly trends through a dynamic business intelligence reporting solution.

The dashboard allows users to explore business performance using interactive filters and key performance indicators (KPIs).

Dashboard Preview
Dataset
The project uses a sample sales dataset covering January–December 2026.

Dataset

Records

Description

Sales

400

Sales transactions, quantities, prices, and related IDs

Products

15

Product information, categories, and costs

Customers

20

Customer information and locations

Date Table

365

Calendar data for time-based analysis

The dataset includes three product categories: Beverage, Dry Fruit, and Food.

Tools & Technologies
Microsoft Excel — Dashboard development and reporting
Power Query — Data import, transformation, and preparation
Power Pivot — Data modeling and table relationships
DAX — Business KPI calculations
PivotTables & PivotCharts — Interactive analysis and visualization
Slicers & Timeline — Dynamic filtering by product category and date
Key Performance Indicators
The dashboard provides four main KPIs:

KPI

Value

Total Revenue

52,082

Total Profit

22,849

Profit Margin

43.87%

Total Sales Transactions

400

These values represent the full dataset with all filters cleared. Monetary units follow the sample dataset.

Dashboard Features
The dashboard contains four interactive visualizations:

Monthly Revenue & Profit Trend — Compares revenue and profit throughout the year.
Revenue & Profit by Category — Evaluates the financial performance of product categories.
Top 5 Products by Revenue — Identifies the highest-revenue products.
Top 5 Cities by Revenue — Highlights the leading customer locations.
A Category Slicer and a Date Timeline allow users to filter the dashboard dynamically.

The KPI cards and charts respond to the selected filters.

Data Preparation & Modeling
The reporting workflow follows these stages:

Import source Excel files using Power Query.
Prepare and transform the sales, product, and customer data.
Load the prepared data into the Excel Data Model.
Create relationships between the sales, product, customer, and date tables.
Define DAX measures for revenue, profit, profit margin, and transaction count.
Build PivotTables, PivotCharts, and interactive dashboard controls.
Project Structure
Sales_Profitability_Excel_BI/
│
├── data/
│   ├── Sales1.xlsx
│   ├── Products1.xlsx
│   └── Customers1.xlsx
│
├── report/
│   ├── query1.xlsx
│   └── Sales_Profitability_Dashboard.xlsx
│
├── images/
│   └── sales_dashboard.png
│
└── README.md
How to Use
Download or clone the repository.
Open report/Sales_Profitability_Dashboard.xlsx in Microsoft Excel for Windows with Power Pivot support.
Navigate to the Dashboard worksheet to explore the saved report.
Use the Category Slicer and Date Timeline to filter the results.
Refreshing the Data
The project includes external Excel data connections.

To refresh the project on another computer:

Open report/query1.xlsx.
Update the Power Query parameter DataFolder to the local path of the downloaded data folder, including the trailing backslash.
Refresh the queries and save the workbook.
Open report/Sales_Profitability_Dashboard.xlsx.
Update its Power Pivot source connections to the local paths of report/query1.xlsx and data/Sales1.xlsx.
Refresh the Data Model and verify the dashboard results.
Note: Source connections currently require local path configuration when the project is moved to another computer.

Business Value
This project demonstrates how Excel-based business intelligence can support:

Sales and profitability monitoring
Product and category performance evaluation
Geographic sales analysis
Monthly performance tracking
Interactive management reporting
Project Scope
This is a portfolio project using sample data to demonstrate practical Excel BI, data modeling, and business reporting skills.