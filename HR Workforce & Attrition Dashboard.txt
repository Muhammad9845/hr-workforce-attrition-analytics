# HR Workforce & Attrition Analytics Dashboard

A comprehensive, enterprise-grade **Power BI Dashboard** analyzing organizational workforce demographics, structural stability, and corporate attrition behavior profiles. Built completely within Power BI, this project cleans, models, and transforms raw HR staging files into a highly interactive, dual-layered executive reporting solution.

## 📊 Core Executive Metrics

### 🏢 Workforce Composition Baseline
* **Total Headcount Managed:** 1,470 Employees
* **Gender Ratio Structure:** 60% Male (882) | 40% Female (588)
* **Active Workforce Health:** 92% On Service (1,353) | 8% Retrenchment Baseline (117)
* **Promotion Status Velocity:** 63.8% Recently Promoted (938) | 21.8% Stagnant Retention (321)

### 📉 Active Attrition Group Parameters (Subset Focused)
* **Analyzed Sample Footprint:** 528 Employees
* **Total Attrition Event Volume:** 106 Departures
* **Organizational Attrition Rate:** 20%
* **Demographic Cohort Averages:** Average Age: 30 Years Old | Average Tenure: 6 Years

---

## 💡 Key Organizational Insights

* **The Gender Attrition Disparity:** While the macro headcount skews heavily male (60%), attrition tracking highlights a significantly higher volatility rate among **Female employees (27%)** compared to **Male counterparts (18%)**. This signals an urgent need to evaluate workplace inclusivity, flexibility guidelines, or equitable growth pathways.
* **Early Career Friction (Tenure Risk):** The vast majority of company departures occur extremely early in the employee lifecycle. Employees with **1 to 2 years of tenure** account for the largest absolute volume of departures (37 total events). 
* **High-Exposure Vulnerability Areas:** 
  * **By Department:** The **Research & Development** department sustains the heaviest absolute loss footprint with 63 total departures.
  * **By Job Role:** Frontline operational roles like **Laboratory Technicians (29)**, **Research Scientists (28)**, and **Sales Executives (23)** act as primary corporate turnover drivers.
* **Marital & Demographic Stability Filters:** **Single employees** display substantially higher voluntary or involuntary transition patterns (57 departures) than Married (35) or Divorced (14) cohorts, pointing toward opportunities for tailored lifestyle or corporate benefit adjustments.

---

## 🛠️ Data Architecture & Power BI Workflow

This analytics project was developed **100% natively inside Power BI Desktop**, leveraging its end-to-end data transformation stack:

1. **Data ETL & Extraction (Power Query):** Loaded raw, unformatted HR tabular files directly into the Power Query engine. Performed data profiling, verified data types, and constructed logical conditional columns (such as Age Groups and Commute Distance buckets) natively using the M formula language.
2. **Analytical Data Modeling (DAX):** Designed a robust tabular data model with explicit calculations. Authored custom **Data Analysis Expressions (DAX)** measures to handle advanced cross-filtering interactions, multi-dimensional percentages, and employee status tracking metrics including:
   * `Total Employees` & `Active Employees` counts
   * `Attrition Rate (%)` calculations
   * `Average Tenure` running values
3. **Report Presentation & UI/UX:** Built a responsive, multi-page layout grid following modern business intelligence interface standards. Utilized native components like conditional formatting, visual-level filters, and custom tooltips to maximize analytical scannability.

---
*Developed as a standalone Power BI demonstration for a professional Data Analytics portfolio. Feedback and performance-tuning recommendations are always welcome!*
