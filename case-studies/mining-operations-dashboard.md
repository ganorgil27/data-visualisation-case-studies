# Mining operations dashboard

## Purpose

This personal project was created to practise organising data in Snowflake and presenting it in a Power BI dashboard using a mining operations scenario.

> **Synthetic data:** I generated the dataset with AI. Every figure shown is synthetic and does not describe or represent a real mine, company or mining operation.

## Data source

The dashboard uses a synthetic dataset that I generated with AI. The reporting data used by the dashboard comes from Snowflake.

No real operational or company data is used or included.

## What I built

I created the synthetic dataset, built the bronze, silver and gold data layers in Snowflake, and built the Power BI dashboard.

In plain language, the data flow is:

1. **Bronze:** holds the data in its initial form.
2. **Silver:** represents cleaned or prepared data.
3. **Gold:** provides data arranged for reporting and dashboard use.

This description stays at a high level because the Snowflake SQL and architecture documentation are not currently included. They may be considered for a later update after the actual files have been reviewed.

## What the screenshot shows

The overview page displays the following synthetic figures:

- 34.23M total tonnes
- 74.10 average utilisation percentage
- 103.40K total operating hours
- 65 overdue work orders
- 0.34 fuel per tonne
- total tonnes by month
- average utilisation by equipment type

These are values displayed in the screenshot. Their calculations cannot be reviewed from the screenshot alone.

<img src="../images/mining-operations-overview.jpg" alt="Synthetic mining operations dashboard showing 34.23 million total tonnes, average utilisation, operating hours, overdue work orders, fuel per tonne, monthly tonnes and equipment utilisation" width="1100">

*Power BI overview built with synthetic mining operations data from Snowflake. The figures do not represent a real operation.*

## Limitations

- The dataset and every displayed figure are synthetic.
- The dashboard is a personal project, not professional client work or a production report.
- Only a static screenshot is available, so interactions and filters cannot be demonstrated.
- The original Power BI file is not included.
- Snowflake SQL, architecture documentation and the underlying dataset are not currently included.
- No claims are made about performance, business outcomes, orchestration or particular transformations.

## Files available

- [`mining-operations-overview.jpg`](../images/mining-operations-overview.jpg) — screenshot of the dashboard overview
- This case-study page

[Return to the main README](../README.md)
