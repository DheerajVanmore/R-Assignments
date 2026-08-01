# Air Quality Data Cleaning – R Assignment 1

**Dataset:** Beijing Multi-Site Air Quality Data (UCI ML Repository) — Aotizhongxin station

## Files
- `air_quality_cleaning.R` – full R script covering all 10 tasks
- `cleaned_air_quality_data.csv` – cleaned dataset after missing-value imputation
- `missing_values_chart.png` – bar chart of missing values before vs after cleaning

## Summary
Handled missing values across PM2.5, PM10, SO2, NO2, TEMP, WSPM (numeric,
median imputation) and wd (categorical, mode imputation) using loops,
user-defined functions, and tryCatch()-based error handling. All selected
variables had 0 missing values after cleaning.
