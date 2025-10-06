# AdventureWorks Sales Analysis – Power BI Project

## Overview
This project analyzes AdventureWorks sales data to provide a comprehensive view of the company’s performance across multiple dimensions — products, customers, and time.  
It focuses on connecting technical analysis with real business insights, helping decision-makers explore *“What if?”* scenarios and understand how pricing and quantity changes affect revenue and profit.

---

## Business Objective
To help stakeholders:
- Understand overall sales and profitability trends.  
- Identify top-performing products and high-value customers.  
- Monitor return rates and customer behavior by segment.  
- Simulate potential business scenarios using dynamic parameters.

---

## Technical Highlights

### Data Model
- Designed a **Star Schema** with **2 Fact Tables**:
  - `FactSales` (orders, revenue, profit)  
  - `FactReturns` (returns and quantities)  
- Linked with dimension tables: `Products`, `Customers`, `Calendar`, `Categories`, and `Geography`.

### DAX & Measures
- Created custom **DAX Measures** for KPIs such as:
  - `Total Revenue`, `Total Profit`, `Total Orders`, `Return Rate %`, `Adjusted Profit`.  
- Implemented **Time Intelligence** functions (e.g., `PREVIOUSMONTH`, `DATESYTD`) for month-over-month and year-to-date analysis.

### Scenario Simulation
- Added **What-If Parameters** for *Price* and *Quantity*, enabling dynamic scenario testing.  
  Example: Adjust product price or sales volume and instantly see the impact on total profit and revenue.

### Visualization
- Interactive KPIs with trend indicators (+/- vs previous month).  
- Filters by *Category*, *Region*, and *Time Period*.  
- Pages for:
  - Overview Dashboard  
  - Product Insights  
  - Profit Analysis  
  - Customer Performance

---

## Key Insights
- 25K total orders generated $24.9M revenue with a 2.17% return rate.  
- Accessories category had the highest sales volume, while Bikes contributed most to profit.  
- Top 100 customers generated over $615K in revenue, highlighting strong loyalty segments.  
- Scenario testing revealed how small price changes can significantly influence profit margins.

---

## Learning Impact
This project helped me understand how powerful **data modeling** and **parameter control** can be in real business contexts.  
Instead of just visualizing data, I learned how to **simulate decisions** and see their potential impact before they happen — turning analysis into real business strategy.

---

## Tools & Technologies
- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query (data cleaning and transformation)  
- Excel / CSV (data sources)

---

## Files
- `AdventureWorks.pbix` – Power BI report  
- `Dataset/AdventureWorks.xlsx` – Source data  
- `AdventureWorks Project.pdf` – Project summary (exported visuals)
