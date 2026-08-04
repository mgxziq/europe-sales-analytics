# europe-sales-analytics
An interactive Power BI dashboard analyzing sales performance, profitability metrics, cross-channel trends, and spatial distribution across European markets using DAX and dynamic visual analytics.

# Europe Sales Performance Dashboard & Analytics

An interactive **Power BI** report designed to analyze sales records, revenue streams, costs, and net profitability across European markets. Built using **Europe Sales Records** data, this project delivers comprehensive key performance indicators (KPIs), geographical distributions, product segmentations, and cross-channel performance insights.

---

## 📌 Project Overview

Understanding market-level dynamics, product profit margins, and distribution efficiency is critical for modern business intelligence. This project transforms complex European transaction data into clear, actionable executive insights through intuitive visualizations and custom DAX metrics.

### Key Business Metrics Captured:
- **Total Revenue:** $1.70B
- **Total Profit:** $501.68M
- **Total Cost:** $1.20B
- **Profit Margin:** ~29.45%
- **Units Sold:** 6,582,322 units

---

## 📊 Dashboard Architecture & Pages

The Power BI report (`Europe Sales Records.pbix`) is structured into two core interactive pages:

### Page 1: Executive Overview & Financial Performance
- **KPI Cards:** Displaying real-time aggregated metrics for **Units Sold**, **Total Profit**, **Total Revenue**, **Total Cost**, and **Profit Margin (%)**.
- **Bar Chart (Profit by Country):** Ranking European markets by net profitability (highlighting top performers like *Andorra*, *Ukraine*, and *Malta*).
- **Clustered Column Chart (Profit by Item Type):** Segmenting gross earnings across product lines (*Cosmetics*, *Office Supplies*, *Household*, etc.).
- **Line Chart (Revenue Trend over Time):** Analyzing multi-year revenue trajectories based on shipment/order date hierarchies.
- **Donut Chart (Revenue by Sales Channel):** Comparing distribution performance between **Online** ($830.37M) and **Offline** ($873.25M) channels.
- **Interactive Slicers:** Dynamic filtering by **Item Type** and **Order Year**.

### Page 2: Spatial & Product Optimization Analytics
- **Geographic Map:** Interactive spatial representation mapping total revenue volume and profitability tooltips per European nation.
- **Scatter Plot (Unit Price vs. Total Profit):** Evaluating product pricing strategy and volume sensitivity against overall returns.
- **Dynamic Slicers:** Full cross-filtering capabilities by **Year** and **Item Line**.

---

## 📁 Repository Structure

```text
├── Europe Sales Records.pbix                        # Main Power BI Report file containing layout & data model
├── Europe Sales Records.xlsx     # Source transactional dataset
└── README.md                     # Documentation file
