# 📊 Task 4 — Sales Dashboard Design

> **Elevate Labs Data Analyst Internship** | Task 4 of 5

An interactive, multi-page sales dashboard built with **HTML + Chart.js**, covering KPI cards, time-series trends, category analysis, and regional breakdowns — inspired by Power BI and Tableau dashboard design principles.

---

## 🚀 Live Demo

Open `dashboard.html` directly in any browser — no installation needed.

---

## 📁 Project Structure

```
task4-sales-dashboard/
│
├── dashboard.html          # ✅ Interactive Sales Dashboard (main deliverable)
├── sales_data.csv          # 📦 Custom dataset — 60 orders across 2024
├── Sales_Dashboard_PPT.pptx  # 📽️ PowerPoint summary (6 slides)
└── README.md               # 📄 This file
```

---

## 🎯 Objective

Design an interactive dashboard for business stakeholders that:
- Displays key KPIs (Sales, Profit, Orders, Margin)
- Enables filtering by **Quarter** and **Region** via slicers
- Includes **time-series trend analysis** across all 12 months
- Covers **4 product categories** and **4 geographic regions**
- Follows consistent color theme and navigation structure

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **HTML5 + CSS3** | Dashboard layout, dark theme, responsive design |
| **Chart.js 4.4** | All chart rendering (line, bar, doughnut, area) |
| **Power BI** *(concepts)* | KPI cards, DAX measures, slicers, drill-through |
| **Tableau** *(concepts)* | Calculated fields, story mode, dashboard actions |
| **Python / Pandas** | Data generation and preprocessing concepts |

---

## 📊 Dashboard Pages

### 1. Overview
- **4 KPI Cards** — Total Sales ($54,170), Profit ($10,834), Orders (60), Margin (20%)
- **Monthly Sales & Profit Line Chart** — 12-month trend with area fill
- **Category Doughnut Chart** — Electronics / Furniture / Office Supplies
- **Regional Bar Chart** — North / South / East / West
- **Category Profit Chart** — Horizontal bar
- **Quarterly Growth Chart** — Q1 to Q4 progression
- **Top Products Table** — Ranked with category tags and profit bars

### 2. Trends
- Full-year time-series for Sales vs Profit
- Cumulative Sales Growth (running total area chart)
- Average Order Value by Month

### 3. Categories
- Category sales comparison (bar)
- Category profit share (pie)
- Category performance per quarter (grouped bar)

### 4. Regions
- Per-region KPI cards
- Regional sales bar chart
- Regional market share doughnut

---

## 🎛️ Slicers / Filters

| Filter | Options |
|--------|---------|
| Quarter | All, Q1, Q2, Q3, Q4 |
| Region  | All, North, South, East, West |

All charts and KPIs update instantly on filter selection.

---

## 📦 Dataset

**`sales_data.csv`** — Custom-generated dataset with 60 transactions across FY 2024.

| Column | Description |
|--------|-------------|
| Order_ID | Unique order identifier |
| Date | Transaction date |
| Region | North / South / East / West |
| Category | Electronics / Furniture / Office Supplies |
| Product | Laptop, Phone, Tablet, Monitor, Chair, Desk, Bookshelf, Paper, Pens, Stapler, Notebook |
| Sales | Revenue in USD |
| Profit | Profit in USD |
| Quantity | Units sold |
| Discount | Discount applied |

---

## 📈 Key Insights

| Insight | Finding |
|---------|---------|
| **Top Category** | Electronics — 55% of total sales ($29,810) |
| **Top Region** | South — 29% market share ($15,885) |
| **Best Month** | December — highest revenue driven by seasonal demand |
| **Top Product** | Laptop — highest per-order value |
| **Profit Margin** | Consistent 20% across all categories |
| **Q4 Growth** | Strongest quarter — $16,430 total sales |

---

## 💡 Dashboard Design Principles Applied

- ✅ **KPI Cards** with accent color borders and trend indicators
- ✅ **Slicers/Filters** for Quarter and Region interactivity
- ✅ **Time-Series Analysis** — 12-month line chart with dual series
- ✅ **Consistent Color Theme** — Dark theme with cyan/purple/green accents
- ✅ **Navigation Menu** — 4 pages: Overview, Trends, Categories, Regions
- ✅ **Responsive Charts** — All charts resize with container

---

## ❓ Interview Q&A

**Q1: What are the key elements of a dashboard?**  
KPI cards, time-series charts, filters/slicers, trend analysis, comparison views, and a consistent color-coded theme.

**Q2: What is a KPI?**  
A Key Performance Indicator is a measurable value showing how effectively a company is achieving business objectives. Examples: Total Sales, Profit Margin, Order Count.

**Q3: What are slicers in Power BI?**  
Visual filter controls that allow users to interactively segment data by fields like Region, Category, or Quarter — updates all connected visuals automatically.

**Q4: Difference between Power BI and Tableau?**  
Power BI integrates deeply with Microsoft 365 and uses DAX for calculations. Tableau offers stronger visual flexibility with VizQL. Both are leading enterprise BI tools — choice depends on ecosystem and use case.

**Q5: How do you make a dashboard interactive?**  
Add slicers, cross-filtering between visuals, drill-through pages, dynamic tooltips, and navigation buttons. In HTML, use event listeners to re-render charts on filter change.

**Q6: How do you handle large datasets in dashboards?**  
Use data aggregation, star-schema data modeling, indexing on key columns, DirectQuery mode (Power BI), and avoid loading row-level detail into visuals unnecessarily.

**Q7: What chart types for trend analysis?**  
Line charts (continuous trends), area charts (cumulative values), bar charts (period-over-period comparison), and combo charts (dual-axis for Sales + Margin).

---

## 📤 How to Run

1. Download or clone this repository
2. Open `dashboard.html` in any modern browser (Chrome / Firefox / Edge)
3. Use the **Quarter** and **Region** slicers to filter data
4. Navigate between **Overview / Trends / Categories / Regions** pages

No server or installation required.

---

## 👤 Author

**Karmveer Kumar**  
Data Analyst Intern — Elevate Labs  
Task 4: Dashboard Design | FY 2024
