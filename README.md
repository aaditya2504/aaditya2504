<div align="center">

# Aaditya Kumar Singh

<a href="https://github.com/aaditya2504">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2EA44F&center=true&vCenter=true&width=640&lines=Data+Engineer+%7C+5%2B+Years+in+Financial+Services;CDC+%C2%B7+Streaming+%C2%B7+Lakehouse+Architecture;MS+Data+Science+%40+Northeastern+University" alt="Typing intro" />
</a>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aaditya-singh-66b269190)
[![Email](https://img.shields.io/badge/singh.aadit%40northeastern.edu-C41E3A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:singh.aadit@northeastern.edu)
![Open to](https://img.shields.io/badge/Open_to-Co--op_Jan_to_Jun_2027-2EA44F?style=for-the-badge)

📫 **singh.aadit@northeastern.edu**

</div>

---

### At a glance

- 🏦 **5+ years** building ETL/ELT pipelines and data models for **CitiBank** and **Commonwealth Bank of Australia**
- ⚡ **500K+ records/day** processed · **40% faster** queries · **99.5% pipeline uptime** SLA
- 👥 Led engineering teams of **5 and 6**, and mentored **10+** junior engineers
- ☁️ **AWS Certified Data Engineer, Associate**
- 🎓 **MS Data Science** @ Northeastern (GPA 4.0) · TA for Essentials of Data Science

### Flagship build: streaming CDC lakehouse

```mermaid
flowchart LR
    A[(Postgres)] -->|CDC| B[Debezium]
    B --> C[Kafka]
    C --> D[Spark]
    subgraph L[Iceberg Lakehouse]
        E[Bronze] --> F[Silver] --> G[Gold]
    end
    D --> E
    H[dbt] -.->|transforms| L
    G --> I[Trino]
```

### Tech stack

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Streaming & CDC** | ![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Debezium](https://img.shields.io/badge/Debezium-91D443?style=flat-square&logoColor=white) |
| **Processing & Orchestration** | ![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Informatica](https://img.shields.io/badge/Informatica-FF4D00?style=flat-square&logoColor=white) |
| **Lakehouse & Query** | ![Iceberg](https://img.shields.io/badge/Apache_Iceberg-2C7BB6?style=flat-square&logoColor=white) ![Trino](https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white) ![Athena](https://img.shields.io/badge/AWS_Athena-232F3E?style=flat-square&logoColor=white) |
| **Databases & Warehouses** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![Teradata](https://img.shields.io/badge/Teradata-F37440?style=flat-square&logo=teradata&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **Cloud & DevOps** | ![AWS](https://img.shields.io/badge/AWS_(S3,_Redshift,_Glue,_Lambda)-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **Analytics & ML** | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logoColor=black) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logoColor=white) |

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**Streaming Lakehouse**](https://github.com/aaditya2504/streaming-lakehouse) | Low-latency CDC lakehouse across 6 services, with a 3-layer medallion architecture managed in dbt for auditable, reproducible transformations | `Postgres` `Debezium` `Kafka` `Spark` `Iceberg` `Trino` `dbt` |
| [**Mental Health Social Determinants**](https://github.com/aaditya2504/brfss-mental-health-analysis) | Survey-weighted analysis of 200K+ BRFSS 2024 respondents across 33 states. Found loneliness is the strongest modifiable predictor of poor mental health days | `R` `survey` `R Markdown` |

| **Restaurant Analytics Platform** | Normalized MySQL database on Aiven Cloud with ACID transactions and concurrency testing, daily Airflow batch ETL, and a 5-table star-schema warehouse with OLAP queries | `MySQL` `Python` `Airflow` `R` |
| **Job Discovery Automation** | Scores job listings against a resume with the Claude API, with hard filters and dedup. Workday portal watcher pushes alerts via ntfy.sh | `Python` `Claude API` |

### Experience

| Company | Role | Client | Years |
|---|---|---|---|
| **Synechron** | Senior Data Management Analyst (Acting Team Lead) | Commonwealth Bank of Australia | 2023 - 2025 |
| **Empaxis Data Management** | Team Lead / ETL Developer | CitiBank | 2019 - 2023 |
| **Northeastern University** | Teaching Assistant, Essentials of Data Science | Khoury College | 2026 - Present |

### Currently

- 🔨 Building **Streaming Lakehouse** and **ShowPass**, a Django event ticketing platform
- 🔍 Seeking a **data engineering co-op, January to June 2027**
