# 📈 Demographic Shifts & Labor Market Dynamics (Germany)

> **Econometric study using R to clean, model, and visualize high-dimensional demographic and migration datasets to evaluate impacts on German labor market outcomes.**
> **Answering to the question "Does EU migration help the German labor market?"**

---

## 📌 Project Overview
This project analyzes the long-term relationship between shifting demographics, regional migration inflows, and macroeconomic labor market indicators across German federal states. It bridges data engineering pipelines in R with quantitative economic theory.

### 📊 Core Analytical Dimensions
* **Demographic Variables:** Age cohorts, dependency ratios, and population aging velocity.
* **Migration Patterns:** Internal regional migration tracking and international net inflows.
* **Labor Market Outcomes:** Unemployment rates, participation capacity, and employment densities.

---

## 🛠️ Tech Stack & Engineering Pipeline (R)

The pipeline was built entirely in **R-Studio**, focusing on creating reproducible workflows for complex, noisy public statistical registries:

* **Data Wrangling (`tidyverse`):** Used `dplyr` and `tidyr` to clean, normalize, and structurally join disparate state-level datasets over a multi-year timeline.
* **Econometric Modeling:** Implemented multivariate regression models to isolate the net impact of migration trends on labor supply elasticity, controlling for regional structural variations.
* **Data Visualization (`ggplot2`):** Engineered publication-grade charts to map correlation trends between aging workforces and regional contraction.
* **Collaborative Git Workflow:** Maintained a shared codebase with a peer, managing version control, code reviews, and modular script development.

---

## 📈 Key Research Insights Derived

<img width="2400" height="1500" alt="3_groups" src="https://github.com/user-attachments/assets/4f3847d5-8d14-41b2-903d-98ff1862a98d" />

* **Dominance of Eastern EU Migration:** The analysis reveals that migration inflows from **Eastern European EU member states** exert the most powerful and statistically significant positive impact on the German labor market, serving as the primary driver for filling critical structural workforce vacancies.
* **The 3-Group Regional Asymmetry:** Using cluster analysis, German states were segmented into three distinct groups, proving that migration does not impact the country uniformly. High-income industrial hubs absorb migration cleanly to fuel growth, while other regions face varying structural friction based on their local infrastructure.
* **The Domestic Aging & Youth Drain Trap:** The empirical data underscores a severe vulnerability: while external migration buffers the workforce, it cannot completely neutralize the deep systemic labor contractions in specific states caused by the combination of a rapidly aging domestic population and an internal "youth drain" (young workers relocating out of the region).
