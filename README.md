# Google Finance Stock Market Dashboard

Project: Global Stock Market Trend Dashboard
Description: An interactive dashboard built using Google Finance stock market data, providing insights into index performance, percentage shifts, company contribution, and daily market volatility.

# Files

Dataset Source: Google Finance
Dashboard Preview: /mnt/data/li.png

# How to open & reproduce (Power BI)

Run Power BI Desktop
Connect to CSV/Excel containing Google Finance data
Clean using Power Query:
Promote Headers
Change Amount column type
Create date-time hierarchy
# Build visuals:
Sum of Amount (Bar Chart)
Percentage Distribution (Pie Chart)
Line Chart for trend
Table with stock indicators
KPI cards (Total Amount, Avg Amount, Sum of Percentage)

# Power Query steps

Trim & clean names
Type conversions
Sort index values
Create calculated date columns

# DAX Measures
Total Amount = SUM('Market'[Amount])
Average Amount = AVERAGE('Market'[Amount])
Total Percentage = SUM('Market'[Percentage])

# Key Insights

Top-performing global indices
Daily performance volatility
Overall market distribution
Company-wise percentage share
Index vs goal comparison

# Repository Structure
/ (root)
├─ README.md
├─ data/
│  └─ market_data.csv
├─ images/
│  └─ stock_market_dashboard.png
└─ pbix/
   └─ Finance_Stock_Market.pbix

# License
MIT License
