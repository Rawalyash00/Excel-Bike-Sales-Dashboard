# Excel — Bike Sales Dashboard

![Bike Sales Dashboard](https://github.com/user-attachments/assets/948a3047-0404-4887-b689-8fdb5c39c4e3)

> **About this project.** A guided project — I worked through a public bike-sales
> exercise to practise Excel data cleaning, pivot tables and dashboard layout.
> Kept here as a learning artifact. For dashboards built for real stakeholders, see my
> [Power BI HR dashboard](https://github.com/yaashhrawal/powerbi-hr-analytics-dashboard);
> professionally I built Tableau KPI dashboards at MedNext Pharma and DoorDash revenue
> reporting at ArcGate.

An Excel dashboard over bike sales data, analysing what sells, to whom, and where.

**Files:** `Bike Sales DashBoard.xlsx` (dashboard) · `Excel Project Dataset.xlsx` (raw data) · `Bike Sales Dashboard.png` (preview)

---

## What it shows

- **Purchase behaviour by demographic** — income, age bracket, marital status, education
- **Commute distance vs purchase** — does travel distance predict buying a bike
- **Regional breakdown** — sales across geographies
- **Gender and age-band comparison** of average income among purchasers

Slicers make the whole dashboard filterable — region, education, marital status.

---

## How it was built

| Step | |
|---|---|
| **Cleaning** | Removed duplicates, standardised categorical values, corrected data types |
| **Transformation** | Derived age brackets from raw age; abbreviated long category labels |
| **Analysis** | Pivot tables per question |
| **Presentation** | Charts wired to pivots, slicers for cross-filtering, single-screen layout |

**Tool:** Microsoft Excel — pivot tables, pivot charts, slicers, `IF` / `VLOOKUP` for derived fields.

---

## Opening it

Open `Bike Sales DashBoard.xlsx` and go to the **Dashboard** sheet. `Excel Project Dataset.xlsx` holds the source data if you want to rebuild it from scratch.

---

Built by [Yash Rawal](https://github.com/yaashhrawal).
