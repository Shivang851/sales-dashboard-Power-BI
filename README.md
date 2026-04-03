# sales-dashboard-Power-BI
A two-page interactive Power BI dashboard analyzing 2,000 sales transactions to uncover revenue trends, product performance, store manager rankings, and time-based patterns.

## Dashboard Pages

### Page 1 — Sales Overview
- Total Sales: ₹22,07,643
- Total Quantity: 11K units
- Total Transactions: 2,000
- Avg. Selling Price: ₹200
- Revenue by Product, Store Manager, Day of Week
- Time of Day analysis (Morning / Afternoon / Evening)
- Payment method breakdown (5 methods, ~20% each)

### Page 2 — Time & Date Analysis
- Monthly revenue trend (Jan–Dec)
- Yearly sales comparison (2023–2025)
- Day of week performance
- Time of day revenue breakdown

## Data Model — Star Schema
Built a proper Star Schema with:
- **Sales** (Fact table) — transactions, quantity, payment, store, product
- **ProductDIM** — product name, category, product ID
- **DateDIM** — date, month, day of week, time of day
- **StoreDIM** — store ID, location, store manager

## Key Insights
- Monitor generated the highest revenue (348K), Laptop the lowest (285K)
- Tuesday was the top sales day (359K), Saturday the lowest (269K)
- Evening had the highest revenue by time of day (1.6M)
- 2024 was the peak sales year (918K), 2025 shows a dip (405K — partial year)
- Noah was the top performing store manager (608K)
- All 5 payment methods had nearly equal share (~18–22%)

## Tools & Skills Used
- Power BI Desktop
- DAX measures (SUM, DIVIDE, FORMAT, CALCULATE)
- Star Schema data modeling
- Multi-page report design
- PDF export for sharing

## Files
- `sales.pbix` — Power BI source file
- `sales.pdf` — Dashboard preview (no Power BI required)

---
*Created by Shivang Sharma*
