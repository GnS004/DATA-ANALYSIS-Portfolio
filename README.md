<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Data%20Analysis%20Portfolio&fontSize=46&animation=fadeIn&fontAlignY=36&fontColor=ffffff&desc=EDA%20%E2%80%A2%20Statistical%20Modeling%20%E2%80%A2%20Business%20Intelligence%20%E2%80%A2%20Visual%20Storytelling&descAlignY=58&descColor=cccccc&descSize=16)

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=18&duration=3000&pause=800&color=F0C060&center=true&vCenter=true&width=700&lines=Data+Analyst+%7C+Data+Enthusiast;End-to-End+Analytics+%E2%80%A2+EDA+to+Insights;Python+%7C+SQL+%7C+Tableau+%7C+Power+BI+%7C+Machine+Learning;IIT+Kharagpur+Hackathon+%F0%9F%8F%86+Top+20%2F800%2B" alt="Typing SVG"/>

---

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://tableau.com)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](#)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)

*"Without data, you're just another person with an opinion. With data, you change the world."*

</div>


## 👩‍💻 About This Repository

This portfolio is a curated showcase of **end-to-end data analysis projects** designed to demonstrate readiness for:

<div align="center">
    
| Role | What I Demonstrate Here |
|------|------------------------|
| 📊 **Data Analyst** | EDA, SQL, dashboards, statistical inference, visualization |
| 💼 **Business Analyst** | Funnel analysis, KPI tracking, market research, stakeholder-ready reports |
| 🔬 **Research Analyst** | Hypothesis testing, correlation analysis, scientific methodology |
| 📈 **BI / Reporting Analyst** | Tableau dashboards, Cognos, automated ETL reports |

</div>

```
Pipeline: Raw Data → Cleaning → EDA → Statistical Analysis → Modeling → Visualization → Insights
```
---

## 📁 Project Index

<div align="center"> 
    
