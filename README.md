# blinkit-dashboard-
# Blinkit Analytics: Sales, Customer & Outlet Insights Dashboard

An interactive **Power BI** dashboard to analyze Blinkit’s sales performance, customer satisfaction, and outlet distribution—uncovering actionable insights for business optimization.

> 📁 This repository contains documentation, DAX measures, Power Query scripts, and placeholders for the `.pbix` file and datasets.

---

## 1) Project Title / Headline
**Blinkit Analytics: Sales, Customer & Outlet Insights Dashboard**  
A dynamic Power BI report focused on sales trends, item performance, outlet efficiency, and customer ratings.

## 2) Short Description / Purpose
The dashboard provides a comprehensive view of Blinkit KPIs and drivers. It helps decision-makers evaluate performance across items and outlets, identify optimization opportunities, and monitor customer satisfaction.

## 3) Tech Stack
- 📊 **Power BI Desktop** – primary visualization & modeling
- 📂 **Power Query** – data shaping and cleansing
- 🧠 **DAX** – calculated measures and dynamic logic
- 📝 **Data Modeling** – relationships across items, outlets, and sales tables
- 📁 **File formats** – `.pbix` (report), `.png` (screenshots)

## 4) Data Source
> See `data/README.md` for schema details.

- **Sales transactions**: item id, outlet id, date, units, revenue
- **Items**: item type, fat content, rating
- **Outlets**: size, location, establishment year/type

## 5) Features / Highlights

### Business Problem
Managers need a fast, interactive way to compare categories and outlets, understand geographic distribution, and track ratings—none of which is simple with raw data.

### Goal of the Dashboard
- Monitor sales across multiple dimensions
- Identify high/low performing outlets and categories
- Surface opportunities in pricing, assortment, and inventory
- Track customer satisfaction via ratings

### Walkthrough of Key Visuals
**KPI Cards**
- Total Sales, Average Sales per transaction, Number of Items, Average Rating

**Breakdown Charts**
1. **Total Sales by Fat Content** – *Donut*
2. **Total Sales by Item Type** – *Bar*
3. **Fat Content by Outlet for Total Sales** – *Stacked Column*
4. **Total Sales by Outlet Establishment** – *Line*
5. **Sales by Outlet Size** – *Donut/Pie*
6. **Sales by Outlet Location** – *Funnel Map*
7. **All Metrics by Outlet Type** – *Matrix Card*

### Business Impact & Insights
- **Sales Optimization**: identify categories (e.g., low-fat vs. regular) that drive revenue
- **Outlet Strategy**: size & establishment types linked to performance
- **Customer Insights**: ratings aligned to assortment choices
- **Geographic Focus**: pinpoint under/over-performing regions
- **Operational Efficiency**: support decisions in inventory and promotions

---

## Getting Started

### Prerequisites
- Power BI Desktop (latest)
- CSV/Parquet files placed under `/data` (see `data/README.md`)
- Optional: Fonts/brand assets for visuals

### Quick Start
1. Place your dataset files into `/data`.
2. Open `powerbi/Blinkit-Analytics.pbix` in Power BI Desktop.
3. Update **Power Query** data source paths if prompted.
4. Refresh the report.  
5. (Optional) Adjust DAX in `measures/dax_measures.dax`.

### Repo Scripts
- **DAX**: `measures/dax_measures.dax`
- **Power Query M**: `powerbi/queries/power_query.m`

---

## Screenshots
Add PNGs in `/docs/images` and embed here:

