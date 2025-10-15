# VAERS-Safety-Dashboard-Analysis
Power BI dashboard for regulatory compliance and risk analysis on vaccine adverse events
# VAERS Safety Report: Regulatory & Risk Analysis Dashboard

## Project Overview & Business Value

This project analyzes raw VAERS (Vaccine Adverse Event Reporting System) data to create a two-page Business Intelligence dashboard in Power BI. The goal is to monitor **regulatory compliance** (timeliness) and proactively identify **high-risk signals** and geographic outliers in adverse event reporting.

***

## Page 1: Executive Safety Summary

This page provides the high-level metrics required for executive decision-making.

![Screenshot of Page 1: Executive Safety Summary](Page1.%20Executive%20Safety%20Summary.png)

### Key Analytical Takeaways

* **Compliance Risk:** The **Compliance Rate Gauge** shows performance at **62.06%** against a 95.00% target, identifying an immediate and severe regulatory gap.
* **Trend Analysis:** The **Monthly Report Volume** line chart confirms the compliance issue by showing a steep drop-off in reporting after the initial months, indicating a reporting lag or process failure.
* **Data Governance:** The 'Raw Sum of Reporting Days' KPI is intentionally flagged, demonstrating awareness of a **data quality issue** in the source data.

***

## Page 2: Regulatory & Geographic Risk Analysis

This page focuses on critical outcomes and geographic distribution to guide risk management and regulatory follow-up.

![Screenshot of Page 2: Regulatory & Geographic](Page%202.%20Regulatory%20and%20geographical%20Risk%20Analysis.png)

### Key Analytical Takeaways

* **Risk Prioritization:** The **Fatality Rate by State** chart is the primary risk driver, showing states with the highest percentage of severe outcomes relative to their report volume.
* **Severity Distribution:** The **Proportional Breakdown of Report Severity** uses a 100% Stacked Bar Chart to categorize outcomes, revealing the overall mix of reports (Fatalities, Disabled, Hospitalized, Non-Severe) for risk allocation.
* **Interactivity:** The use of the **Vaccine Slicer** and the **Geographic Map** allows a manager to filter the entire risk profile down to a single product for root cause investigation.

***

