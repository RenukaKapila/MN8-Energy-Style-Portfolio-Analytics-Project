# MN8 Energy Style Portfolio Analytics Project

A portfolio project tailored to the **MN8 Energy Data Analytics Intern** posting.

This project simulates how an EPMO or enterprise analytics team could use project, schedule, risk, engineering, and financial data to support **data-driven decisions across solar PV and battery storage programs**.

> **Important:** the datasets in this repo are synthetic and were created for portfolio demonstration only.

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

## Folder structure

```text
mn8_energy_portfolio_analytics_project/
├── README.md
├── data/
│   ├── raw/
│   └── clean/
├── notebooks/
├── scripts/
├── visuals/
├── dashboard/
└── docs/
```

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

## Files worth highlighting in interviews

- `notebooks/mn8_portfolio_analytics.ipynb` for exploratory analysis
- `scripts/analysis.py` for repeatable analysis and chart generation
- `dashboard/mn8_portfolio_dashboard.xlsx` for PMO-style dashboard reporting
- `docs/key_findings.md` for executive summary style findings

## Resume-ready project description

Built a renewable energy portfolio analytics project using Python, Excel, and synthetic solar and battery storage data to analyze schedule variance, budget performance, issue root causes, and PMO-style KPIs; created dashboards and business recommendations to support enterprise project reporting.

## How this maps to the MN8 role

This project was designed to mirror the internship's focus on:

- project performance analytics
- engineering and financial data analysis
- dashboard reporting
- root-cause investigations
- cross-functional business communication
- process and governance support

## Next improvements

- Add Power BI or Tableau version of the dashboard
- Add KPI filters by region, project stage, and technology
- Build a project risk scoring model
- Simulate telemetry or SCADA-style operational data for a more technical energy use case
