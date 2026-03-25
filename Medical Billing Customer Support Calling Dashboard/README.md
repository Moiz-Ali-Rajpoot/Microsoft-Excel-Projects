# 📞 Medical Billing Customer Support Dashboard — Microsoft Excel

> **Patient Call Tracking & CS Agent Productivity Intelligence** — A fully automated Excel dashboard that consolidates data from **multiple Google Sheets** via Power Query into a single source, tracking inbound/outbound calls, issue resolution rates, patient query types, and individual agent productivity — built to drive continuous improvement in customer service operations.

---

## 🗂️ Overview

This dashboard gives Customer Support managers a **real-time weekly and monthly view** of call center productivity within a Medical Billing operation. It tracks every patient interaction — from call volumes per agent to issue resolution status — enabling leadership to identify bottlenecks, manage pending cases, and benchmark CS agent performance.

Filterable by **Month**, **Location**, and **Week**, the dashboard dynamically refreshes all panels to reflect the selected period — powered by automated Power Query pipelines pulling from multiple Google Sheets sources.

---

## 📊 Dashboard Sections

### 1. 📈 Weekly Call Volume Trend — Inbound vs Outbound

A dual-line chart tracking daily call volumes (Monday–Friday) for the selected week, comparing Inbound and Outbound call trends side by side. Helps managers spot low-activity days and address staffing or workload distribution issues.

**Sample (Week 1, March):**
- Peak Outbound: 91 calls (Tuesday)
- Peak Inbound: 78 calls (Tuesday)
- Both lines tracked daily across the full work week

---

### 2. 👤 Agent-Level Call Breakdown

Individual CS agent cards showing their personal Inbound and Outbound call counts for the selected month — giving supervisors a clear view of each agent's contribution:

| Agent | In-Bound | Out-Bound |
|---|---|---|
| Usman | 0 | 0 |
| Urwah | 66 | 73 |
| Mary | 27 | 166 |
| Jennifer | 0 | 0 |

Inactive agents (0 calls) are immediately visible, enabling quick follow-up on productivity gaps.

---

### 3. ✅ Issues Resolution Summary

Circular donut KPI cards showing the resolution health of all patient issues for the selected location and month:

| Status | Rate |
|---|---|
| ✅ Resolved | **93%** |
| ⏳ Pending | **7%** |
| 🔺 Escalated | **0%** |
| ℹ️ Info Provided | **0%** |

A **Select filter (Pending/Resolved/Escalated)** instantly loads the patient-level detail table on the right — showing Patient Name, Phone No, Patient Type, and Reason for each case.

---

### 4. 📋 Pending / Resolved Patient Detail Table

A live drill-down table populated based on the status filter, listing individual patient records with:
- Patient Name
- Phone Number
- Patient Type (Follow-Up/Recheck, Appt/Scheduled Visit, Testing/Diagnostics, Walk-In, Occupational/Employer Visit, etc.)
- Reason (Insurance, Prescription, Billing, General Query, WorkersComp, Physicals, Results, etc.)

---

### 5. 📊 Top N Analysis — Patient Types & Call Reasons

A **Select Top N** control (e.g., Top 7) dynamically renders the most frequent patient types and call reasons for the selected month — side by side:

**Top Patient Types (Sample):**
- Follow-Up/Recheck — 243
- Other — 94
- Appt/Scheduled Visit — 38
- Testing/Diagnostics — 30
- Walk-In/General Visit — 20
- Occupational/Employer Visit — 2

**Top Call Reasons (Sample):**
- Follow-Up Visit — 238
- General Query — 82
- Scheduling — 36
- Prescription — 19
- Results — 15
- Physicals — 12
- Records — 9

---

## 🛠️ Tools & Technology

| Layer | Tool / Feature |
|---|---|
| **Platform** | Microsoft Excel (Advanced) |
| **Data Sources** | Multiple Google Sheets (connected and merged via Power Query) |
| **Data Pipeline** | Power Query — Extract, Transform, Load (ETL) from Google Sheets into a single consolidated source |
| **Transformations** | Merging multiple sheets, cleaning inconsistent data, reshaping call logs, standardizing categories |
| **Formulas** | Advanced Excel: SUMIFS, COUNTIFS, INDEX-MATCH, dynamic filtering logic, conditional aggregations |
| **Interactivity** | Month, Location, Week, Status, and Top N filters — all panels update simultaneously |
| **UI Design** | Agent avatar cards, circular donut KPI indicators, dual-line trend charts — fully native Excel |

---

## 💡 Excel & Power Query Expertise Demonstrated

- 🔗 **Multi-Source Google Sheets Integration** — Power Query connects to and consolidates call data from multiple Google Sheets into one unified Excel model — no manual copy-pasting
- 🔄 **Automated ETL Pipeline** — One refresh pulls the latest data from all sources, cleans and transforms it, and updates every visual and table automatically
- 🧹 **Advanced Power Query Transformations** — Handles messy, inconsistent raw call logs: standardizes agent names, fixes date formats, categorizes call reasons, removes duplicates
- 🎛️ **Dynamic Top N Control** — A single selector changes the number of results shown across both the patient type and call reason charts simultaneously
- 🏥 **Domain-Specific Design** — Dashboard built specifically for Medical Billing CS workflows — patient types, billing reasons, and escalation statuses are all contextually accurate
- 🎨 **Modern User-Friendly UI** — Agent avatar cards, circular resolution gauges, and clean tabular drill-downs make the dashboard accessible to non-technical CS supervisors

---

## 💼 Purpose & Business Value

- **CS Managers** — Monitor agent call productivity daily and monthly without manual reporting
- **Operations Leadership** — Track resolution rates and escalation trends to measure service quality
- **Team Leads** — Drill into pending cases instantly and assign follow-ups from the same dashboard
- **Process Improvement** — Top N analysis reveals the most common patient issues, enabling targeted training and workflow fixes
- **Billing Teams** — Understand which patient types and billing reasons generate the most inbound volume to optimize staffing and scripts

---

> 📌 **Note:** Due to data privacy and confidentiality, only a PDF screenshot is shared for visual reference. All patient names, phone numbers, and agent data are **sample/dummy data**. The live dashboard connects to real Google Sheets sources via automated Power Query pipelines.
