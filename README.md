# Power-BI-Commercial-Flight-Dashboard

# Summary

An interactive Power BI dashboard analyzing roughly 2 million commercial flight records. It summarizes flight activity and shows delay and cancellation patterns across months, cities, airlines, and cancellation categories.

# Business Questions Answered
Which airlines and cities have the highest delay rates?
How do flight volume, delays, and cancellations change month to month?
Why are flights canceled, and on which days of the week do cancellations cluster?
Key Findings
United Airlines had the highest delay rate among airlines at 53%, with about 139K delayed flights.
Houston, TX had the highest delay rate among cities at 42%, with about 61K delayed flights.


# Dashboard Features
**KPI cards**: total flights, delayed flights, canceled flights

**Monthly trends**: total flights, delays, and cancellations over time

**City analysis**: flight volume by city

**Airline analysis**: delay rate by airline

**Cancellation analysis**: breakdown by cancellation description and day of week

**Flight status**: share of on-time, delayed, and canceled flights

# Data Preparation

Used Power Query to clean and transform the source data and keep only the relevant columns.

Created a conditional column classifying each flight as on-time, delayed, or canceled.
Built data relationships and DAX measures to support the KPI cards and visuals.
Tools

Microsoft Power BI, Power Query, data modeling, DAX measures, data visualization

# Files
Flight_Performance_Dashboard.pbix: Power BI dashboard file

dashboard-screenshot.png: dashboard preview

# Notes
Built for portfolio and educational purposes. Findings apply to the source dataset and should be interpreted in that context.