| # | Project | Type | Tools | Key Result |
|---|---------|------|-------|------------|
| [01](#-project-1-covid-19--weather-correlation) | 🦠 COVID-19 × Weather Correlation | Research / EDA | Python, Seaborn, SciPy | r = −0.42 temp-case correlation |
| [02](#-project-2-customer-behavior--journey-analysis) | 👥 Customer Behavior Analysis | Business Analytics | Python, GA Data | 68% funnel drop-off identified |
| [03](#-project-3-sales--revenue-analysis) | 🛒 Sales & Revenue Dashboard | BI / Reporting | Pandas, Tableau | Top 20% SKUs = 78% revenue |
| [04](#-project-4-time-series-demand-forecasting) | 📈 Time Series Forecasting | Data Science | Statsmodels, ARIMA | RMSE = 143 on 30-day forecast |
| [05](#-project-5-ab-testing-framework) | 🧪 A/B Testing Framework | Research / Stats | SciPy, Python | +8.3% conversion lift, p < 0.01 |
| [06](#-project-6-real-estate-market-eda) | 🏡 Real Estate Market EDA | Data Analysis | Scikit-learn, Plotly | Location = 41% of price variance |

</div>

---

## 🔬 Project Details

### 🦠 Project 1: COVID-19 × Weather Correlation
> **`/01_covid_weather_analysis/`** &nbsp;|&nbsp; Research Analytics 

**Objective:** Investigate statistical relationships between COVID-19 mortality rates and environmental factors across the full pandemic timeline.

**Research Questions:**
- Does temperature significantly correlate with COVID-19 case severity? (r = **−0.42** in temperate zones)
- How do ozone levels and humidity interact with mortality rates?
- Are these relationships consistent across geographies and time lags?

**Methods Used:**
```
Pearson Correlation → Spearman Rank → Time-lagged Analysis → Multivariate OLS Regression
```

**Key Findings:**
- Moderate negative correlation between temperature and case counts in temperate regions
- 14-day time-lagged ozone levels show stronger predictive power than same-day readings
- Coastal humidity negatively correlated with mortality rate (p < 0.05)

---

### 👥 Project 2: Customer Behavior & Journey Analysis
> **`/02_customer_behavior/`** &nbsp;|&nbsp; Business Analytics 

**Objective:** Analyze user interaction patterns from Google Analytics export data to uncover conversion inefficiencies and growth opportunities.

**Business Questions Answered:**
- Where do users drop off in the conversion funnel? (**68% drop at cart stage**)
- Which traffic sources bring highest-LTV users? (**Direct traffic = 2.3× LTV**)
- What pages drive return visits and engagement?

**Methods Used:**
```
Funnel Analysis → Cohort Retention → RFM Segmentation → Session Clustering → Path Analysis
```

**Deliverables:**
- Executive summary slide deck
- Annotated Jupyter notebook with reproducible code
- Tableau funnel visualization dashboard

---

### 🛒 Project 3: Sales & Revenue Analysis
> **`/03_sales_revenue/`** &nbsp;|&nbsp; Business Intelligence 

**Objective:** Comprehensive multi-dimensional analysis of sales performance across product lines, regions, and time periods.

**Business Questions Answered:**
- Which product SKUs drive disproportionate revenue? (Pareto: **top 20% = 78% revenue**)
- What seasonal trends and anomalies exist in sales data?
- Which regions are underperforming relative to market potential?

**Methods Used:**
```
YoY Growth Analysis → Pareto (80/20) → Moving Averages → Heatmaps → Regional Decomposition
```

**Deliverables:**
- Interactive Tableau dashboard (`dashboard.twbx`) with drill-down capability
- Automated Python report generator
- Regional performance heatmap

---

### 📈 Project 4: Time Series Demand Forecasting
> **`/04_time_series/`** &nbsp;|&nbsp; Data Science / Forecasting 

**Objective:** Forecast retail demand using classical time series decomposition and ARIMA modeling with rigorous statistical validation.

**Technical Approach:**
```
ADF Stationarity Test → STL Decomposition → ACF/PACF Analysis → ARIMA(2,1,2) → Forecast Evaluation
```

**Results:**
- ARIMA(2,1,2) achieves **RMSE = 143** on 30-day out-of-sample forecast
- Seasonal component accounts for 34% of total variance
- 95% prediction intervals constructed for uncertainty quantification

**Deliverables:**
- Reproducible forecasting pipeline
- Diagnostic plots (residuals, ACF, forecasts with confidence bands)
- Model selection comparison table

---

### 🧪 Project 5: A/B Testing Statistical Framework
> **`/05_ab_testing/`** &nbsp;|&nbsp; Research / Product Analytics 

**Objective:** Build a rigorous A/B testing framework with proper statistical controls, power analysis, and business impact quantification.

**Statistical Methods:**
```
Power Analysis → Two-proportion Z-test → Chi-square Test → Mann-Whitney U → Bonferroni Correction
```

**Key Results:**
- Variant B shows **+8.3% conversion lift** (p < 0.01, 95% CI: [4.1%, 12.5%])
- Power analysis confirms 95%+ statistical power at given sample size
- Multiple testing correction applied — no false discovery rate inflation

**Deliverables:**
- Reusable A/B testing Python module (`ab_test.py`)
- Statistical decision report template
- Business impact calculator (revenue × lift × confidence)

---

### 🏡 Project 6: Real Estate Market EDA
> **`/06_real_estate_eda/`** &nbsp;|&nbsp; Data Analysis 

**Objective:** Deep-dive EDA into housing market data — feature importance, anomaly detection, and geospatial price patterns.

**Analytical Techniques:**
```
Outlier Detection (IQR + Z-score) → Correlation Matrix → Feature Importance (RF) → Geospatial Visualization
```

**Key Findings:**
- Location-encoded features account for **41% of price variance**
- Above-ground square footage is the single strongest continuous predictor (r = 0.71)
- 4.2% of listings flagged as statistical anomalies requiring business review

**Deliverables:**
- Comprehensive EDA report with 25+ annotated charts
- Cleaned, documented dataset pipeline
- Feature importance ranking for downstream modeling

---

## 🛠️ Full Tech Stack

```python
portfolio_stack = {
    "languages":           ["Python 3.10+", "SQL"],
    "data_wrangling":      ["Pandas", "NumPy", "OpenRefine", Excel],
    "visualization":       ["Matplotlib", "Seaborn", "Plotly", "Tableau", "Power BI"],
    "statistics":          ["SciPy", "Statsmodels", "Pingouin"],
    "machine_learning":    ["Scikit-learn", "XGBoost", "SHAP"],
    "time_series":         ["Statsmodels (ARIMA)", "Prophet"],
    "notebooks":           ['VS Code", "Jupyter Notebook", "Google Colab"],
    "etl":                 ["Python ETL Pipelines", "SQL Transformations"],
    "version_control":     ["Git", "GitHub"],
    "communication":       ["Executive Summaries", "Slide Decks", "Dashboard Storytelling"]
}
```

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/garima-srivastava-32431a21a/)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:garimasrivastava.work.in@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GnS004)
[![Linktree](https://img.shields.io/badge/Linktree-43E55E?style=for-the-badge&logo=linktree&logoColor=white)](https://linktr.ee/GarimaSrivastava)

**📍 Lucknow, Uttar Pradesh, India**

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=140&section=footer&fontColor=ffffff)

**⭐ Star this repo if you found it useful!**

*Turning data into decisions, one notebook at a time.*

</div>
