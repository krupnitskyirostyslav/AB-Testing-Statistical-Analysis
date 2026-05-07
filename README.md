# AB-Testing-Statistical-Analysis

Portfolio Project

Tools: Python · SQL · BigQuery · Tableau

## [Tableau Dashboard](https://public.tableau.com/views/ABtestwithstatisticalsignificance/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Project Overview
This project analyzes A/B test results using Python to calculate statistical significance and visualize conversion metrics. It demonstrates practical experimentation analysis — from data extraction to hypothesis testing and dashboard creation.

## 1. Data Preparation (SQL + BigQuery)
- Joined session, event, and account tables from the DA dataset
- Aggregated metrics by test, country, device, continent, and channel

## 2. Statistical Analysis (Python)
- Calculated conversion rates for four key metrics:

add_payment_info/session, add_shipping_info/session, begin_checkout/session, new_account/session
- Automated significance testing using z‑tests for proportions
- Computed lift %, z‑statistic, and p‑value for each metric

## 3. Visualization (Tableau)
- Built an interactive dashboard showing conversion differences and significance
- Added filters by test number and visual indicators for statistically significant results

## Key Skills Demonstrated
Python: Pandas, NumPy, StatsModels, automation with loops

SQL: data extraction and aggregation in BigQuery

Statistics: hypothesis testing, z‑test, p‑value interpretation

Visualization: Tableau dashboards for experiment insights
