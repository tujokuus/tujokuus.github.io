---
layout: default
---

## Portfolio

A selection of my work in data engineering, analytics, and machine learning.

---

### Experience

### Cense Analytics - Machine Learning & Data Science Intern

Worked on building and maintaining data pipelines and machine learning solutions in a Databricks environment using Python, SQL, and Apache Spark. Focused on data quality and reliability by identifying inconsistencies, tracing root causes, and improving data structures for downstream use. Built image-based machine learning solutions end-to-end, including data preprocessing, feature engineering, model development, and validation, achieving strong results (details confidential).

---

### Projects

#### Air Strikes on Ukraine Analysis Dashboard

[![Open Dashboard](https://img.shields.io/badge/Streamlit-Open%20Dashboard-ff4b4b?logo=streamlit&logoColor=white)](https://strikes-on-ukraine-analysis.streamlit.app/)
[![View on GitHub](https://img.shields.io/badge/GitHub-View%20on%20GitHub-24292e?logo=github&logoColor=white)](https://github.com/tujokuus/air-strikes-on-ukraine-dashboard)

In this MVP-stage project, I developed an end-to-end data analytics solution for exploring reported missile and UAV strike activity in Ukraine. The project combines data analysis, data engineering, and dashboard development: I collected and processed raw CSV data in Python with pandas, cleaned and standardized key fields such as dates, weapon references, and target areas, and transformed the data into a bronze, silver, and gold architecture. I then used DuckDB and SQL to build analytics-ready marts and views, and created an interactive Streamlit dashboard with Plotly and PyDeck to visualize trends over time, weapon activity, regional patterns, and air defense success rates.

<div style="display:flex; flex-wrap:wrap; gap:16px; margin-top:16px;">
  <div style="flex:1 1 320px;">
    <img src="images/Screenshot_overview1_b.png" alt="Dashboard overview" />
    <p style="font-size:12px; margin-top:6px; text-align:center;">Dashboard overview</p>
  </div>
  <div style="flex:1 1 320px;">
    <img src="images/Screenshot_interactivemap1b.png" alt="Interactive map view" />
    <p style="font-size:12px; margin-top:6px; text-align:center;">Interactive map and regional analysis</p>
  </div>
</div>

<div style="display:flex; flex-wrap:wrap; gap:16px; margin-top:8px;">
  <div style="flex:1 1 320px;">
    <img src="images/Screenshot_weapons1b.png" alt="Weapon activity analysis" />
    <p style="font-size:12px; margin-top:6px; text-align:center;">Weapon activity analysis</p>
  </div>
  <div style="flex:1 1 320px;">
    <img src="images/Screenshot_weaponshareb.png" alt="Weapon share comparison" />
    <p style="font-size:12px; margin-top:6px; text-align:center;">Weapon share comparison</p>
  </div>
</div>

<div style="margin-top:8px;">
  <img src="images/Screenshot_periodoverperiod.png" alt="Period-over-period comparison" />
  <p style="font-size:12px; margin-top:6px; text-align:center;">Period-over-period comparison</p>
</div>

#### Korisliiga Winners App

[![View on GitHub](https://img.shields.io/badge/GitHub-View%20on%20GitHub-24292e?logo=github&logoColor=white)](https://github.com/tujokuus/korisliiga-winners-app)

This is a small web application for browsing Korisliiga championship winners. I included it as a lightweight side project alongside my main data and analytics work.

---

<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
