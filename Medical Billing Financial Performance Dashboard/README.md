# 🏥 Medical Billing Financial Performance Dashboard — Microsoft Excel

> **RCM Financial Intelligence & Team Performance Tracking** — A fully automated, data-driven Excel dashboard built with **Advanced Formulas, Power Query, and automated data pipelines** — tracking Claims, Charges, Payments, AR aging, rejection rates, and individual/team target achievements with top performer recognition for monthly bonus nominations.

---

## 🗂️ Overview

This is one of the most advanced Excel dashboards in this portfolio — a **Medical Billing Financial Performance Dashboard** designed for RCM (Revenue Cycle Management) operations. It consolidates financial performance data across multiple management levels (AMOs, Team Leads, Teams) and provides a real-time snapshot of how each unit is performing against their monthly targets.

The dashboard is filterable by **Month** and gives decision-makers a complete operational and financial picture — from raw charge volumes down to individual rejection rates — all automated through Power Query and formula-driven pipelines.

---

## 📊 Dashboard Sections

### 1. 📈 Forecasted vs Actual Performance

Tracks projected vs actual billing performance for the month:

| Metric | Forecasted | Forecasted MTD | Actual |
|---|---|---|---|
| Charges | $5,450,385 | $5,268,705 | $6,240,415 |
| Payment | $2,434,682 | $2,329,475 | $2,605,458 |
| **PC Ratio %** | **45%** | **44%** | **42%** |

---

### 2. 🎯 AMO's Targets vs Actual (Assistant Manager Operations)

Individual AMO-level target tracking with % achievement — color-coded indicators show who is on track, above target, or underperforming. Top-performing AMOs are highlighted in the **Top AMOs Target Achievers** panel with a 5-star rating and trophy recognition.

---

### 3. 🎯 Team Targets vs Actual

Team-level breakdown comparing monthly targets against actual MTD performance across all billing teams with directional arrows (▲/▼) and % age indicators:

| Sample Metric | Target | Actual MTD | % Age |
|---|---|---|---|
| Team 1 | $367,505 | $379,357 | +3% ▲ |
| Team 2 | $347,257 | $453,261 | +31% ▲ |
| Team 3 | $115,817 | $219,141 | +89% ▲ |

**Top Teams Target Achievers** panel recognizes the highest-performing teams with 5-star ratings and names displayed for bonus nomination.

---

### 4. 💰 AR (Accounts Receivable) Performance — RCM Level

Full AR aging bucket analysis showing Opening AR vs Closing AR vs Roll Over with % age movement:

| AR Bucket | Opening AR | Closing AR | Roll Over | % Age |
|---|---|---|---|---|
| Current | $2,853,463 | $2,747,011 | ($106,452) | -4% |
| 30-60 Days | $1,367,967 | $1,350,041 | ($17,927) | -1% |
| 60-90 Days | $869,622 | $1,218,861 | $349,239 | +40% |
| 90-120 Days | $761,367 | $774,711 | $13,344 | +2% |
| 120-180 Days | $1,480,561 | $1,196,872 | ($283,689) | -19% |
| 180+ Days | $5,262,775 | $5,821,508 | $558,733 | +11% |
| **Total** | **$12,595,754** | **$13,109,003** | **$513,248** | **+4%** |

---

### 5. 💰 Team AR Performance

Same AR aging analysis drilled down to individual team level with a **Select Team** filter — enabling managers to isolate any team's AR movement and hold them accountable for collections.

---

### 6. ❌ RCM Rejections

Tracks claim submission quality at the RCM level:

| Metric | Submitted | Accepted | Rejected |
|---|---|---|---|
| Claims | 3,126 | 3,111 | 15 |
| Amount | $532,153 | $527,127 | $5,026 |
| **FCR Rate %** | | | **0.48%** |
| **FCA Rate %** | | | **99.52%** |

---

### 7. ❌ Team Rejections

Same rejection analysis filtered by **Team** and **Week** — enabling weekly quality audits per team:

| Metric | Submitted | Accepted | Rejected |
|---|---|---|---|
| Claims | 1,882 | 1,872 | 10 |
| Amount | $127,323 | $123,823 | $3,500 |

---

### 8. 🏆 Top Performers Recognition Panel

A dedicated panel nominates top-performing AMOs and Teams with 5-star ratings and trophy visuals — used directly by management for **monthly bonus decisions**.

---

## 🛠️ Tools & Technology

| Layer | Tool / Feature |
|---|---|
| **Platform** | Microsoft Excel (Advanced) |
| **Data Transformation** | Power Query — cleaning, merging, and reshaping messy raw data |
| **Automation** | Automated data pipelines — refresh updates all panels instantly |
| **Formulas** | Advanced Excel: INDEX-MATCH, SUMIFS, IFERROR, dynamic named ranges, nested IFs |
| **Visualizations** | KPI cards, conditional formatting, color-coded status indicators, directional arrows |
| **Interactivity** | Month selector, Team selector, Week selector — all panels update dynamically |

---

## 💡 Excel & Data Engineering Expertise Demonstrated

- ⚙️ **Power Query Pipelines** — Raw messy billing data from multiple sources is cleaned, transformed, and loaded automatically — no manual reformatting needed
- 🔄 **Automated Data Refresh** — One click refreshes the entire dashboard across all panels, AR buckets, rejection tables, and target trackers
- 🧮 **Advanced Formula Architecture** — Complex multi-condition SUMIFS, dynamic AR aging calculations, and % achievement logic built without any macros or VBA
- 🎨 **Professional Financial UI** — Dark-themed financial dashboard aesthetic with color-coded performance indicators, trophy visuals, and clean tabular layouts — all native Excel
- 📐 **Multi-Level Hierarchy Tracking** — Simultaneously tracks performance at RCM, AMO, Team Lead, and Team levels in one unified view
- 🏆 **Gamified Performance Recognition** — Built-in top performer nomination system tied directly to financial data — not a manual process
- 💼 **Business-Ready Reporting** — Dashboard is designed to be presented directly to leadership in monthly review meetings

---

## 💼 Purpose & Business Value

- **Finance & Billing Leadership** — Monitor actual vs forecasted charges and payment collection in real time
- **Operations Managers** — Hold AMOs and teams accountable with target vs actual tracking and visual indicators
- **AR Management** — Identify aging buckets at risk of bad debt and take corrective action per team
- **Quality Control** — Track rejection rates per team and per week to enforce billing accuracy standards
- **HR & Payroll** — Use top performer data directly for bonus nomination and incentive decisions
- **Executives** — One-screen monthly performance review covering the entire billing operation

---

> 📌 **Note:** Due to data privacy and confidentiality, the PDF screenshot is shared for visual reference only. All financial figures, team names, and employee data are **sample/dummy data** for demonstration purposes. The actual dashboard connects to live Excel data sources via Power Query pipelines.
