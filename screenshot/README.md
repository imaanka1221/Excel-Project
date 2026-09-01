Electricity Consumption Data Analysis – Excel Dashboard

📊 Project Overview

This project analyzes electricity consumption and customer data using Microsoft Excel.
The analysis focuses on data quality, electricity consumption by area, revenue, customer type, payment status, and monthly reading dates.

The workbook includes:

Data quality / blank-value analysis

Area-level analysis

Units consumed (kWh) analysis

Tariff analysis

Revenue analysis

Customer type analysis

Payment status analysis

Interactive Excel dashboard

Pivot tables, charts, and slicers

🧹 Data Quality Analysis

The analysis sheet identifies blank or missing values in important columns:

Field

Blank Records

Meter ID

15

Reading Date

15

Customer Type

15

Units_kWh

16

Tariff_per_kWh

16

Payment Status

16

Area

15

Total

108

This helps identify missing information before performing the main analysis.

Data Quality Screenshot



📍 Area Analysis

The dataset contains electricity customers across several areas:

Baidoa

Bosaso

Garowe

Hargeisa

Kismayo

Mogadishu

Blank / missing area records

The analysis compares the number of records and electricity consumption across these areas.

⚡ Electricity Consumption Analysis

Units consumed are analyzed by area to understand which locations have higher electricity consumption.

From the analysis:

Area

Units (kWh)

Baidoa

30,969.4

Bosaso

29,487.6

Garowe

39,842.1

Hargeisa

51,167.7

Kismayo

26,954.0

Mogadishu

100,110.4

Blank

13,910.5

Total

292,441.7

Mogadishu has the highest recorded electricity consumption in the displayed analysis.

💰 Revenue Analysis

Revenue is compared across areas to identify the areas generating the highest revenue.

The dashboard also provides an overall revenue KPI and an average revenue per customer.

👥 Customer Type Analysis

The dashboard analyzes customers by type, including:

Commercial

Industrial

Residential

Non-customer

Unknown

Blank

The displayed customer counts include:

Customer Type

Records

Commercial

75

Industrial

20

Unknown

2

Blank

16

Other customer categories

Included in dashboard

💳 Payment Status Analysis

Payment status is analyzed using the following categories:

Paid

Pending

Overdue

Non-pay

Blank

The dashboard uses a doughnut chart to make the payment distribution easier to understand.

📈 Dashboard

The final Excel dashboard provides an interactive summary of the electricity consumption data.

Main Dashboard



Dashboard Features

The dashboard contains:

Total Consumption / Consumption KPI

Total Revenue

Average Consumption

Number of Customers / Meters

Paid Customers

Pending Customers

Payment Rate

Average Revenue per Customer

Consumption by Area chart

Revenue by Area chart

Customer Type chart

Payment Status chart

Reading Date chart

Interactive slicers for:

Area

Customer Type

Payment Status

Reading Date

🛠️ Tools Used

Microsoft Excel

Pivot Tables

Pivot Charts

Slicers

Excel formulas

Data cleaning and quality checks

Dashboard design

🎯 Project Objectives

The main objectives of this project are to:

Inspect the quality of the electricity consumption dataset.

Identify blank and missing records.

Analyze electricity consumption by area.

Compare revenue across different areas.

Understand customer types.

Analyze payment status.

Calculate useful KPIs.

Build an interactive Excel dashboard.

Present the results in a clear and understandable way.

📌 Key Insights

Mogadishu records the highest electricity consumption among the listed areas.

The dataset contains 108 blank/missing field entries across the inspected columns.

Customer information includes commercial, industrial, residential, non-customer, unknown, and blank categories.

Payment status can be monitored through the dashboard to distinguish paid, pending, overdue, and non-paying records.

Slicers allow the dashboard to be filtered interactively by area, customer type, payment status, and reading date.

📁 Project Structure

Electricity-Consumption-Analysis/
│
├── README.md
├── analysis.png
└── dashboard.png

👨‍💻 Project Type

Excel Data Analytics Project – Electricity Consumption Analysis
