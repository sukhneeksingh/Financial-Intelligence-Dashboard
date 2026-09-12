# 📊 Financial Intelligence Dashboard

An executive Power BI dashboard providing a 360° view of sales, profitability, and performance across regions, segments, and products.

![Dashboard Preview](https://github.com/sukhneeksingh/Financial-Intelligence-Dashboard/blob/main/Power%20BI%20Finance/Finance%20Dashboard.png)

## Overview

This dashboard consolidates core financial KPIs into a single interactive report, helping stakeholders track revenue and margin performance and quickly identify the drivers behind them — without querying raw data.

## Features

- **KPI Cards** — Total Sales, Total Profit, Profit Margin, Units Sold, Top Country, and Top Product with embedded sparkline trends
- **Geographic Breakdown** — Interactive map and ranked country table (France, Mexico, Japan, US, India, Canada, China, Germany)
- **Financial Waterfall** — Gross Sales → Discounts → Net Sales → COGS → Profit, visualizing margin erosion at each stage
- **Segment Analysis** — Donut chart of sales by Government, Small Business, Channel Partners, Enterprise, and Midmarket
- **Product Rankings** — Top 10 products by sales (Paseo, VTT, Velo, and more)
- **Trend Analysis** — Monthly Sales vs. Profit trend and Profit Margin trend with average reference line
- **Dynamic Slicers** — Filter by Year, Country, Segment, Product, and Discount Band

## Key Metrics (Sample Data)

| Metric | Value |
|---|---|
| Total Sales | $118.73M |
| Total Profit | $16.89M |
| Profit Margin | 14.23% |
| Units Sold | 1.13M |
| Top Country | France ($24.35M) |
| Top Product | Paseo ($33.01M) |

## Tech Stack

- **Tool:** Microsoft Power BI
- **Data Model:** Star schema (Sales, Products, Countries, Segments, Discount Bands)
- **Visuals:** Cards, Maps, Waterfall Chart, Donut Chart, Bar Chart, Line/Combo Charts

## Getting Started

1. Clone this repository
2. Open `Financial-Intelligence-Dashboard.pbix` in Power BI Desktop
3. Refresh the data source connection
4. Explore using the Year, Country, Segment, Product, and Discount Band slicers

## License

[MIT](LICENSE)
