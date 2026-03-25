# 👥 Employee Analytics Dashboard — Power BI

> **HR & Payroll Intelligence** — Built with Microsoft Excel as the data source and Power BI for interactive workforce analytics and payroll insights.

---

## 🗂️ Overview

This repository contains **2 Power BI dashboards** (exported as PDFs) designed for an internal **Human Resources & Payroll Analytics** system. The dashboards provide a comprehensive view of workforce composition, department distribution, hiring trends, and salary breakdowns — empowering HR teams and management to make data-driven decisions.

> ⚠️ **Note:** All data used in these dashboards is **sample/dummy data** created for demonstration purposes. Figures, employee counts, and salary values are not reflective of any real organization. Real data will be connected during deployment.

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
| `Employee_Analytics.pdf` | Employee Overview Dashboard + Payroll Dashboard |

---

## 👤 Dashboard 1 — Employee Overview

A high-level snapshot of the entire workforce across locations, departments, designations, and experience levels.

### Key Metrics

| Metric | Value |
|---|---|
| **Total Employees** | 291 |
| **Male Employees** | 210 (72%) |
| **Female Employees** | 81 (28%) |

### Visuals Included

**By Location:**
- Islamabad: 247 employees (63 Female / 184 Male)
- Karachi: 44 employees (18 Female / 26 Male)

**By Position Level:**

| Level | Count | Share |
|---|---|---|
| Entry-Level | 123 | 42% |
| Mid-Level | 77 | 26% |
| Senior Level | 47 | 16% |
| Lead Level | 27 | 9% |
| Managerial Level | 11 | 4% |
| Executive Level | 3 | 1% |
| Senior Manager Level | 3 | 1% |

**By Tenure:** Distribution from 0 to 4.5 years — majority of staff fall in the 0–1 year range, indicating a growing and actively scaling organization.

**Total Employees by Month:** Line chart tracking monthly headcount trends across 2020–2025, with a peak hiring period in July–August (up to 49 new employees/month).

**Top Designations by Headcount:**
- Account Manager Operations — 120
- Virtual Assistant — 27
- Billing Executive Internee — 26
- Business Development Executive — 12
- Credentialing Analyst — 12

**By Department (with Gender Split):**
- Operations: 187 employees (M: 75% | F: 25%) — largest department
- VA: (M: 48% | F: 52%)
- Credentialing: (M: 80% | F: 20%)
- Sales: (M: 57% | F: 43%)
- Coding: (M: 64% | F: 36%)

---

## 💰 Dashboard 2 — Employee Payroll

A detailed payroll breakdown by location, department, salary band, and position level.

### Key Metrics

| Metric | Value |
|---|---|
| **Total Salaries — Islamabad** | Rs 5,729,700 |
| **Total Salaries — Karachi** | Rs 990,500 |
| **Grand Total Payroll** | Rs 6,720,200 |

### Visuals Included

**By Location & Gender:**
- Islamabad: Female Rs 1,770,500 | Male Rs 3,959,200
- Karachi: Female Rs 537,000 | Male Rs 453,500

**Salary Bucket Distribution:**

| Salary Range (PKR) | Employees |
|---|---|
| Rs 50K – 75K | 44 |
| Rs 35K – 50K | 37 |
| Rs 75K – 100K | 29 |
| Rs 100K – 150K | 22 |
| Rs 150K – 200K | 15 |
| Under Rs 35K | 7 |
| Rs 200K+ | 5 |

**Monthly Salary Trends:** Payroll peaks in July (Rs 982,000) and October–November (Rs 1,038,000), aligning with headcount growth visible in the Overview dashboard.

**Total Salaries by Department:**

| Department | Total Salary |
|---|---|
| Operations | Rs 4,255,200 |
| Coding | Rs 505,500 |
| Sales | Rs 309,000 |
| Credentialing | Rs 285,000 |
| IT & Networks | Rs 175,000 |
| Medical Record Mgmt Unit | Rs 107,000 |
| Admin | Rs 97,000 |
| HR | Rs 96,000 |
| Medical Scribe Unit | Rs 60,500 |

**Salaries by Position Level:**
- Entry-Level: Rs 3,137,700
- Senior Level: Rs 1,977,000
- Mid-Level: Rs 758,000
- Lead Level: Rs 687,500

---

## 💡 Purpose & Business Value

These dashboards were designed to support:

- **HR Teams** — Monitor headcount, tenure distribution, and gender diversity across departments
- **Finance & Payroll** — Track monthly salary trends, cost-per-department, and salary band distribution
- **Management** — Make informed hiring, compensation, and restructuring decisions
- **Operations** — Understand team composition by position level and office location

---

## 🚀 How to Use

1. Open the PDF file to view the exported dashboard snapshots
2. The live Power BI `.pbix` file connects to a **Microsoft Excel workbook** as its data source
3. To refresh with real data, replace the Excel source file and refresh the Power BI data model
4. Use the **Overview / Payroll** toggle in the top-right of the dashboard to switch between the two views

---

## 👤 Author

**Moiz Ali** — Reporting Analyst  
Built using Microsoft Power BI | Data Source: Microsoft Excel

---

*This project is for internal use. All employee counts, designations, and salary figures in the current version are sample/dummy data.*
