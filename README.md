# 📊 Blinkit Sales Analysis – Power BI Project

## ⚡ Project Overview
An interactive Power BI dashboard analyzing sales performance, inventory, and customer satisfaction for Blinkit (a quick‑commerce grocery app). The dashboard includes KPIs, trends, and segmentation to support data‑driven business decisions.

## 🧰 Tools & Techniques
- Power BI Desktop (Power Query, Data Modeling)
- DAX for advanced KPIs
- Excel (data source)
- Visuals: KPIs, Bar/Donut charts, Matrix tables, Maps, Slicers

## 🛠 Workflow
1. **Data Preparation**
   - Imported and cleaned data in Power Query
   - Ensured correct data types and handled missing values
2. **Data Modeling**
   - Defined relationships across tables (sales, outlets, products)
   - Created calculated columns/measures (e.g., Total Sales, Average Rating)
3. **DAX Measures**
   - Used measures like:
     ```dax
     Total Sales = SUM(Sales[Amount])
     Avg Rating = AVERAGE(Products[CustomerRating])
     ```
4. **Visualizations & Interactivity**
   - KPI cards for metrics: Total Sales, Avg Sales, Items Sold, Avg Rating
   - Trend analysis (line chart) by establishment year
   - Bar/donut charts for fat content, item category, outlet size/type
   - Funnel map for geographic distribution
   - Slicers for interactive filtering (e.g., outlet size/location)

## 📈 Key Insights
- ✅ Total Sales: ~$1.2 M | Avg Sales/Order: ~$141
- 🥦 Low‑fat products drive ~65% of sales
- 🍎 Fruits, Vegetables, Snacks = top categories
- 🏬 Medium outlets in Tier 3 locations show strongest profitability
- 🛒 Supermarkets lead in volume; grocery outlets have better item visibility

## 🔍 Skills Demonstrated
- ETL with Power Query
- Data modeling & relationships
- DAX for KPI calculations
- Advanced visual storytelling
- Business-focused insights & recommendations

## 💡 Recommendations / Business Impact
- Emphasize low-fat products in marketing — they account for ~65% of sales
- Expand medium-sized Tier 3 outlets — top profit drivers
- Optimize SKU visibility strategies for grocery outlets
