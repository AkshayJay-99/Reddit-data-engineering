# 🚀 Reddit Data Pipeline: AWS + Airflow + Glue + Redshift

![Reddit Data Pipeline](![RedditDataEngineering](https://github.com/user-attachments/assets/65111596-a1ac-4d5c-a0e0-969e1a3b6c6d)
)

## Overview 📊

This project implements a complete data pipeline to extract Reddit data and move it through a series of transformations and storage layers using modern data engineering tools. The pipeline is built for scalability, reliability, and analytics-readiness.

---

## ⚙️ What's Happening

- 🌐 Data is extracted from the Reddit API, collecting posts, comments, and metadata from target subreddits.
- 🔄 Apache Airflow orchestrates the pipeline, with Celery executing ETL tasks in parallel.
- 📦 Extracted data is stored in Amazon S3 in a structured format (e.g., JSON or Parquet).
- 🧠 AWS Glue crawlers automatically catalog the data in the AWS Glue Data Catalog.
- 📜 Amazon Athena queries are used to inspect and transform data directly from S3 using SQL.
- 🏢 A Redshift cluster is set up, and cleaned/processed data is loaded into it for analytics, BI tools, or dashboards.
- ✅ Best practices are implemented throughout for efficiency, fault tolerance, and monitoring.

---

## 🛠️ Tech Stack

- **Reddit API** – For data extraction
- **Apache Airflow** – Task orchestration
- **Celery + Redis** – Distributed task execution
- **Amazon S3** – Raw and processed data storage
- **AWS Glue** – Data cataloging and ETL support
- **Amazon Athena** – Serverless SQL querying over S3
- **Amazon Redshift** – Scalable data warehouse for analytics

