# Power BI Data Cleaning and M Language in Power Query

This repository contains two Power BI Power Query implementations:

-  **Cleaning and Transforming Dirty Table Data** – A structured approach to converting messy Excel input into a clean, analysis-ready format.
-  **Custom Date Dimension Table using M Language** – A dynamic date table generator with rich time-based attributes for reporting and time intelligence.


## Cleaning Dirty Table: Key Steps

- Connected to Excel source
- Transposed table to flip rows to columns
- Promoted first row as headers
- Filled down missing values
- Unpivoted columns
- Extracted text and renamed columns
- Corrected data types

**Outcome**: A normalized and clean table structure ready for visual reporting.


## Custom Date Table using M Language

- Auto-generates dates from `2024-01-01` to `2025-05-01`
- Includes columns like:
  - Full weekday name
  - Weekday number
  - Year, Quarter, Month, Short Month
  - Is Weekend flag
  - Start of month
  - Day of year, Week of year

**Uses**: Time intelligence in Power BI dashboards.


