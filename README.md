<div align="center">

# Khaled Metwalie

### Pharmacist · Data Scientist · HealthTech Analyst

[![GitHub](https://img.shields.io/badge/GitHub-kahledawad2019--netizen-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kahledawad2019-netizen)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khaled-metwalie)

</div>

---

## About Me

I'm a pharmacist turned data scientist — I combine deep healthcare domain expertise with modern machine learning and data engineering to solve real-world problems. My work spans the full pipeline: from designing production-grade databases and building ETL workflows, to training ensemble ML models and deploying them via REST APIs.

**What drives me:** Turning raw data into actionable insights that matter — whether it's predicting pharmaceutical demand, detecting unauthorized drones, or optimizing hospital operations.

---

## Tech Stack

| Domain | Tools & Technologies |
|---|---|
| **Languages** | Python, SQL |
| **ML / AI** | Scikit-learn, XGBoost, LightGBM, Random Forest, Time-Series Forecasting |
| **Deep Learning** | PyTorch, CNNs, Multimodal Fusion Networks |
| **Data Engineering** | SQL Server, Database Design (3NF), ER Modeling, Stored Procedures, Triggers |
| **Analytics & Viz** | Power BI, Orange 3, Pandas, Matplotlib, Seaborn, Excel Pivot Tables |
| **Deployment** | FastAPI, Uvicorn, Jupyter Notebooks, REST APIs |
| **Domain** | Pharmaceutical Analytics, Healthcare (Hospital LOS), Counter-UAV Systems |

---

## Featured Projects

---

### HYDRA-Net — Counter-UAV Detection System
> **H**ierarchical **Y**ield-**D**riven **R**esilient **A**sync-fusion Network

A cascaded multimodal architecture for anti-drone detection that achieves **91.9x speedup** at the median through confidence-gated early exit, while retaining full multimodal reasoning for hard cases.

- **90.07% accuracy** on drone distance estimation (1m / 50m / 100m)
- **97.94% accuracy** among early-exit samples at the 0.95 confidence threshold
- **1.10ms p50 latency** vs 101ms monolithic baseline
- Full architecture: Stages 1-3 (RF signals, RGB/IR vision, swarm GNN), async fusion, meta-learned modality gate, explainability module, FastAPI serving
- 4 Colab notebooks, 14 passing unit tests, comprehensive documentation

`Python` `PyTorch` `Computer Vision` `Signal Processing` `FastAPI`

---

### Hotel Reservation — Data Mining Project
> **Predicting Hotel Booking Cancellations with 92.93% Accuracy**

End-to-end data mining pipeline from database design to a production-ready prediction app, processing **119,208 bookings** with **60+ engineered features** across **8 ML models**.

- **Part 1:** SQL Server database with 4 normalized tables and 28 insight queries
- **Part 2:** Python EDA + Orange 3 visual data mining + Power BI dashboard
- **Part 3:** Stacking Ensemble, XGBoost, LightGBM, HistGB — best accuracy **92.93%**

`Python` `SQL Server` `XGBoost` `Power BI` `Orange 3` `Machine Learning`

---

### Hospital Length of Stay — Data Mining Project
> **Complete Data Engineering & Analytics Pipeline (Score: 20/20)**

A two-part integrated pipeline tackling hospital LOS prediction through production-grade database design and exploratory data analysis on **318,438 patient records**.

- **Part 1:** 22 normalized tables, 28 foreign keys, 6 stored procedures, 3 triggers, 10 views, 6 RBAC roles, 21 indexes across 7 functional domains
- **Part 2:** Python EDA notebook, Orange visual pipeline, Power BI dashboard, 20 EDA questions answered, storytelling report

`Python` `SQL Server` `Power BI` `Orange 3` `Database Design`

---

### Pharma Demand Forecasting
> **End-to-End ML Pipeline for Pharmaceutical Drug Sales Forecasting**

A complete forecasting pipeline for **8 ATC-coded drug categories** using time-series analysis and ensemble models, deployed via a production-ready FastAPI REST API.

- Multi-granularity data: hourly, daily, weekly, monthly
- XGBoost + Random Forest with RandomizedSearchCV hyperparameter tuning
- FastAPI `/predict_sales` endpoint for real-time inference
- Time-aware train/test split to prevent future data leakage

`Python` `XGBoost` `FastAPI` `Time-Series` `Forecasting` `REST API`

---

### Pharma Sales Analysis Dashboard
> **600,000+ Medical Sales Transactions Analyzed**

Analysis of pharmaceutical sales data to identify seasonal trends, top-selling drug categories, and weekly demand cycles — demonstrating how pharmacy domain knowledge enhances data analytics.

- Built a **translation layer** mapping ATC codes to business-friendly categories for non-medical stakeholders
- Discovered strong seasonality: Antihistamines peak in Spring, Asthma/COPD drugs peak in Winter
- Identified Monday as the highest-volume sales day for staffing optimization

`Excel` `Pivot Tables` `Data Visualization` `Healthcare Analytics`

---

### ML Prediction Project — Body Performance Analysis
> **Predicting Physical Performance Categories with Machine Learning**

Full ML pipeline for analyzing and predicting human body performance from health and fitness metrics — from EDA and feature engineering to interactive Jupyter-based prediction.

- Multi-model comparison of classification algorithms
- Interactive prediction interface in Jupyter Notebook
- Complete analytical story report and presentation decks

`Python` `Scikit-learn` `Jupyter` `Pandas` `Seaborn`

---

### HR & Payroll Analytics Dashboard
> **Workforce Analytics for Salary, Tax, and Bonus Optimization**

Employee-level workforce analytics exploring salary structures, tax deductions, bonuses, and net salary distribution with actionable insights for payroll management.

- Departmental breakdown across Full-time, Contract, Hourly, and Half-time work types
- Country-level workforce distribution analysis
- Extra bonus eligibility identification based on net salary thresholds
- Hiring trend analysis by year, month, and experience

`Excel` `HR Analytics` `Data Cleaning` `Workforce Segmentation`

---

### Sales & Profit Analytics Dashboard
> **Global Sales Performance Analysis with KPI Tracking**

Comprehensive sales analytics across multiple countries, categories, and products — tracking profitability, customer behavior, and operational efficiency.

- 7 KPIs tracked: profit margin, total sales, profit, customer count, order volume, shipping duration, discount value
- Country, category, and product-level profitability analysis
- Yearly and monthly sales/profit trend identification
- Identified products with negative profitability for corrective action

`Excel` `Pivot Tables` `KPI Design` `Customer Segmentation`

---

### PageTurners Bookstore Database
> **Complete SQL Database for Bookstore Operations**

A full relational database project for PageTurners Bookstore featuring ER diagrams, data integrity constraints, and business queries.

- Entity-Relationship diagram design
- Data integrity constraints and referential integrity
- Business query implementations

`SQL` `Database Design` `ER Modeling`

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kahledawad2019-netizen&show_icons=true&theme=radical&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kahledawad2019-netizen&layout=compact&theme=radical&hide_border=true)

</div>

---

## What I Bring to the Table

- **Domain + Data:** A rare combination of healthcare/pharmacy expertise with full-stack data science skills
- **End-to-End Thinking:** I don't just build models — I design databases, engineer features, train models, evaluate rigorously, and deploy via APIs
- **Production Awareness:** REST endpoints, database normalization, RBAC, stored procedures — not just notebooks
- **Communication:** Storytelling reports, presentation decks, and dashboards that make insights accessible to non-technical stakeholders

---

<div align="center">

*Open to collaborations in HealthTech, Pharma Analytics, and ML Engineering.*

</div>
