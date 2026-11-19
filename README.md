# Andressa Avelar Belo

**Control & Automation Engineer moving into data.** I build data workflows from messy source to
decision-ready dashboard.

Porto, Portugal · Open to **Data Analyst / BI Analyst / Junior Data Engineer** roles ·
[LinkedIn](https://linkedin.com/in/andressaavelar) · [Portfolio](https://aavelarbelo.github.io/) · eng.belo@gmail.com

I hold a Post-Graduate degree in **Big Data & Decision Making** from **ISEP (Porto)**. I like the
unglamorous part of data work: taking **fragmented, unreliable data** and making it **clean,
traceable and useful**, with quality checks and clear documentation.

## Featured: UrbanEco, energy efficiency and housing prices in Porto

[urbaneco-analytics](https://github.com/aavelarbelo/urbaneco-analytics) ·
[project site](https://aavelarbelo.github.io/urbaneco-analytics/) · *final group project, ISEP 2026*

**Question:** how does energy efficiency relate to the asking price per m² of homes for sale in Porto?

| | |
|---|---|
| **What we found** (2,874 SuperCasa listings, June 2026) | Location matters more than energy class: the median €/m² ranges from 4,180 to 6,950 across parishes (+66%). Within the same parish and typology, A/B homes ask more per m² in 15 of 15 segments (median gap +766 €/m²). Association, not causation, and the sample is skewed: 91% of certified new builds are A/B vs 50% of used homes. |
| **My contribution** | Data collection (SuperCasa scraping with Python/Selenium) · cleaning and Energy Value Index calculation in Python · local PostgreSQL database in Docker · project documentation · dashboard review (Oct 2026): found and fixed a card that summed all segments (14,772 €/m² → 338 €/m²), an index that scored missing data as 0, and a "best parish" card picked alphabetically |
| **Group work** | The original DAX measures and the shared PostgreSQL database (Aiven) were built by the group. |
| **Stack** | `Python` · `Selenium` · `pandas` · `PostgreSQL` · `Docker` · `Power BI` |

> **Next:** I'm extending the Energy Value Index on my own, testing whether the energy premium
> holds after controlling for location, typology, condition, age and size. Repository will be
> public once it runs end to end.

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
| **From my postgrad** | data warehousing · dimensional modeling · data quality · CRISP-DM |
| **Currently learning** | T-SQL / SQL Server · AWS · CI/CD · PySpark |

*Engineer by training, data professional by choice. I care about work that is reliable,
traceable, and honest about its limits.*
