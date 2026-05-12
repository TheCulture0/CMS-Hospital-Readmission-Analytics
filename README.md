# CMS-Hospital-Readmission-Analytics
End-to-end Power BI dashboard analyzing the correlation between HCAHPS patient experience scores and CMS readmission penalties (FY 2026)

# CMS Hospital Readmission & Quality Analytics (FY 2026)

## Project Overview
This project investigates the correlation between patient experience and clinical readmission penalties using CMS FY 2026 datasets. The analysis identifies that **66.38% of hospitals are currently penalized**, and highlights a **7% performance advantage** for high-service facilities.

## Key Performance Indicators
* **Excess Readmission Ratio (ERR):** Measures if a hospital's readmissions are above (penalty) or below (success) the national average (1.0).
* **Readmission Impact Ratio (0.93):** Proves that 5-star rated hospitals have a 7% lower readmission risk than 1-star hospitals.

## Features
* **National Penalty Heatmap:** Identifies geographic hotspots for HRRP penalties.
* **Service-Outcome Correlation:** A dynamic toggle to compare metrics like 'Discharge Information' vs. 'Nurse Communication'.
* **State Leaderboards:** Identifies top and bottom performers via dynamic Top-N filtering.

## Technical Stack
* **Power BI & Power Query:** Data cleaning and multi-table modeling.
* **DAX:** Advanced measures including Field Parameters and error-handled ratios.
* **Geospatial Mapping:** Custom location logic for accurate US plotting.

## How to Access
1. Download `CMS_Hospital_Analytics.pbix`.
2. Open with Power BI Desktop.
