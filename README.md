

# Patient Waiting List Analysis & Dashboard (Power BI)

## Project Overview

Healthcare waiting lists directly affect patient outcomes, operational efficiency, and resource planning.
This project focuses on analyzing patient waiting list data to uncover trends, bottlenecks, and disparities across case types, age groups, specialties, and time bands, and then translating those insights into an interactive Power BI dashboard for decision-makers.

The goal is twofold:

1. Perform structured exploratory data analysis (EDA) to understand the drivers of waiting times.
2. Design an executive-ready dashboard that communicates insights clearly to both technical and non-technical stakeholders.

---

## Dataset Description

The dataset contains historical records of patient waiting lists with attributes including:

* Archive date
* Case type (Outpatient, Day Case, Inpatient)
* Specialty
* Age profile
* Time bands (waiting duration buckets)
* Waiting list counts

The data spans multiple years, allowing for trend analysis and year-over-year comparison.

---

## Exploratory Data Analysis (EDA)

### 1. Data Understanding & Cleaning

The initial phase involved:

* Inspecting data structure, data types, and completeness
* Handling missing values and inconsistent category labels
* Standardizing date fields to support time-series analysis
* Validating numeric fields to ensure accurate aggregations

This step ensured that all subsequent analysis was built on reliable and consistent data.

---

### 2. Univariate Analysis

Single-variable analysis was performed to understand distribution patterns:

* Total waiting list volume across years
* Distribution of patients by case type
* Specialty-level contribution to overall waiting lists
* Waiting time distribution across predefined time bands

This helped identify dominant categories and outliers early in the analysis.

---

### 3. Bivariate & Multivariate Analysis

To uncover relationships between variables, the analysis explored:

* Case type vs waiting time bands
* Age profile vs waiting duration
* Specialty vs average and median waiting list size
* Time trends segmented by patient type (inpatient, outpatient, day case)

These comparisons revealed how different patient groups experience waiting times differently and where pressure points exist in the system.

---

### 4. Average vs Median Analysis

Both **average** and **median** waiting list metrics were calculated and compared:

* The average highlighted overall workload pressure.
* The median reduced the influence of extreme values and better represented the typical patient experience.

A dynamic toggle was implemented to allow users to switch between these measures seamlessly in the dashboard.

---

## Dashboard Design Process

### 1. Stakeholder-Focused Design

The dashboard was designed with two primary audiences in mind:

* **Executives:** high-level KPIs, trends, and summaries
* **Operational users:** detailed breakdowns by specialty, case type, age group, and time band

This led to a two-page structure:

* **Executive Summary**
* **Detailed View**

---

### 2. Executive Summary Page

<img width="1333" height="745" alt="Screenshot 2025-12-15 162841" src="https://github.com/user-attachments/assets/3574367b-4fec-4e52-adee-1184f7f1cfcc" />

The Executive Summary provides an at-a-glance view of system performance:

* KPI cards showing current and prior-year waiting list volumes
* Trend analysis for inpatient, outpatient, and day case waiting lists
* Distribution of waiting lists by case type
* Top specialties contributing to the waiting list
* Age profile vs time band analysis to highlight vulnerable groups

The focus here is fast insight and decision support.

---

### 3. Detailed View Page

<img width="1325" height="751" alt="image" src="https://github.com/user-attachments/assets/b8d9e4aa-152e-4ac6-a734-ebe75e5eeef8" />

The Detailed View enables deeper exploration:

* Interactive slicers for age profile, case type, time bands, and date range
* Dynamic switching between average and median metrics
* Flexible filtering to investigate specific patient cohorts or specialties

This page supports root-cause analysis and operational planning.

---

### 4. Interactivity & Usability

Key design considerations included:

* Consistent color coding across visuals
* Minimal clutter with clear labeling
* Slicer synchronization across pages
* Use of dynamic DAX measures to maintain consistency across visuals

The result is a dashboard that is intuitive, responsive, and suitable for real-world decision-making.

---

## Tools & Technologies

* **Power BI** – Data modeling, DAX, and dashboard development
* **DAX** – Dynamic measures, KPIs, and toggle logic
* **Power Query** – Data cleaning and transformation

---

## Key Insights

* Outpatients account for the largest proportion of the waiting list.
* Certain specialties consistently contribute disproportionately to long waits.
* Median waiting values reveal a different patient experience than averages, highlighting the importance of robust metrics.
* Waiting times vary significantly across age groups and time bands, indicating areas for targeted intervention.

---

## Conclusion

This project demonstrates how structured exploratory data analysis combined with thoughtful dashboard design can turn raw healthcare data into actionable insights.
By balancing analytical depth with clear visual communication, the dashboard supports both strategic decision-making and operational improvement.

---

## Author

**Chukwuebuka Enoch**
Data Analyst | Power BI | Healthcare Analytics

---

If you want, next I can:

* Shorten this into a **recruiter-optimized README**
* Add **screenshots placement guidance**
* Rewrite it to align with a **specific job role (Data Analyst / BI Analyst)**
