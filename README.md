# 🟡 Blinkit Grocery Sales Dashboard — Power BI

A single-page Power BI dashboard analysing sales, product, and outlet performance for **Blinkit** (India's quick-commerce grocery delivery platform). The report is built on the *BlinkIT Grocery Data* dataset and is intended for retail analysts and business stakeholders who need a consolidated view of revenue, ratings, and outlet metrics.

---

## 📁 File

| File | Description |
|---|---|
| `blinkit_dashboard.pbix` | Power BI Desktop report file |

**Tool required:** [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

---

## 📊 Dashboard Overview

The report contains **one page — Home** — with a fully interactive layout themed in Blinkit's signature yellow branding.

### KPI Cards (Top-Level Metrics)
| Metric | Description |
|---|---|
| **Total Sales** | Sum of all sales revenue across the dataset |
| **Average Sales** | Mean sales value per record |
| **Number of Items** | Total count of distinct grocery items |
| **Average Rating** | Mean customer rating across products |

---

### Visuals & Charts

| Visual | Type | What It Shows |
|---|---|---|
| **Outlet Establishment** | Area Chart | Total sales trend by outlet establishment year |
| **Outlet Size** | Donut Chart | Sales distribution split by outlet size (Small / Medium / Large) |
| **Outlet Location** | Funnel Chart | Sales breakdown by outlet location tier (Tier 1 / 2 / 3) |
| **Outlet Type** | Pivot Table | Side-by-side comparison of all outlet types across Total Sales, No. of Items, Avg Sales, Avg Rating, and Item Visibility |
| **Fat Content** | Donut Chart | Average rating split between Low Fat and Regular items |
| **Item Type** | Bar Chart | Average rating ranked by grocery item category |
| **Fat by Outlet** | Clustered Bar Chart | Avg rating comparison of Low Fat vs Regular items across outlet location tiers |

---

### Slicers (Filters)

Users can dynamically filter the entire dashboard using three slicers:

- **Outlet Location Type** — filter by city tier
- **Outlet Size** — filter by store size
- **Item Type** — filter by grocery product category

A **Metric** slicer is also present for toggling between different measure views.

---

## 🗂️ Data Source

| Property | Value |
|---|---|
| **Dataset** | BlinkIT Grocery Data |
| **Key Fields** | `Item Type`, `Item Fat Content`, `Item Visibility`, `Outlet Type`, `Outlet Size`, `Outlet Location Type`, `Outlet Establishment Year` |
| **Key Measures** | `Total Sum Sales`, `Average Sales`, `No of Items`, `Avg Rating` |

---

## 🎨 Design

- **Theme:** CityPark (Power BI built-in) customised with Blinkit brand assets
- **Brand assets included:** Blinkit yellow app icon, delivery icon, shopping bag icon, rating icon, and increase/trend icons
- **Background image:** Custom dashboard backdrop (`Picture2.png`)

---

## 🚀 Getting Started

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Open `blinkit_dashboard.pbix` in Power BI Desktop.
3. If prompted about data source credentials, update the connection to point to your local copy of the BlinkIT Grocery Data source.
4. Use the slicers on the dashboard to explore data by outlet location, size, and item type.

---

## 📌 Use Cases

- Track overall revenue and average sales performance at a glance
- Compare outlet types and sizes to identify top-performing store formats
- Analyse how product fat content relates to customer ratings
- Understand sales trends over time by outlet establishment year
- Filter views by location tier or item category for targeted insights

---

## 📝 Notes

- This dashboard was last modified on **27 August 2025**.
- The report is read-only friendly — all interactions are via slicers and built-in visual cross-filtering.
- No row-level security (RLS) is configured in this file.
