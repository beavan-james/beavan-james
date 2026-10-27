# Hey, I’m James 👋

Junior at Georgia Tech (Mathematics, Data Science concentration) focused on data engineering. Skilled in architecting data pipelines, designing database schemas, and building backend APIs using Python, SQL, Dagster, and cloud infrastructure.

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio.stockidence.com-0A66C2?style=flat-square)](https://portfolio.stockidence.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jamesbeavan-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/jamesbeavan)
[![Email](https://img.shields.io/badge/Email-beavan@gatech.edu-555?style=flat-square&logo=gmail&logoColor=white)](mailto:beavan@gatech.edu)

---

### 🔭 Currently building: [Stockidence](https://stockidence.com)

A stock-ranking platform that ingests prices, fundamentals, and news sentiment into a DuckDB warehouse and ranks 380 tickers with an XGBoost LambdaMART model.

- **Pipeline:** Dagster jobs incrementally load data from 4 APIs, gated by per-endpoint watermarks
- **Warehouse:** three DuckDB layers (raw → staging → mart) that compute 11 technical indicators in the pipeline
- **Model:** walk-forward validated over 26 out-of-sample quarters. Rank IC was +0.142, and the top 20 picks averaged +4.6 pp/qtr over the S&P 500
- **Serving:** FastAPI + React in Docker Compose on Oracle Cloud, retrained every quarter

[Live site](https://stockidence.com) · [Repo](https://github.com/beavan-james/Stockidence)

---

### 💼 Experience

| Role | Company | When |
| --- | --- | --- |
| Data Insights Intern | Northrop Grumman | Summer 2026 |
| Software & Data Intern | Lindaben Foundation | 2025 – 2026 |
| Data Science Intern | Intechgambit | 2024 – 2025 |

---

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Data Engineering & ML**

![Dagster](https://img.shields.io/badge/Dagster-4F43DD?style=flat-square&logo=dagster&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

**Cloud, Infra & APIs**

![AWS](https://img.shields.io/badge/AWS_(EC2,_S3,_Route_53)-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
