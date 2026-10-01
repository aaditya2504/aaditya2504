<div align="center">

# Aaditya Singh

<a href="https://github.com/aaditya2504">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2EA44F&center=true&vCenter=true&width=620&lines=Data+Engineer+%7C+6+Years+in+Financial+Services;Streaming+%C2%B7+CDC+%C2%B7+Lakehouse+Architecture;MS+Data+Science+%40+Northeastern+University" alt="Typing intro" />
</a>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aaditya-singh-66b269190)
[![Email](https://img.shields.io/badge/Email-C41E3A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:singh.aadit@northeastern.edu)
![Open to](https://img.shields.io/badge/Open_to-Summer_2027_Co--ops-2EA44F?style=for-the-badge)

</div>

---

### At a glance

- 🏦 **6 years** building data platforms for **CitiBank, UBS, Oldwest Bank,** and **Commonwealth Bank of Australia**
- 👥 **Team lead** at Synechron, delivering a Bronze/Silver/Gold medallion lakehouse on a streaming CDC stack
- ☁️ **AWS Certified Data Engineer, Associate**
- 🎓 **MS Data Science** @ Northeastern (Khoury College) · TA for DS 5110

### The pattern I build

```mermaid
flowchart LR
    A[(Postgres)] -->|CDC| B[Debezium]
    B --> C[Kafka]
    C --> D[Spark]
    subgraph L[Iceberg Lakehouse]
        E[Bronze] --> F[Silver] --> G[Gold]
    end
    D --> E
    H[dbt] -.-> G
```

### Tech stack

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Streaming & CDC** | ![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Debezium](https://img.shields.io/badge/Debezium-91D443?style=flat-square&logoColor=white) |
| **Processing** | ![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) |
| **Storage** | ![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Iceberg](https://img.shields.io/badge/Apache_Iceberg-2C7BB6?style=flat-square&logoColor=white) |
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) |
| **Web** | ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) |

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**streaming-lakehouse**](https://github.com/aaditya2504/streaming-lakehouse) | End-to-end streaming lakehouse pipeline | `Python` |
| **Job discovery automation** | Scores job listings against a resume with the Claude API, with hard filters and dedup. Workday portal watcher pushes alerts via ntfy.sh | `Python` `Claude API` |
| **ShowPass** | Event ticketing platform | `Django` |
| **BRFSS risk classification** | Imbalanced classification on ~400K survey respondents: logistic regression vs. random forest vs. XGBoost | `Python` `XGBoost` |

### Experience

| Company | Role | Clients | Years |
|---|---|---|---|
| **Synechron** | Data Engineer, Team Lead | Commonwealth Bank of Australia | 2024 - 2025 |
| **Empaxis Data Management** | Data Engineer | CitiBank, UBS, Oldwest Bank | 2019 - 2024 |

### Currently

- 🔨 Building **streaming-lakehouse** and **ShowPass**
- 🔍 Looking for **Summer 2027 data engineering co-ops** (open to relocating anywhere in the US)
