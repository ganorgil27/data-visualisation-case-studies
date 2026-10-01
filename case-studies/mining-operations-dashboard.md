# Mining operations dashboard

## Project overview

This personal project demonstrates how mining operations data can be prepared in Snowflake and presented in Power BI. The goal was to create a clear view of production, equipment performance, maintenance and fuel efficiency.

The dataset and all figures shown are synthetic. They do not represent a real mine or company.

## What I built

I generated the synthetic dataset, organised it into three layers in Snowflake and built the Power BI dashboard.

The data follows this workflow:

1. **Bronze:** stores the data in its initial form.
2. **Silver:** contains cleaned and prepared data.
3. **Gold:** provides reporting-ready data for the dashboard.

## Dashboard highlights

The dashboard shows:

- 34.23M total tonnes
- 74.10% average equipment utilisation
- 103.40K total operating hours
- 65 overdue work orders
- 0.34 fuel per tonne
- monthly tonnes and utilisation by equipment type

<img src="../images/mining-operations-overview.jpg" alt="Synthetic mining operations dashboard showing 34.23 million total tonnes, average utilisation, operating hours, overdue work orders, fuel per tonne, monthly tonnes and equipment utilisation" width="1100">

*Power BI dashboard built with synthetic mining operations data prepared in Snowflake.*

[Back to both projects](../README.md)
