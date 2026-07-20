# HR Analytics Dashboard 📊

A Power BI dashboard analyzing employee attrition trends across departments, roles, and demographics.

![HR Analytics Dashboard](HR-Analytics-Dashboard/Hrdashboard.png)

---

## Overview

This dashboard helps HR teams understand *why* and *where* employee attrition is happening — by role, education field, age group, salary slab, and tenure — to support retention strategy decisions.

## Key Visuals

- **KPI Cards** — Count of Employees, Attrition, Attrition Rate, Average Age, Average Salary, Years at Company
- **Sum of Attrition by Gender** — Female vs. Male comparison cards
- **Sum of Education by Attrition** — Donut chart
- **Attrition by Job Role** — Interactive table + bar chart (Laboratory Technician, Sales Executive, Research Scientist, etc.)
- **Attrition by Education Field** — Human Resources, Life Sciences, Marketing
- **Attrition by Age Group** — Bar chart across age bands (18–55+)
- **Attrition by Salary Slab** — Upto 5k, 5k–10k, 10k–15k, 15k+
- **Attrition by Years at Company** — Trend/area chart showing attrition spikes by tenure

## Insights Covered

- Overall organizational attrition rate
- Job roles and departments with highest attrition
- Attrition trends by tenure, age group, and salary band
- Gender-wise and education-wise attrition split

## Dataset

- `HR_Analytics.xlsx` — Employee dataset (fields include Department, JobRole, EducationField, SalarySlab, YearsAtCompany, AgeGroup, Attrition, etc.)

> **Note:** If this dataset was originally sourced from a public repository (e.g., Kaggle), please retain attribution to the original source. The license in this repo applies to the dashboard file, DAX code, and documentation — not necessarily to the raw dataset, which may carry its own license terms.

## Tools Used

- **Power BI Desktop** — Data modeling, DAX measures, dashboard design
- **Excel** — Source dataset

## How to Use

1. Clone or download this repository
2. Open the `.pbix` file in Power BI Desktop
3. If prompted, update the data source path to point to `HR_Analytics.xlsx` on your machine
4. Explore the interactive visuals and filters

## License

This project is licensed under the [MIT License](LICENSE) — feel free to use, modify, and share with attribution.

## Author

Built by Ram as part of Power BI dashboard practice/portfolio work.
