# MN8 Energy Style Portfolio Analytics Project

A portfolio project tailored to the **MN8 Energy Data Analytics Intern** posting.

This project simulates how an EPMO or enterprise analytics team could use project, schedule, risk, engineering, and financial data to support **data-driven decisions across solar PV and battery storage programs**.

> **Important:** the datasets in this repo are synthetic

## Project goals

- Collect, validate, and analyze project, engineering, and financial data
- Build dashboard-style reporting for portfolio visibility
- Support schedule, risk, and budget analytics
- Perform root-cause analysis on project issues
- Translate technical project data into business-facing insights

## Tools used

- Python
- pandas
- matplotlib
- Jupyter Notebook
- Excel dashboard
- Git/GitHub

## Dataset overview

The project includes three synthetic datasets:

1. **project_portfolio.csv**  
   Portfolio-level project data for solar, battery storage, and hybrid projects.

2. **monthly_progress.csv**  
   Monthly progress, CAPEX, performance ratio, safety incident, and change-order data.

3. **issue_log.csv**  
   Issue tracking data for root-cause analysis, severity, impact days, and impact cost.

## Business questions answered

- Which projects are most at risk based on schedule variance, budget performance, and risk score?
- Which root causes drive the most delay across the portfolio?
- How is portfolio capacity distributed across solar, battery, and hybrid assets?
- Which projects need escalation in governance or recovery planning?
- How can dashboard reporting support portfolio management conversations?

## Headline results

- Total modeled portfolio capacity: **3,428 MW**
- Projects flagged **At Risk**: **2**
- Average schedule variance: **4.3 days**
- Top delay drivers:
- Supply chain: 222 impact days
- Weather: 219 impact days
- Design revision: 153 impact days

## project description

Built a renewable energy portfolio analytics project using Python, Excel, and synthetic solar and battery storage data to analyze schedule variance, budget performance, issue root causes, and PMO-style KPIs; created dashboards and business recommendations to support enterprise project reporting.
ilters by region, project stage, and technology
- Build a project risk scoring model
- Simulate telemetry or SCADA-style operational data for a more technical energy use case
