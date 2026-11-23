# Andressa Avelar Belo

**Junior Data Engineer** with a background in Control & Automation Engineering. I build data
workflows from messy source to decision-ready dashboard.

Porto, Portugal · Open to **Data Analyst / BI Analyst / Junior Data Engineer** roles ·
[LinkedIn](https://linkedin.com/in/andressaavelar) · [Portfolio](https://aavelarbelo.github.io/) · eng.belo@gmail.com

I hold a Post-Graduate degree in **Big Data & Decision Making** from **ISEP (Porto)**. I like the
unglamorous part of data work: taking **fragmented, unreliable data** and making it **clean,
traceable and useful**, with quality checks and clear documentation.

## Featured: LLM Job Application Assistant

[llm-job-application-assistant](https://github.com/aavelarbelo/llm-job-application-assistant) · *personal project, 2026 · in production since 19 Nov 2026*

**Problem:** use an LLM to screen job postings and tailor CVs faster, without letting it invent
experience, round numbers up or misread a profile.

| | |
|---|---|
| **What it does** | A daily n8n workflow reads LinkedIn job alerts, applies a free rule-based pre-filter and asks the Claude API to score each posting (0–100) against a verified master profile, returning structured JSON. Postings scoring 60+ arrive by email with a tailored CV and cover letter; every result is logged in Google Sheets. I review and submit every application myself. |
| **Guardrails** | Single-source profile with an explicit list of forbidden claims; a Python CV generator that rejects any fact not marked as verified and checks the 1-page limit; error alerts instead of silent failures. |
| **Found in testing** | Responses were truncated because adaptive thinking used 5,764 of 6,000 output tokens; fixed through the thinking configuration and token limit. Measured cost: ≈ US$ 0.04 per posting. |
| **Stack** | `n8n` · `Claude API` · `Python` · `python-docx` · `Gmail` · `Google Sheets` |

## Also: UrbanEco, energy efficiency and housing prices in Porto

[urbaneco-analytics](https://github.com/aavelarbelo/urbaneco-analytics) ·
[project site](https://aavelarbelo.github.io/urbaneco-analytics/) · *final group project, ISEP 2026*

**Question:** how does energy efficiency relate to the asking price per m² of homes for sale in Porto?

| | |
|---|---|
| **What we found** (2,874 SuperCasa listings, June 2026) | Location matters more than energy class: the median €/m² ranges from 4,180 to 6,950 across parishes (+66%). Within the same parish and typology, A/B homes ask more per m² in 15 of 15 segments (median gap +766 €/m²). Association, not causation, and the sample is skewed: 91% of certified new builds are A/B vs 50% of used homes. |
| **My contribution** | Data collection (SuperCasa scraping with Python/Selenium) · cleaning and Energy Value Index calculation in Python · local PostgreSQL database in Docker · project documentation · dashboard review (Oct 2026): found and fixed a card that summed all segments (14,772 €/m² → 338 €/m²), an index that scored missing data as 0, and a "best parish" card picked alphabetically |
| **Group work** | The original DAX measures and the shared PostgreSQL database (Aiven) were built by the group. |
| **Stack** | `Python` · `Selenium` · `pandas` · `PostgreSQL` · `Docker` · `Power BI` |

## Also: Customer Churn Prediction

[data-mining-churn-prediction](https://github.com/aavelarbelo/data-mining-churn-prediction)

| | |
|---|---|
| **What it is** | Telecom customer churn with **CRISP-DM**: EDA, data cleaning and several classifiers compared. |
| **Key finding** | The highest-*accuracy* model was **not** the best *business* choice, because missing a churner costs more than a false alarm. Full write-up in the repo. |
| **Stack** | `Python` · `pandas` · `scikit-learn` · `CRISP-DM` |

## Tech

| | |
|---|---|
| **Used in projects** | Python (pandas, NumPy, scikit-learn, Selenium) · SQL · PostgreSQL · Power BI · Docker · Git |
| **LLM applications** | Claude API · prompt and context engineering · structured JSON output · n8n workflow automation |
| **From my postgrad** | data warehousing · data quality · CRISP-DM · Spark · Kafka · NoSQL |
| **Currently learning** | Airflow · Snowflake · dbt (Data Engineering bootcamp, in progress) |

*Engineer by training, data professional by choice. I care about work that is reliable,
traceable, and honest about its limits.*
