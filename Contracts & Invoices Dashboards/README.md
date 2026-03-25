# 📊 RCM Comprehensive Dashboards — Power BI

> **Revenue Cycle Management (RCM) Insights** — Built with Microsoft Excel as the data source and Power BI for interactive analytics and decision-making.

---

## 🗂️ Overview

This repository contains **4 Power BI dashboards** (exported as PDFs) built for an internal Revenue Cycle Management (RCM) system. The dashboards provide a 360° view of company **Invoices** and **Contracts** performance, enabling data-driven decision-making across departments.

> ⚠️ **Note:** All data used in these dashboards is **dummy/sample data**. Client names and figures are randomly generated for demonstration purposes only. Real data will be integrated during deployment.

---

## 🛠️ Tools & Technology

| Layer | Tool |
|---|---|
| **Data Source** | Microsoft Excel (.xlsx) |
| **BI & Visualization** | Microsoft Power BI Desktop |
| **Export Format** | PDF (for sharing & documentation) |

---

## 📁 Dashboard Files

| File | Description |
|---|---|
| `Invoices_Dashboards.pdf` | KPI Dashboard + Summary Dashboard for Invoices |
| `Contracts_Dashboard.pdf` | Contract Insights + Geographical Insights Dashboard |

---

## 🧾 Invoices Dashboards

### Dashboard 1 — Invoices KPI Dashboard

A high-level performance overview of all invoices for the period **Jan – Dec 2025**.

**Key Metrics:**
- **Total Invoices:** 1,281 *(+18.9% from Last Year)*
- **Charge Amount:** $1,465,857 *(+24.9% from LY)*
- **Received Amount:** $1,321,216 *(+18.2% from LY)*
- **Due Amount:** $142,192 *(+153.3% from LY)*

**Visuals Included:**
- Monthly trend lines for all 4 KPIs
- Donut charts breaking down figures **by Invoice Type** (Billing, Credentialing, FTE, PHD)
- Bar charts showing performance **by Lead Source** (Sales, Client Referral, Referral Program, Marketing)
- Breakdown **by Brand Name** (RCM Matter, East Main Health, DoctorPapers, Medimote LLC)

---

### Dashboard 2 — Invoices Summary Dashboard

A detailed tabular view for department-level analysis.

**Sections:**
- **Collection by Department (2025):** Month-by-month breakdown of Invoices, Charges, Received, and Due amounts across departments — Billing, Credentialing, FTE, Marketing, and PHD
- **Bottom 10 Clients by Charges:** Highlights lowest-performing client accounts for follow-up action
- **Collection by Payment Type (2025):** Monthly splits across ACH/Wire, Check, Credit Card, and Zelle — Total collected: **$1,323,230**

---

## 📑 Contracts Dashboards

### Dashboard 1 — Contract Insights

A comprehensive view of all active, terminated, and categorized contracts.

**Key Metrics:**
- **Total Contracts:** 1,181
- **Avg Govt Credits:** $154
- **Avg Commercial Credits:** $146
- **In-Network Avg %:** 3.7%
- **Out-of-Network Avg %:** 7.8%
- **Terminated Contracts:** 94 *(Termination Ratio: 7.96%)*

**Visuals Included:**
- Monthly trend of contracts across the year
- **Contracts by Brand:** RCM Matter dominates with 1,101 contracts
- **Contracts by Lead Source:** Sales (841) leads, followed by Client Referral (202) and Referral Program (114)
- **Top 10 Leads by Volume:** Zeeshan Mustafa (107), Kurt (93), Scott (84) are the top performers
- **Contracts by Type:** Billing & Credentialing Services Agreement (374) is the most common type

---

### Dashboard 2 — Geographical Contracts Insights

A geographic map-based view of contract distribution across the United States.

**Top 10 States by Contract Volume:**

| Rank | State | Contracts |
|---|---|---|
| 1 | Texas | 215 |
| 2 | California | 134 |
| 3 | Florida | 111 |
| 4 | New Jersey | 96 |
| 5 | New York | 78 |
| 6 | Maryland | 71 |
| 7 | Georgia | 63 |
| 8 | Arizona | 48 |
| 9 | Illinois | 46 |
| 10 | Pennsylvania | 32 |

An interactive bubble map visualizes contract density at the state level, offering quick regional insights.

---

## 💡 Purpose & Business Value

These dashboards were designed to support:

- **Finance Teams** — Track invoice aging, due amounts, and collection efficiency
- **Sales & Operations** — Monitor lead source performance and contract acquisition trends
- **Management** — Executive-level KPI summaries with year-over-year comparisons
- **Geographic Expansion** — Identify high-performing and underserved states for growth planning

---

## 🚀 How to Use

1. Open the PDF files to view the exported dashboard snapshots
2. The live Power BI `.pbix` file connects to an **Excel workbook** as its data source
3. To refresh with real data, replace the Excel source file and refresh the Power BI model

---

## 👤 Author

**Moiz Ali** — Reporting Analyst  
Built using Microsoft Power BI | Data Source: Microsoft Excel

---

*This project is for internal use. All client names and financial figures in the current version are sample/dummy data.*
