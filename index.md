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

### Projects & Data Science

#### Air Strikes on Ukraine Analysis Dashboard

[![Open Dashboard](https://img.shields.io/badge/Streamlit-Open%20Dashboard-ff4b4b?logo=streamlit&logoColor=white)](https://strikes-on-ukraine-analysis.streamlit.app/)
[![View on GitHub](https://img.shields.io/badge/GitHub-View%20on%20GitHub-24292e?logo=github&logoColor=white)](https://github.com/tujokuus/air-strikes-on-ukraine-dashboard)

In this MVP-stage project, I developed an end-to-end data analytics solution for exploring reported missile and UAV strike activity in Ukraine. The project combines data analysis, data engineering, and dashboard development: I collected and processed raw CSV data in Python with pandas, cleaned and standardized key fields such as dates, weapon references, and target areas, and transformed the data into a bronze, silver, and gold architecture. I then used DuckDB and SQL to build analytics-ready marts and views, and created an interactive Streamlit dashboard with Plotly and PyDeck to visualize trends over time, weapon activity, regional patterns, and air defense success rates.

<div class="project-gallery-pair">
  <div class="project-gallery-grid">
    <div class="project-gallery-item project-gallery-item--fixed">
      <img src="images/Screenshot_overview1_b.png" alt="Dashboard overview" />
    </div>
    <div class="project-gallery-item project-gallery-item--fixed">
      <img src="images/Screenshot_interactivemap1b.png" alt="Interactive map view" />
    </div>
  </div>
  <p class="project-gallery-caption">Dashboard overview and interactive regional analysis.</p>
</div>

<div class="project-gallery-pair">
  <div class="project-gallery-grid">
    <div class="project-gallery-item project-gallery-item--fixed">
      <img src="images/Screenshot_periodoverperiod.png" alt="Period-over-period comparison" />
    </div>
    <div class="project-gallery-item project-gallery-item--fixed">
      <img src="images/Screenshot_weaponshareb.png" alt="Weapon share comparison" />
    </div>
  </div>
  <p class="project-gallery-caption">Time period comparison and weapon share analysis.</p>
</div>

#### Predicting Irrigation Need - Kaggle competition

[![Kaggle EDA](https://img.shields.io/badge/Kaggle-EDA-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/kuusistotuomas/irrigation-need-eda)
[![Kaggle Modeling](https://img.shields.io/badge/Kaggle-Modeling-0f172a?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/kuusistotuomas/highstacking)

In this notebook project, I built an end-to-end stacked machine learning workflow for the Kaggle Playground Series S6E4 irrigation need prediction task. The work combines exploratory data analysis, gradient boosting model development, and ensemble optimization: I profiled the raw tabular data in Python with pandas, compared feature distributions and class balance with interactive visual analysis, trained tuned XGBoost and CatBoost models, and generated out-of-fold probability predictions for model blending. I then optimized class-specific post-processing for the rare High irrigation class, trained a dedicated binary meta-model on top of the blended probabilities, and evaluated the full stack with cross-validation before exporting competition-ready submission files.

<div class="project-gallery-pair">
  <div class="project-gallery-grid">
    <div class="project-gallery-item project-gallery-item--fixed">
      <img src="images/numerical_feature_dist.png" alt="Numerical feature distributions" />
    </div>
    <div class="project-gallery-item project-gallery-item--fixed">
      <img src="images/target_call_composition.png" alt="Target class composition" />
    </div>
  </div>
  <p class="project-gallery-caption">Exploratory views for feature distributions and target class composition.</p>
</div>

<div class="project-gallery-pair">
  <div class="project-gallery-grid">
    <div class="project-gallery-item project-gallery-item--fixed">
      <img src="images/Violin_plots.png" alt="Violin plots" />
    </div>
    <div class="project-gallery-item project-gallery-item--fixed">
      <img src="images/Feature importance.png" alt="Feature importance" />
    </div>
  </div>
  <p class="project-gallery-caption">Feature behavior and model interpretation views.</p>
</div>

<div class="project-gallery-single">
  <img src="images/3d.png" alt="3D class separation view" />
  <p class="project-gallery-caption">3D projection view for class separation analysis.</p>
</div>

#### Korisliiga Winners App

[![View on GitHub](https://img.shields.io/badge/GitHub-View%20on%20GitHub-24292e?logo=github&logoColor=white)](https://github.com/tujokuus/korisliiga-winners-app)

This is a small web application for browsing Korisliiga championship winners. I included it as a lightweight side project alongside my main data and analytics work.

---
