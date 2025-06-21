# Excel Sales Dashboard – Revenue Analysis Report

An interactive and visually appealing dashboard built in Microsoft Excel to analyze sales performance across different customer segments, product categories, and time dimensions. This dashboard leverages Power Pivot, DAX, PivotTables, and slicers for dynamic data exploration.

# Overview

This Excel dashboard provides end-to-end visibility into:
- Total orders placed
- Total revenue generated
- Customer purchase behavior
- Performance across product categories, occasions, cities, months, and hours

# Key Features

- KPIs: 
  - Total Orders
  - Average Customer Spending
  - Average Order Gap
  - Total Revenue Generated
- Time-Based Analysis:
  - Revenue by Month
  - Revenue by Hour
- Product & Category Insights:
  - Revenue by Occasion
  - Revenue by Category
  - Top 5 Products by Revenue
- Geographic Breakdown:
  - Top 10 Cities by Orders
- Slicers:
  - Filter dashboard dynamically by `Order Date` and `Occasion`

# Tools & Technologies

- Microsoft Excel
- Power Pivot (Data Model)
- DAX Calculated Columns
- PivotTables & PivotCharts
- Power Query
- Slicers and Timelines

## Project Workflow

1. **Extract Data**
   - Loaded data from multiple CSV and Excel tables (`Orders_Table`, `Customers_table`, `Products`) into Power Query.

2. **Preprocess Data**
   - Cleaned null values, removed duplicates, standardized column formats (dates, currency).
   - Ensured data consistency across different sources.

3. **Transform Data Using Power Query**
   - Merged tables based on foreign keys (`Customer_ID`, `Product_ID`).
   - Derived columns such as `Order Day`, `Revenue`, and `Order Time` using Power Query and custom logic.

4. **Load Data to Data Model**
   - Loaded transformed tables to Power Pivot for building relationships and optimized analytics.

5. **Apply DAX Calculations**
   - Created measures and calculated columns like:
     - Total Revenue
     - Average Customer Spending
     - Average Order Gap
     - Total Orders
   - Used DAX for time intelligence and ranking logic.

6. **Design Visualizations**
   - Created PivotTables and PivotCharts for each analysis dimension (time, category, geography, product).
   - Added slicers and timelines for dynamic interactivity.
   - Designed layout with consistent formatting and grouped elements for a clean dashboard view.

# Screenshot


# Future Enhancements

- Add customer segmentation and churn analysis
- Integrate with Power BI for advanced dashboards
- Automate data refresh using Power Query connections to external files or databases

# Get Started

1. Open `dashboard.xlsx` in Excel
2. Ensure macros and Data Model are enabled
3. Use slicers to interact with the data dynamically

# References
WS Cube (Youtube)

# Contributing
Feel free to fork this project and enhance it with new features, visuals, or connectors. Pull requests are welcome.
