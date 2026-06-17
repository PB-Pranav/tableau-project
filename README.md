# Sales & Customer Dashboards (Tableau)
 
Interactive Tableau workbook analyzing sales performance and customer behavior, built on a Superstore-style sales dataset. The workbook contains two linked dashboards — **Sales Dashboard** and **Customer Dashboard** — with KPI scorecards, year-over-year comparisons, and cross-filtering between charts.
 
## Dashboards
 
**Sales Dashboard**
- KPI scorecards for Sales, Profit, and Quantity, each comparing Current Year (CY) vs Prior Year (PY) with a % difference indicator
- Weekly sales trend chart
- Sub-category comparison chart with min/max highlighting
**Customer Dashboard**
- KPI scorecards for Customers, Orders, and Sales per Customer (CY vs PY)
- Top Customers ranking chart
- Customer Distribution view by location
Both dashboards share a custom navigation bar (icon-based page switching) and use dashboard actions, so clicking a customer, sub-category, or week on one chart filters related views.
 
## Data
 
- **Source:** "Sales DataSource" — a Superstore-style sales extract (Hyper format), originally loaded from a local CSV source
- **Key fields:** Order Date, Customer Name, Sub-Category, Sales, Profit, Quantity, Orders, Location
