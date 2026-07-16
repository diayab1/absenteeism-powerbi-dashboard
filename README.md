# absenteeism-powerbi-dashboard
Power BI dashboard analyzing employee absenteeism patterns and risk factors using the UCI Absenteeism at Work dataset
# Employee Absenteeism Analytics Dashboard

A Power BI dashboard analyzing workplace absenteeism patterns using the [UCI Absenteeism at Work dataset](https://archive.ics.uci.edu/dataset/445/absenteeism+at+work) — 740 records from a courier company, covering absence reasons, employee demographics, health indicators, and work conditions.

## Business Problem

Unplanned absenteeism drives up labor costs and disrupts operations. This dashboard was built to help HR and operations teams identify **who** is at risk of high absenteeism, **why** it's happening, and **when** it spikes — so interventions can be targeted rather than reactive.

## Dashboard Pages

- **Executive Dashboard** — top-line KPIs (total absence hours, average per employee, disciplinary failure rate), absence trends over time, and breakdown by reason and season
- **Risk Analysis** — scatter analysis of absenteeism drivers (workload, distance to work, BMI) against absence hours, with risk scoring by employee segment
- **Temporal Analysis** — absence patterns by month, day of week, and season via pivot tables and trend lines
- **Alerts & Flags** — a treemap and flagging table surfacing employees exceeding absence thresholds, with interactive drill-through
- **Behavioral Analysis** — absenteeism cut by lifestyle factors (social drinking/smoking, dependents, education level)
- **Performance Analysis** — workload and hit-target performance vs. absenteeism, with advanced filtering by employee attributes

## Key Variables Analyzed

Reason for absence, transportation expense, distance from residence to work, service time, age, workload average/day, disciplinary failure, education, dependents, social drinking/smoking, BMI, and absenteeism hours.

## Tools

Power BI (data modeling, DAX measures, custom Risk Heatmap visual)

## Files

- `absenteeism-dashboard.pbix` — full Power BI file (open in Power BI Desktop)
- `/screenshots` — page-by-page dashboard exports
- `Absenteeism_at_work.csv` — source dataset

---
*Academic project, Seattle Pacific University*
