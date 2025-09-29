# 🗂 Data Engineering Portfolio

![Python](https://img.shields.io/badge/Python-Programming-yellow)
![SQL](https://img.shields.io/badge/SQL-Queries-lightgrey)
![Airflow](https://img.shields.io/badge/Airflow-Orchestration-blue)
![Kafka](https://img.shields.io/badge/Kafka-Streaming-black)
![dbt](https://img.shields.io/badge/dbt-Transformations-orange)
![Snowflake](https://img.shields.io/badge/Snowflake-Cloud-lightblue)
![AWS S3](https://img.shields.io/badge/AWS-S3-green)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue)

Welcome! This repository highlights **end-to-end data engineering projects** I built to demonstrate skills in **real-time streaming pipelines, batch orchestration, cloud data warehousing, and modern transformation frameworks**.

Each project is fully documented and containerized for reproducibility.  

---

## 📐 Projects Overview

### 🌊 Real-Time NOAA Buoy Data Pipeline
- **Tech:** Kafka (Redpanda), Python, S3, Snowflake, Snowpipe, Pandas  
- **Highlights:**  
  - Real-time streaming ingestion from NOAA buoy sensors.  
  - Curated Parquet files with schema enforcement, timestamp normalization, and missing-value handling.  
  - Automated Snowflake loading via Snowpipe for analytics-ready querying.  
- 📂 [Project Folder](./streaming_pipeline)  

---

### 🎯 Pinball Maps Batch Data Pipeline
- **Tech:** Apache Airflow, dbt, Snowflake, Docker, REST API  
- **Highlights:**  
  - Airflow DAGs ingest data from the Pinball Maps API into Snowflake.  
  - Config-driven and data-driven DAGs with retries, logging, and error handling.  
  - dbt models structured data into a star schema (fact + dimension tables).  
- 📂 [Project Folder](./batch_pipeline)  

---

## ⚡ Skills Demonstrated
- **Streaming & Batch**: Kafka, Redpanda, Airflow  
- **Data Warehousing**: Snowflake (staging, integration, Snowpipe)  
- **Transformations**: dbt (star schema, fact/dimension modeling)  
- **Cloud & Infra**: AWS S3, Docker, docker-compose  
- **Data Quality**: Schema enforcement, timestamp normalization, missing-value handling  
- **Core Languages**: Python and SQL  

---

## 🚀 Next Steps
- Add automated data quality tests (Great Expectations/dbt tests).  
- Expand ingestion to additional APIs & buoy stations.  
- Implement CI/CD workflows for dbt + Airflow.  

---

📫 Connect with me: [LinkedIn](https://www.linkedin.com/in/wes-martin/) | [Email](mailto:wes.martin713@gmail.com)