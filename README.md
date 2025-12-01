# Sales-Performance-Dashboard-Excel
A sales dashboard in Excel that is designed to create actionable insights from raw sales information about revenues, geographic locations, products, and performance of sales representatives.

# Summary
- This sales dashboard uses Microsoft Excel to analyze and report on sales performance from several areas including regional performance, product performance, and performance of individual sales representatives.
- The objective was to convert raw sales data into meaningful insights and create an interactive tool to support business decision-making.

# Primary Objectives
- To calculate total sales for each order.
- To use look-up functions to enrich the data.
- To visualize how each sales representative and region are performing.
- To identify the high-value orders that may qualify for a sales bonus.

# Demonstrated Skills
- Data Cleaning/Preparation
- Excel Formulas (SUM, IF, VLOOKUP, CONCATENATE)
- Pivot Tables/Data Modeling
- Charting/Dashboard Design
- Business Reporting/Insight Generation

# Main Dashboard Features
## Total Sales Calculation
A TotalSales Column has been added using: =Quantity * UnitPrice
This displays the amount of revenue produced from each order.

## Order Detail (Concatenation)
Product Name and Region have been combined to produce a single descriptive field using: =ProductName & " - " & Region
This will make it easier to group your reports when you add a pivot table.

## Category Look-Up (VLOOKUP)

Product Categories have been pulled from the Product Information Sheet using: =VLOOKUP(ProductID, ProductInfo!$A:$C, 2, FALSE)
This has enriched the dataset to allow for further analysis.

## Bonus Eligibility (IF Statement)
Orders over ₦50,000 in TotalSales: =IF(TotalSales>50000,"Yes","No")
Have been identified as possible bonus eligible orders based on their TotalSales amount.

# Dashboard Components
- Cards for Total Sales Summary
- Bar Chart - Sales By Region
- Column Chart - Sales By Salesperson
- Pie or Donut Chart - Sales By Category
- KPI Indicator - Bonus-Eligible Orders
  
  # Slicers for Region and Salesperson
- Managers can easily find trends in the data and act quickly based on this dashboard.
- Some Insights Found Through This Analysis
- Regions and Products that are producing high sales performance can be easily seen.
- Sales Representatives can easily see their contribution levels at a glance.
- Orders that are potentially eligible for bonuses show the highest concentration of revenue.
- Categories help to identify what Product Groups are driving sales.
  
![Alt text](https://github.com/Anniewilliamsokpeke/Sales-Performance-Dashboard-Excel/blob/9e772f5b7d2905b297236c0a3b050b8e56f8e513/Sales%20Performance%20dashboard%20(BrightMart%20Superstore).png)
