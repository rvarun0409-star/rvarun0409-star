# Hi, I'm Varun 👋

### Data Engineer · FinTech & Capital Markets · Jersey City, NJ

I build scalable batch and real-time data pipelines for financial services. I currently work at **DriveWealth**, where I build data pipelines and models for brokerage, trade, and account data. Before that, I spent two years at **Broadridge** building ETL pipelines and data models for capital markets reporting.

I care about data that people can trust: well-modeled warehouses, automated quality checks, and pipelines that recover on their own when something breaks.

- 🔭 Currently building pipelines on **AWS, Snowflake, Airflow, and Kafka** at DriveWealth
- 🎓 Master's in Computer Science, Montclair State University
- 💼 Open to Data Engineer roles across the US (on-site, hybrid, or remote)
- 📫 Reach me at **rvarun0409@gmail.com**

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Bash](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Big Data, Streaming & Orchestration**

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)

**Cloud & Warehousing**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

**DevOps, Quality & BI**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great%20Expectations-FF6310?style=flat-square)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

## 💼 Experience

**Data Engineer · DriveWealth** · New York, NY · *July 2026 – Present*
- Build Python and PySpark ETL pipelines that ingest brokerage, trade, and account data from APIs, Kafka streams, and relational sources into an AWS data lake
- Design Snowflake and Redshift data models for analytics, reporting, and regulatory needs
- Orchestrate workflows in Airflow with monitoring, alerting, and automated retries
- Automate data quality and reconciliation checks for transaction and portfolio data

**Data Engineer · Broadridge** · Hyderabad, India · *Aug 2021 – Oct 2023*
- Built ETL pipelines in Python, SQL, and Spark for large volumes of financial and securities data
- Designed dimensional models for investor communications and capital markets reporting
- Built batch and near real-time ingestion on AWS (S3, Glue, Lambda, EMR)
- Migrated legacy on-premises ETL to cloud pipelines, improving scalability and processing time

---

## 🚀 Featured Projects

### [Real-Time Trade Stream Pipeline](https://github.com/rvarun0409-star/realtime-trade-pipeline)
Streams trade events from **Kafka** through **Spark Structured Streaming** into a bronze, silver, and gold **Delta Lake**. Quarantines bad events with a reason, handles late data with watermarks, and computes 1-minute VWAP and order imbalance per symbol. Fully Dockerized, with an end-to-end streaming test in CI.

`Kafka` `PySpark` `Spark Structured Streaming` `Delta Lake` `Docker` `GitHub Actions`

### [Market Data ELT with Airflow & dbt](https://github.com/rvarun0409-star/market-data-elt)
Daily **Airflow** DAG that extracts equity prices, loads them idempotently into a warehouse, and builds a **dbt** star schema with returns, moving averages, and volatility. 26 dbt data tests, Snowflake-ready, and CI that backfills four months and verifies the DAG in real Airflow.

`Airflow` `dbt` `DuckDB` `Snowflake` `SQL` `Docker` `GitHub Actions`

### [Transaction Reconciliation Framework](https://github.com/rvarun0409-star/txn-reconciliation)
Reconciles an internal trade ledger against broker records, the daily control every brokerage runs. Normalizes different file formats, quarantines bad data, and classifies every break (missing, duplicate, quantity, price, amount) with configurable tolerances.

`Python` `pandas` `Data Quality` `pytest` `GitHub Actions`

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varun-r04)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rvarun0409@gmail.com)
