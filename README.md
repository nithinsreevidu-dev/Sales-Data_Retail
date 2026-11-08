# Sales-Data_Retail
Data Analyst Mini Project On Excel &amp; PowerBI
### **Problem statement  :***********************************************************************************************8
The company wants to understand its overall sales and profit performance across different products, customers, regions and time periods.
Currently, the company needs better visibility into:

* \- Which products and categories generate the highest sales?
* \- Which products generate the highest and lowest profits?
* \- Which customers contribute the most revenue?
* \- Which states and regions perform well?
* \- How do discounts affect profitability?
* \- How do sales and profits change from year to year?
* \- Which months generate the highest and lowest sales?
###############################################################################################################

##################################################################################################################
POWER BI SALES ANALYTICS PROJECT 
######################################
Sheets: Sales, Messy Data, Descriptive Analysis. Fields include Order ID, Customer Name, Category, Sub Category, City, Order Date, Region, Sales, Discount, Profit, State.
3. Data Cleaning - Power Query
    1. Load Sales and Messy Data.
    2. Check null values. DOCUMENTATION

Dataset: Retail Sales.xlsx
   1. Project Overview
     Objective: Clean raw and messy sales data, transform it in Power BI, build a star schema model, create DAX measures, reports and dashboards for business insights.
  2. Dataset Understanding

  3. Remove duplicate Order IDs.
    4. Standardize State names.
    5. Correct date formats.
    6. Replace invalid dates.
    7. Fix data types.
    8. Trim and clean text columns.
    9. Handle missing Category and Customer values.
    10. Validate Sales, Discount and Profit columns.
4. Data Transformation
    Create Year, Month, Month Number, Quarter. Split and merge columns where required. Rename columns. Create business-friendly dimensions.
5. Data Validation
   Validate row counts, duplicates, nulls, totals, date ranges and measure accuracy against source data.
6. Data Modelling (Star Schema)
     FactSales table connected to DimDate, DimCustomer, DimProduct, DimLocation. Use one-to-many relationships and single direction filters.
7. DAX Measures
  Total Sales = SUM(FactSales[Sales])
  Total Profit = SUM(FactSales[Profit])
  Orders = COUNT(FactSales[Order ID])
  Avg Sales = AVERAGE(FactSales[Sales])
  Profit Margin % = DIVIDE([Total Profit],[Total Sales])*100
  YTD Sales = TOTALYTD([Total Sales],DimDate[Date])
8. Reports
  Report 1: Executive Summary KPIs.
  Report 2: Sales Analytics Performance.
  Report 3: Profit Analytics Performance.
  Report 4: Monthly Trend Analysis.
  Report 5: Sales & Profit Analytics DASHBOARD.
9. Visualizations
    Cards, Multi-row Cards, Clustered Column Charts, Bar Charts, Line Charts, Donut Charts, Treemaps, Matrix, Funnel, Scatter Plot, Map and     Slicers.
10. Dashboard
    KPIs: Total Sales, Profit, Orders, Average Sales, Profit Margin. Include filters for Year, Region, Category and State.
11. Key Insights
    Identify top performing regions, categories, profitable products, seasonal patterns and target achievement.
12. Project Conclusion
    The project converts inconsistent raw data into an analytics-ready Power BI solution through cleaning, transformation, modelling and           visualization.
############################################################################################################################################


Sales Analytics Report
#########################

<img width="1608" height="847" alt="Sales Analytics" src="https://github.com/user-attachments/assets/bd2afb95-8815-465e-a4c2-ffdf044d78cf" />

################################
Profit Analytics
##################################
<img width="1602" height="842" alt="Profit Analytics" src="https://github.com/user-attachments/assets/59a46040-1e9a-4c7f-aac2-a51e5a9894c9" />

##########################################
Sales & Profit Performance DashBoard
#########################################

<img width="1596" height="845" alt="Sales   Profit Performance DashBoard" src="https://github.com/user-attachments/assets/19b4e22a-2143-4f7a-86b3-1f0ef7bb146d" />
