# Hi, I'm Andressa Avelar 👋🤓

**Control & Automation Engineer turned Data Engineer — I build data pipelines end to end, from messy source to decision-ready dashboard.**

I hold a Post-Graduate degree in **Big Data & Decision Making** from **ISEP (Porto)**. My focus is the part of data engineering that banks and ESG teams struggle with most: taking **fragmented, unreliable data** and making it **clean, traceable and useful** — with quality checks, dimensional modeling and clear documentation.

📍 Porto, Portugal  ·  💼 Open to **junior / trainee Data Engineering** roles

🔗 [LinkedIn](https://linkedin.com/in/andressaavelar)  ·  [Portfolio](https://aavelarbelo.github.io/)  ·  eng.belo@gmail.com  ·  [@debugandressa](https://www.instagram.com/debugandressa)

---

## ⭐ Featured — UrbanEco: an ESG-style data pipeline

**[energy-value-index-porto](https://github.com/aavelarbelo/energy-value-index-porto)**  ·  *in active development*

Turning fragmented, unreliable public property data into a **reliable, geographically-disaggregated Energy Value Index (EVI)** — from ingestion and quality control all the way to the dashboard. It's the same problem sustainable-finance teams describe: ESG data that is scarce, messy and hard to trust.

**What I built, end to end:**
- **Ingestion** — a multi-page Selenium scraper (~2,800 property listings across 7 districts of Porto), with source traceability and de-duplication
- **Quality & standardization** — separate raw and validated bases, cleaned prices/areas, boolean amenities
- **Warehouse** — a 24-variable schema on PostgreSQL (Aiven Cloud)
- **Index** — a documented, weighted **Energy Value Index** (Energy 55% + Price 45%, scored 1–10)
- **Reporting** — a Power BI dashboard with the EVI and a per-district energy gap

`Python` · `Selenium` · `PostgreSQL` · `Power BI` · `Data Quality` · `Dimensional Modeling`

> Individual continuation of an ISEP group project ([urbaneco-analytics](https://github.com/aavelarbelo/urbaneco-analytics), archived), where I led the data engineering — rebuilt end to end and developed with the team's permission. Prices are asking prices and any synthetic fields are flagged, stated openly for methodological transparency.

---

## 🧠 Also — Customer Churn Prediction

**[data-mining-churn-prediction](https://github.com/aavelarbelo/data-mining-churn-prediction)**

Telecom customer churn with **CRISP-DM**: EDA, data cleaning, and several classifiers compared — with the honest finding that the highest-*accuracy* model was **not** the best *business* choice, because missing a churner costs more than a false alarm. The dataset also hid mixed encodings from two merged sources; I caught it during preparation and re-ran the pipeline. Full write-up in the repo.

`Python` · `pandas` · `scikit-learn` · `CRISP-DM`

---

## 🛠️ Tech

**Core:** Python (pandas, NumPy, scikit-learn) · SQL · PostgreSQL · Selenium · Power BI · Docker · Git
**From my postgrad:** dimensional modeling · data warehousing · data quality · CRISP-DM
**Currently learning:** T-SQL / SQL Server · AWS · CI/CD · PySpark

---

*Engineer by training, data engineer by choice — I care about pipelines that are reliable, traceable, and honest about their limits.*
