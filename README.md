# 📊 Power BI Dashboards — Advanced Business Intelligence

> **Enterprise-Grade Analytics Built in Power BI** — Connecting data from Excel, EHR Software, Google Sheets, Databases, and more — transformed via **Power Query & DAX** into fully interactive, modern dashboards for data-driven decision making across Healthcare, RCM, HR, Sales, Operations, and more.

---

## 🗂️ Overview

This repository is a collection of **production-level Power BI dashboards** built to solve real business problems across multiple industries. Each dashboard demonstrates the full data analytics pipeline — from raw, messy source data all the way to clean, interactive, executive-ready visuals.

Every dashboard in this repo follows the same pipeline architecture:

**Raw Data Sources → Power Query ETL → Data Model → DAX Measures → Modern Interactive Dashboard**

---

## 📁 Projects

| Dashboard | Domain | Data Sources |
|---|---|---|
| **Contracts & Invoices Dashboards** | Healthcare / RCM | Excel |
| **Employee Analytics** | HR | Excel |
| **HR Analytics** | HR / Operations | Excel |
| **Medical Billing Credentialing Dashboard** | Healthcare / RCM | Excel |
| **Sales Operations Dashboard** | Sales | Excel |
| **Airline Performance** | Operations / Transport | Excel |
| **Life Expectancy** | Public Health / Research | Excel |
| **Paradise Restaurant** | Food & Beverage | Excel |
| **Seattle Construction** | Construction / Project Mgmt | Excel |

> 🔄 More dashboards are actively being added across Healthcare, E-Commerce, Sales, Marketing, and Finance domains.

---

## 🛠️ Tools & Technology

| Layer | Tool / Method |
|---|---|
| **Visualization Platform** | Microsoft Power BI Desktop |
| **Data Sources** | Excel, EHR Software, Google Sheets, CSV Exports, Databases |
| **Data Pipeline** | Power Query — Multi-source Extract, Transform, Load (ETL) |
| **Query Language** | M Query — custom transformations, merges, conditional columns |
| **Calculation Engine** | DAX — measures, calculated columns, KPI logic, time intelligence |
| **Automation** | Scheduled refresh keeps dashboards up to date automatically |

---

## ⚙️ Technical Approach

### 🔗 Multi-Source Data Integration
Raw data is pulled from multiple disconnected sources — Excel workbooks, EHR software exports, Google Sheets, CSV files, and databases — and unified into a **single Power BI data model** via Power Query. Relationships between tables are defined to enable cross-filtering and drill-through across all visuals.

### 🧹 Power Query Transformations
Every pipeline includes custom M Query scripts that handle real-world data messiness: inconsistent formats, duplicates, mismatched naming conventions, multi-source merges, conditional column logic, and reshaping raw data into clean analytical structures ready for modeling.

### 📐 DAX Measures & Calculations
Business logic is implemented using DAX — covering dynamic KPI calculations, MOM% and YOY% comparisons, running totals, conditional aggregations, and time intelligence functions. Measures are reusable, performant, and decoupled from raw data.

### 🔄 Automated Data Refresh
Once published, dashboards can be configured for scheduled refresh — pulling the latest data from all connected sources and updating every visual, KPI, and chart automatically without manual intervention.

---

## 🎨 Design Philosophy

Every dashboard in this repo is built with a **modern, user-friendly UI** — designed to be presented directly in business meetings and shared with stakeholders without any modifications:

- **Consistent professional color themes** — dark navy/teal or clean light themes with branded accent colors
- **KPI cards** with current period value, MOM%, This Year, and Last Year comparisons
- **Color-coded visuals** — highlights trends, risks, and top performers automatically
- **Interactive slicers & filters** — Year, Month, Department, Location, and Category filters cross-filter all visuals simultaneously
- **Multi-page navigation** — clean tab/button navigation between dashboard views
- **Drill-through & tooltips** — click any visual to drill into underlying detail
- **Clean layout and visual hierarchy** — dense data made scannable and readable at a glance

---

## 💼 Business Domains Covered

| Domain | Use Cases |
|---|---|
| **Healthcare / RCM** | Invoice KPIs, Contract Insights, Credentialing Tracking, AR Analysis, Provider Performance |
| **HR & Operations** | Headcount, Payroll, Attendance, Gender Diversity, Position Levels, Tenure |
| **Sales** | Pipeline Performance, Target vs Actual, Lead Source Analysis, Revenue Tracking |
| **Operations** | Airline Performance, Delay Analysis, Route Efficiency, Operational KPIs |
| **Public Health** | Life Expectancy Trends, Global Health Analytics |
| **Food & Beverage** | Restaurant Sales, Menu Performance, Revenue Analytics |
| **Construction** | Project Tracking, Cost Analysis, Timeline Performance |
| **E-Commerce** | Orders, Revenue, Returns, Customer Analytics *(coming soon)* |
| **Marketing** | Campaign Analytics, Conversion Funnels, Channel Performance *(coming soon)* |

---

## 💡 Why Power BI?

> Power BI transforms raw, disconnected data into living, interactive dashboards that update automatically and can be shared across an entire organization — turning data into decisions at every level.

- ✅ Connects natively to Excel, Google Sheets, databases, APIs, and 100+ data sources
- ✅ DAX enables complex business calculations that go far beyond basic spreadsheet formulas
- ✅ Published dashboards are accessible from any browser or mobile device
- ✅ Row-level security ensures the right people see only the right data
- ✅ Scheduled refresh keeps every dashboard current without manual updates
- ✅ One report can serve an entire organization — from frontline managers to C-suite

---

> 📌 **Note:** All dashboards use **sample/dummy data** for demonstration and privacy purposes. Each project folder contains a detailed README with dashboard insights, KPI descriptions, and technical notes. The live versions connect to real data sources and are actively used for business decision-making.
