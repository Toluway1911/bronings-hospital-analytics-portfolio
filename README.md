# bronings-hospital-analytics-portfolio
bronings-hospital-analytics-portfolio
# Bronings University Hospital Group — Advanced Healthcare Analytics Portfolio

## 🏥 Project Overview
This enterprise-grade portfolio showcases an end-to-end healthcare analytics and data governance transformation executed for **Bronings University Hospital Group**. The project addresses complex operational challenges across elective waiting lists, clinical coding revenue leakage, theatre productivity, workforce staffing governance, and executive board reporting. 

Designed for healthcare executives, NHS trusts, and international clinical governance boards, this repository demonstrates rigorous data architecture from raw CSV ingestion and Snowflake cloud warehousing to advanced SQL querying, Python automation, and dual-platform executive dashboards (Power BI and Tableau).

---

## 🛠️ Tools & Technology Stack
* **Cloud Data Warehouse:** Snowflake (`BRONINGS_ANALYTICS.HOSPITAL_OPERATIONS`)
* **Database Management & Querying:** SQL Server Management Studio (SSMS) & T-SQL (CTEs, Window Functions, JOINs)
* **Business Intelligence & Dashboards:** Power BI Desktop (12 advanced DAX measures) & Tableau Public
* **Data Transformation & Automation:** Python (`pandas`, `numpy`, `openpyxl`, Jupyter Notebooks)
* **Spreadsheet Analytics & Modeling:** Microsoft Excel (Advanced Pivot Tables, Power Query)
* **Executive Presentation:** PowerPoint (Boardroom-ready narrative and challenge Q&A)

---

## 📊 Key Findings & Metrics (Verified)
* **Elective Care & RTT Compliance:** Overall Referral-to-Treatment (RTT) compliance stands at **87.4%**, breaching the **92.0%** NHS statutory target. **Trauma & Orthopaedics (OR)** recorded the lowest compliance at **84.2%** (Red status), with 90th percentile wait times exceeding **34.2 weeks**. Exactly **76 patients** are actively breaching the 18-week statutory threshold.
* **Clinical Coding Revenue Leakage:** Inpatient data audits uncovered **28 missing HRG codes**, creating a direct financial exposure of **£51,800** at £1,850 per episode.
* **Theatre Productivity & Wastage:** Monthly theatre wasted costs total **£94,200.0** (**£1,130,400.0 annualized**), driven by downstream bed shortages (e.g., T&O losing 14 operating sessions in a single week).
* **Workforce Staffing & Agency Spend:** Ward W-01 recorded **142 confirmed agency shifts**, representing an estimated expenditure of **£54,670.00** at £385/shift, compounded by 34 unflagged workforce records.
* **Clinical Governance & Quality:** The 30-day emergency readmission rate reached **11.4%**, breaching the **10.0%** clinical governance ceiling. Overall Data Quality (DQ) scores across core datasets average **96.4%** post-cleansing.

---

## 📂 Repository Structure
* `/excel`: Audited investigation logs, KPI calculations, and exception models.
* `/sql`: 12 production-grade T-SQL investigation queries with descriptive comments.
* `/snowflake`: DDL setup scripts and table schemas for `BRONINGS_ANALYTICS`.
* `/powerbi`: 6-page interactive Power BI executive dashboard (.pbix).
* `/tableau`: Tableau workbook and public deployment link (.twbx).
* `/python`: Jupyter Notebook automating weekly waiting list extraction and Excel reporting.
* `/presentation`: 12-slide executive board presentation with pre-prepared Q&A.

---

## 📈 Dashboard Previews
* **Executive Summary:** RAG KPI scorecards tracking Trust-wide performance against NHS standards.
* **Emergency Department:** 4-hour compliance trend line charts (91.2% actual vs 95.0% target).
* **Outpatient Waiting:** Specialty-level RTT compliance and rolling 12-week average waiting trends.
* **Capacity:** Bed occupancy rates (peaking at 94.2% on Ward W-01) and ALOS trends.
* **Finance:** YTD budget variance and departmental agency spend percentage tracking.
* **Workforce:** Staff vacancy rates and agency shift usage trends across all wards.

---

## 👤 Author & Contact
* **Analyst:** Advanced Healthcare Data Analyst & Public Sector Analytics Specialist  
* **GitHub Portfolio:** [github.com/bronings-hospital-analytics-portfolio](https://github.com/bronings-hospital-analytics-portfolio)  
* **Tableau Public:** [tableau.com/app/profile/bronings.analytics](https://public.tableau.com/app/profile/bronings.analytics)  
* **Professional Inquiry:** Available for NHS Data Analyst, BI Developer, and Healthcare Analytics leadership roles.
