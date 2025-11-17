Air Pollution Data Cleaning and Exploratory Analysis for Simulated Sickle Cell Disease Study

📘 Project Overview

This project supports an epidemiologic study investigating whether exposure to air pollution is associated with vaso-occlusive pain and health care utilization among individuals with sickle cell disease (SCD) in Durham County, North Carolina.

SCD is a genetic blood disorder that causes red blood cells to assume a sickle shape, leading to anemia, pain crises, infection, and stroke. Prior research suggests that air pollution may exacerbate vaso-occlusion and pain episodes. To explore this relationship, this project processes simulated pollutant measurements and performs exploratory data analysis (EDA).

🧹 Data Cleaning Function

A custom R function was written to clean and preprocess raw EPA air pollution data. The function performs:

Conversion of date fields into usable formats

Standardization of pollutant variable names

Averaging of values within each day

Removal of duplicated or irrelevant fields

Creation of a clean, analysis-ready dataset

This function ensures that raw monitoring data—often messy and inconsistently formatted—is transformed into a consistent structure suitable for downstream epidemiologic analysis.

📊 Exploratory Data Analysis

Two primary visualizations were created to understand pollutant patterns over time:

1. Monthly CO and O₃ Levels

A plot comparing carbon monoxide (CO) and ozone (O₃) concentrations by month.
This visualization helps identify shared seasonal trends, peak pollution periods, and potential correlations between the two pollutants.

2. PM2.5 Concentrations by Month and Year

A plot showing fine particulate matter (PM2.5) concentrations stratified by month and year.
Year-level color coding allows for examination of seasonal patterns as well as comparisons across years, highlighting possible long-term changes or anomalies in particulate pollution.

🧭 Purpose of the Analysis

These plots and the cleaning function serve as the foundation for upcoming work to:

Merge exposure data with SCD health system utilization records

Investigate pollutant–health associations

This EDA establishes baseline understanding of pollutant behavior and ensures data quality before conducting more advanced analyses.
