
# 📊 Power BI Report: Blinkit Sales Dashboard

## 📝 Description
This Power BI report provides a comprehensive overview of Blinkit's sales performance. It includes analysis by product category, time period, location (city/region), and promotional campaign. The dashboard is designed to help business teams monitor KPIs, identify trends, and optimize inventory and marketing efforts.

## 📁 File Name
- `Blinkit_Sales_Report.pbix`

## 📅 Last Updated
- July 10, 2025

## 📂 Data Sources
- **Order Transactions** — MySQL: `blinkit_db.order_history`  
- **Product Master** — Excel: `blinkit_products.xlsx`  
- **Promotions** — Google Sheets: `blinkit_campaigns_2025`  
- **Customer Info** — PostgreSQL: `blinkit_customers`

## 🔄 Data Refresh
- **Scheduled Refresh:** ✅ Yes  
- **Frequency:** Daily at 3:00 AM  
- **Gateway:** `BlinkitDataGateway`

## 🧭 Report Pages
1. Executive Summary  
2. Sales Trends (Daily / Weekly / Monthly)  
3. Top-Selling Products  
4. Sales by City & Zone  
5. Campaign Effectiveness  
6. Customer Segmentation  
7. Inventory Turnover

## 📈 KPIs Tracked
- Total Revenue  
- Average Order Value (AOV)  
- Order Volume  
- Customer Retention Rate  
- Sales per Region  
- Campaign ROI

## 🔐 Access & Ownership
- **Report Owner:** [Your Name / Team]  
- **Maintainer:** [Analyst Name]  
- **Workspace:** `Blinkit Business Analytics`

## ⚠️ Known Issues
- Data from smaller cities may have delays of up to 24 hours.  
- Missing product categories are being cleaned in the next ETL run.

## ✅ Viewer Tips
- Use the date range filter at the top to focus on specific timeframes.  
- Hover over line charts to view tooltips for exact daily metrics.  
- Click on regions on the map to filter all other visuals.
"""


