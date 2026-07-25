# 📊 IT Expenditure Analysis & Dashboard (Power BI)

A comprehensive Power BI reporting solution designed to analyze and evaluate corporate IT expenditure. This project tracks planned budgets, dynamic forecasts, and actual costs across multiple business units, regions, and granular cost elements to provide key variance insights.

---

## 📌 Project Overview

Managing and optimizing large-scale IT budgets requires real-time visibility into cost drivers and variance trends. This dashboard delivers an interactive end-to-end financial breakdown to help stakeholders identify overspending, monitor regional allocations, and perform root-cause analysis on budget deviations.

---

## Key Metrics & Insights

* **Overall Budget Execution:** Total Actual Expenses (**$866.41M**) remained within the Planned Expense budget (**$900.40M**) and under Forecasted Expenses (**$890.54M**).
* **Expense Trends:** Actual spending peaked significantly in **January** and **December**, exceeding monthly forecasted targets during these periods.
* **Business Area Performance:** While overall variance sits favorably at **+$33.99M**, the **Infrastructure** unit experienced budget overruns with a negative plan variance of **-$5.57M**.
* **Geographical Insights:** The **United Kingdom** (~30%) and **France** represent the largest expenditure footprints. **Germany (-$30.79M)** and the **UK (-$28.23M)** recorded the highest negative plan variances.
* **Cost Drivers:** Root cause breakdown via dynamic decomposition reveals that **Computer Hardware**, **Software Maintenance**, and **Telephone/Telecom** expenses primary drive negative variances within Infrastructure.

---

## 🛠️ Tools & Technologies Used

* **Business Intelligence:** Power BI Desktop
* **Data Transformation:** Power Query (ETL)
* **Data Modeling & Calculations:** DAX (Data Analysis Expressions) for dynamic KPIs, cumulative totals, and plan/forecast variances
* **Visualizations:** KPI Cards, Line Charts, Pie/Donut Charts, Bar Charts, Decomposition Trees

---

## 📖 Dashboard Structure

The Power BI report is organized into four interactive pages:

1. **Study of Planned, Forecasted, and Actual Expenses**
   * Overview KPI Cards for Actuals, Forecasts, and Planned Expenditures.
   * Monthly trend and cumulative financial trajectories throughout the fiscal year.

2. **Expenses and Business Area**
   * High-level plan variance KPIs and distribution by business units (BU, R&D, Infrastructure, Manufacturing, etc.).
   * Monthly cumulative plan variance tracking per business segment.

3. **Region-wise Distribution of Expenses**
   * Country-level expense contribution pie charts for Planned vs. Actual spending.
   * Country-by-country breakdown of Plan Variance in visual bar charts and structured tables.

4. **Decomposition of Expenses**
   * Interactive **Decomposition Tree** enabling drill-downs from IT Area $\rightarrow$ Country $\rightarrow$ Cost Element.
   * Detailed breakdown of specific cost elements (e.g., Salaries, Hardware, Software, Telecom).

---

## 🚀 How to View / Run the Project

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/it-expenditure-analysis.git](https://github.com/your-username/it-expenditure-analysis.git)
