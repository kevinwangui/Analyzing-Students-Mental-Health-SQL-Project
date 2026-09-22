# Analyzing Students' Mental Health (SQL Project)

## 📌 Project Overview
This project investigates whether studying abroad in a foreign country impacts mental health and evaluates whether a student's length of stay is a primary contributing factor. Using PostgreSQL, this analysis extracts and aggregates diagnostic survey results from international students.

## 📊 Key Diagnostics Analyzed
* **PHQ-9 (`todep`):** Total score measuring depression levels.
* **SCS (`tosc`):** Total score measuring social connectedness and belonging.
* **ASISS (`toas`):** Total score measuring acculturative stress.

## 🛠️ Key Queries & Operations
* Filtered data specifically for international student cohorts (`inter_dom = 'Inter'`).
* Calculated rounded average test scores (`average_phq`, `average_scs`, `average_as`) across varying lengths of stay (`stay`).
* Grouped and ordered the resulting data in descending order by length of stay to observe trends over time.

## 💻 Tech Stack
* **Database:** PostgreSQL
* **Tools:** DataLab / SQL Workspace
