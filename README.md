# Marketing-View-Dashboard

Overview

The Marketing View dashboard analyzes product and regional sales performance, profitability, and cost/margin dynamics to support marketing and commercial decision-making.

Filters & Slicers

Located at the top of the page:

Region, Market — dropdown (default: All)
Customer — dropdown (default: All)
Segment, Category, Product… — dropdown (default: All)
Year selector — 2019, 2020, 2021 (selected), 2022…
Quarter selector — Q1, Q2, Q3, Q4
Period toggle — YTD / YTG (Year-to-Date / Year-to-Go)
Visuals
Product Performance (table)

Breakdown by product segment (Desktop, Notebook, Accessories, Peripherals, Networking, Storage) with:

Net Sales $
Gross Margin $
Gross Margin %
Net Profit $
Net Profit %
Total row: $823.85M Net Sales, $300.63M Gross Margin (36.49%), -$54.65M Net Profit (-6.63%)
Performance Matrix (scatter/bubble chart)

Plots products by Net Sales $ (x-axis) vs Gross Margin $ (y-axis), bubble size/color coded by division: N & S, P & A, PC. Products shown include: Keyboard, Mouse, Business Laptop, Personal Laptop, Processors, Gaming Laptop, Wi-Fi Extender, External Solid State Drives, Graphic Card, Personal Desktop, MotherBoard — used to identify high-sales/high-margin vs. low-performing products.

Region / Market / Customer Performance (table)

Same metric structure as Product Performance, broken down by region:

APAC, NA, LATAM, EU
Total row: $823.85M Net Sales, $300.63M Gross Margin (36.49%), -$54.65M Net Profit (-6.63%)
Unit Economics (donut chart)

Compares Total COGS vs Gross Margin as a proportion of revenue (COGS ~63.51%, Gross Margin ~36.4%).

Net Profit Bridge (bar chart)

Shows the walk from Gross Margin to Net Profit, broken into Increase/Decrease components:

Gross Margin: 301 (positive/green)
Operational (cost): -355 (negative/red)
Net Profit: -55 (net negative/red)
Purpose / How to Use

This view is intended for marketing and commercial teams to:

Evaluate product-level profitability — which segments/products drive sales vs. which erode margin.
Use the Performance Matrix to spot products with strong sales but weak margins (or vice versa), guiding pricing/promotion decisions.
Compare regional performance to identify underperforming markets (e.g., APAC and NA currently show negative Net Profit %).
Understand cost structure via the COGS/Gross Margin split and the bridge from margin to net profit, highlighting where operational costs are eroding profitability.
Drill down by region, customer, or product segment/category using the top filters, and by year/quarter/YTD-YTG for time-based analysis.
Notes for Maintainers
The "Add data fields here" placeholder in the Values pane indicates the currently selected visual has an incomplete/unbound field — check before publishing.
Both the Product and Region tables total to the same figures ($823.85M Net Sales, -6.63% Net Profit %), confirming they're two cuts of the same underlying fact table.
Net Profit is negative overall despite a healthy ~36% Gross Margin — the bridge chart suggests operational costs are the primary driver; worth confirming the exact cost categories feeding "Operational" in the DAX measure.
