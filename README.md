# 📊 Inventory Analytics Dashboard

**Interactive Inventory Analytics Dashboard using Microsoft Excel**

## 📌 Project Overview

This project focuses on analyzing inventory data using Microsoft Excel. It provides insights into inventory performance, stock availability, product categories, warehouse distribution, supplier purchases, and monthly sales trends.

The objective is to transform raw inventory data into meaningful business insights and support better inventory management decisions.

## 🎯 Project Objectives

- Analyze overall inventory performance.
- Monitor stock availability and low-stock products.
- Identify top products by quantity.
- Analyze inventory value across different categories.
- Compare warehouse-wise stock quantities.
- Evaluate monthly sales and purchase trends.
- Analyze supplier-wise purchase values.

## 🛠️ Tools & Technologies

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Data Analysis

## 📂 Project Files

- **Excel Workbook:** Inventory Analytics Dashboard.xlsx
- **Dashboard Screenshot:** dashboard-screenshot.jpg
- **Pivot Tables Screenshot:** pivot-tables.png

## 📂 Dataset Information

- Total Records: 500
- Total Inventory Quantity: 63,128 (sum of dated records, not a single-day stock count)
- Total Inventory Value: ₹12.81 Crore
- Data Period: January 2025 – 15 May 2026

## 📊 Analysis Performed

1. Inventory Value by Category
2. Top 10 Products by Quantity
3. Purchase Value by Supplier
4. Stock Quantity by Warehouse
5. Monthly Sales vs Purchase Trends
6. Stock Status Analysis

## 📈 Dashboard Preview

![Dashboard Screenshot](dashboard-screenshot.jpg)

## 📋 Pivot Table Analysis
Pivot Tables were used to summarize and analyze inventory data across different categories, products, warehouses, suppliers, and monthly trends.

![Pivot Tables](pivot-tables.png)

## 💡 Key Business Insights

1. Electronics holds 51.4% of inventory value. Laptop Pro 15 alone holds 19.9% of total value but has the lowest sell-through (9.0%), so it is an overstock risk.
2. Sales fell ~28% (Jan–Apr 2026 vs Jan–Apr 2025), but purchases fell only ~19%, so stock keeps building up.
3. Total purchases (₹1.79 Cr) exceed total sales (₹1.60 Cr) by ~12%.
4. HYD Hub holds 35.8% of inventory value (20,839 units), which creates a concentration risk.
5. 52 of 500 records (10.4%) are Low Stock, but they represent only 1.25% of inventory value.
6. KLR (14.9%) and CHN (14.6%) have the highest low-stock rates among warehouses; Furniture (16.4%) is the highest among categories.
7. January 2025 had the highest sales; August 2025 had the highest purchases.

## ✅ Recommendations

1. Cut purchase orders for slow-moving, high-value items (Laptop Pro 15, Air Conditioner 1.5T) until sell-through improves.
2. Align purchasing with the declining sales trend to stop stock build-up.
3. Review stock rebalancing from HYD Hub to KLR and CHN, which have the highest low-stock rates.
4. Prioritise reorders for Furniture, which has the highest low-stock rate.
5. Track sell-through % (Sales Qty ÷ Quantity) as a monthly KPI to catch overstock early.

> Note: May 2026 data is available only up to 15 May.

## 📌 Conclusion

The analysis shows the main inventory problem is overstocking, not shortage. Purchases exceed sales by ~12%, sales are declining, and a large share of value is locked in slow-moving, high-priced items. Reducing purchases for these items and tracking sell-through monthly would improve inventory efficiency.

## 👨‍💻 Author

**Lucky Kumar**

Aspiring Data Analyst

**Skills:** Excel | SQL | Python | Power BI
