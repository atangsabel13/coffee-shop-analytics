# coffee-shop-analytics
# ☕ Coffee Shop Sales Dashboard — Excel

An interactive Excel dashboard analyzing six months of transaction-level sales data for a three-location coffee shop chain, built end-to-end with PivotTables, PivotCharts, and slicers.


---

## 📌 Overview

This project turns 149,116 raw point-of-sale transactions into a single-page, filterable dashboard that a franchise owner could use to spot sales trends, compare store performance, and make decisions on staffing, hours, and product mix. It's built on the publicly available **Maven Roasters "Coffee Shop Sales"** dataset (Maven Analytics), covering three New York City locations — Lower Manhattan, Hell's Kitchen, and Astoria — from January through June 2023.

**Objectives:**
1. Profile and clean the raw transaction data, adding calculated date/time fields
2. Explore the data with Excel PivotTables to surface patterns by time, location, and category
3. Build a dynamic, interactive dashboard with PivotCharts and a store-location slicer

---

## 🗂️ Dataset

| | |
|---|---|
| Rows | 149,116 transactions |
| Date range | Jan 1 – Jun 30, 2023 |
| Locations | Lower Manhattan · Hell's Kitchen · Astoria |
| Product categories | 9 (Coffee, Tea, Bakery, Drinking Chocolate, Flavours, Coffee Beans, Loose Tea, Branded, Packaged Chocolate) |
| Unique products | 80 |
| Total revenue | $698,812.33 |

**Columns:** Transaction ID, Transaction Date, Transaction Month, Transaction Day, Transaction Time, Transaction Hour, Transaction Qty, Store ID, Store Location, Product ID, Unit Price, Product Category, Product Type, Product Detail, Revenue.

---

## 🛠️ Tools & Skills Demonstrated

- Data cleaning and QA on a raw transactional dataset
- Calculated date/time fields for time-series analysis
- Excel **PivotTables** for slicing and dicing (by month, day of week, hour, category)
- **PivotCharts** for visualizing trends
- **Slicers** for interactive, one-click filtering by store
- Dashboard layout and design for a non-technical business audience

---

## 📁 Workbook Structure

| Sheet | Contents |
|---|---|
| `Transactions` | Cleaned transaction-level data — all 149,116 rows |
| `Pivot Tables` | 5 pivot tables: Revenue by Month · Transactions by Day of Week · Transactions by Hour of Day · Transactions by Product Category · Transactions & Revenue by Product Category |
| `Dashboard` | The interactive dashboard — 4 PivotCharts plus a Store Location slicer |

---

## 📊 The Dashboard

The `Dashboard` sheet brings four PivotCharts together on one page, all connected to a single **Store Location** slicer so every chart updates together when you filter to a single store:

1. **Sum of Revenue by Month** — line chart
2. **Number of Transactions by Day of Week** — bar chart
3. **Number of Transactions by Hour of Day** — bar chart
4. **Most Popular Product Categories** — bar chart



---

## 🔍 Key Insights

- **Revenue more than doubled over the period** — from $81.7K in January to $166.5K in June, a 104% increase, with a brief dip in February ($76.1K).
- **Coffee is the top category**, generating $269,952 (38.6% of total revenue) across 58,416 transactions — more than any other category.
- **Barista Espresso is the top-earning product type** ($91,406), followed by Brewed Chai Tea ($77,082) and Hot Chocolate ($72,416).
- **The morning rush drives over a third of all traffic** — 8–10am alone accounts for 36% of transactions (54,000 of 149,116).
- **Revenue is evenly split across locations**: Hell's Kitchen (33.8%), Astoria (33.2%), and Lower Manhattan (32.9%) all perform within a percentage point of each other.
- **Weekday transactions consistently outpace Saturday**, the quietest day of the week, with Friday and Thursday the busiest.

---

## 🚀 How to Use

1. Download `Analytics.xlsx` and open it in Microsoft Excel (PivotTables and slicers require Excel — Google Sheets will not render them fully).
2. Go to the `Dashboard` sheet.
3. Click a location on the **Store Location** slicer to filter every chart to that store, or click it again to clear the filter.
4. Explore the underlying `Pivot Tables` sheet to see the raw pivot data behind each chart, or the `Transactions` sheet for the full dataset.

---

## 📬 Contact

**Abel Atangs**
📧 abelatangs7@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/abel-atangs03) · [GitHub](https://github.com/atangsabel13)
