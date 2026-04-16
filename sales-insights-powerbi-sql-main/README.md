📊 SALES INSIGHTS DASHBOARD (POWER BI + SQL)


📌 PROJECT OVERVIEW

This project analyzes sales data across multiple Indian markets using SQL and Power BI to generate actionable business insights on revenue, sales quantity, and profitability.

The dashboard enables stakeholders to track market performance, customer contribution, product trends, and profit margins in an interactive and visual format.


🛠️ TOOLS & TECHNOLOGIES

SQL – Data extraction & analysis
Microsoft POWER BI – Dashboard & visualization
DATA MODELLING – Relationships between transactions, customers, and date tables

📊 DASHBOARD SECTIONS

🔹 1. SALES KEY INSIGHTS

KEY HIGHLIGHTS:

💰 Total Revenue: ₹985M
📦 Total Sales Quantity: 2M units
Insights:
🏙️ Delhi NCR dominates revenue (~₹520M) contributing more than 50% of total sales
📉 Smaller markets like Bangalore, Surat, Bhubaneswar contribute very little
📊 Revenue shows a declining trend towards 2020, indicating possible business slowdown
👤 Top Customer (Electricalsara Stores) alone contributes ~₹413M → high dependency risk
📦 A product category labeled "(Blank)" contributes highest revenue (~₹469M) → indicates data quality issue

🔹 2. SALES PERFORMANCE INSIGHTS

KEY HIGHLIGHTS:

💰 Revenue (2020): ₹142M
📦 Sales Quantity: 350K
📈 Profit Margin: ₹2.1M (~1.4%)
Insights:
🌍 Bhubaneswar leads revenue contribution (10.5%), followed by Hyderabad & Chennai
📉 Lucknow shows negative contribution (-2.7%), indicating losses
📊 Profit margins fluctuate heavily → unstable profitability across months
📅 Drop in revenue observed in April 2020, possible external impact (seasonality / market disruption)
👥 Top customers contribute large revenue but low profit margins (~0.4%–3%)

🔹 3. SALES PROFIT ANALYSIS

KEY HIGHLIGHTS:

💰 Total Revenue: ₹985M
📈 Total Profit Margin: ₹24.7M
Insights:
🏙️ Delhi NCR contributes ~52.8% revenue and ~48.5% profit → strongest market
📉 Bangalore has negative profit margin (-20.8%) → major loss-making region
⚖️ Some markets generate revenue but low profit contribution → inefficient operations
📊 Profit margins across markets vary significantly → pricing/cost issues
📉 Markets like Kanpur, Lucknow show near-zero or negative profitability


🔍 SQL ANALYSIS PERFORMED

Extracted customer and transaction data
Performed market-specific analysis (e.g., Chennai)
Analyzed year-wise and monthly revenue trends
Calculated total revenue using joins with date table
Filtered multi-currency transactions (INR & USD)


💡 OVERALL BUSINESS INSIGHTS

⚠️ Business is heavily dependent on a few customers and markets
📉 Several markets are running at low or negative profitability
📊 Revenue is high but profit margin is very low (~2–3%)
🧾 Data quality issues detected (e.g., blank product category)
📅 Revenue decline trend indicates need for strategic intervention


🚀 HOW TO USE

Clone this repository using "https://github.com/2905adi/sales-insights-powerbi-sql.git"
Open .pbix file in Power BI Desktop
Interact with filters (Year, Month, Market)
Use SQL queries for backend analysis

 NOTE:

This project is inspired by existing datasets, but the analysis, insights, and presentation are independently developed and enhanced.
