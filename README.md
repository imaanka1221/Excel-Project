# Excel-Project

# Electricity Consumption Data Analysis (Excel)

## Overview
This workbook contains a raw and cleaned dataset of electricity meter readings, along with pivot tables and a dashboard used to analyze consumption, revenue, and payment behavior across several regions.

## Sheets

| Sheet | Description |
|---|---|
| `Project_Index` | An index of 24 student projects (this workbook covers project #6: Electricity Consumption). |
| `06_Electricity` | Raw dataset (300 rows, 7 columns) — includes intentional blank cells for data-cleaning practice. |
| `Data_clean` | Cleaned version of the dataset (300 rows, 8 columns) with a calculated `Total Revenue` column added. |
| `PivotAreaByRevenue` | Pivot table: total units consumed and revenue by area. |
| `PovitCustomerType` | Pivot table: total revenue and units by customer type. |
| `PovitPayment` | Pivot table: revenue and record count by payment status. |
| `PivotReading_date` | Pivot table: total units consumed by month. |
| `PovitConsumptionbyArea` | Pivot table: total units consumed by area. |
| `Dashboard` | Summary dashboard for the electricity consumption analysis. |
| `Analysis` | Notes on data quality issues (blanks, category inconsistencies, etc.). |
| `pivot table` | Combined pivot summary by area (units and revenue, cleaned vs. raw). |

## Data Dictionary (`Data_clean`)

| Column | Type | Description |
|---|---|---|
| `Meter_ID` | Text | Unique electricity meter identifier (e.g., `MTR0003`). |
| `Reading_Date` | Date | Date of the meter reading (range: Jan 2025 – Aug 2026). |
| `Area` | Text | City/region of the meter (Mogadishu, Baidoa, Kismayo, Bosaso, Garowe, Hargeisa). |
| `Customer_Type` | Text | Commercial, Industrial, or Residential. |
| `Units_kWh` | Number | Electricity consumed, in kilowatt-hours. |
| `Tariff_per_kWh` | Number | Price charged per kWh. |
| `Payment_Status` | Text | Paid, Pending, or Overdue. |
| `Total Revenue` | Number | Calculated as `Units_kWh × Tariff_per_kWh`. |

## Known Data Quality Issues
The raw and cleaned sheets intentionally contain messy data for cleaning practice:
- **Missing values**: blank cells in `06_Electricity` (and some in `Data_clean`).
- **Inconsistent text casing**: e.g., `Paid` vs. `paid`, `Overdue` vs. `OVERDUE`, `Pending` vs. `pending`.
- **Placeholder/invalid categories**: `non_area` (invalid area), `non_customer` (invalid customer type), `non_pay` (invalid payment status).
- **Zero values**: some rows have `Units_kWh = 0` or `Tariff_per_kWh = 0`, resulting in `Total Revenue = 0`.

## Suggested Uses
- Practice data cleaning (standardizing categories, handling blanks/placeholders).
- Analyze consumption and revenue trends by area, customer type, month, and payment status.
- Build or refine dashboards/pivot tables summarizing the above.

## File
- `electricity_consumption1.xlsx`
