# 🚀 100 Real-World Data Engineering Projects (YouTube Edition)

Welcome to the ultimate **Data Engineering Project Portfolio Guide**! This curated list of **100 hands-on projects** is sourced from top data engineering creators on YouTube. Whether you are a beginner building your first ETL script or an experienced engineer designing real-time streaming lakehouses, these projects cover the most in-demand industry domains and modern data stacks.

---

## 📊 Quick Navigation by Category
1. [⚡ Real-Time Streaming & IoT (Kafka, Flink, Spark Streaming)](#-1-real-time-streaming--iot-projects)
2. [☁️ AWS Cloud Data Engineering](#-2-aws-cloud-data-engineering-projects)
3. [🔷 Azure & Microsoft Fabric Data Engineering](#-3-azure--microsoft-fabric-data-engineering-projects)
4. [🌐 Google Cloud Platform (GCP) & BigQuery](#-4-google-cloud-platform-gcp--bigquery-projects)
5. [🧱 Databricks & Lakehouse Architecture](#-5-databricks--lakehouse-architecture-projects)
6. [❄️ Snowflake & dbt (Modern Data Stack)](#-6-snowflake--dbt-modern-data-stack-projects)
7. [🔄 Workflow Orchestration (Airflow, Dagster, Prefect)](#-7-workflow-orchestration-airflow-dagster-prefect)
8. [🦆 Next-Gen & AI Data Engineering (Iceberg, DuckDB, ClickHouse, LLMs)](#-8-next-gen--ai-data-engineering-iceberg-duckdb-llms)

---

## ⚡ 1. Real-Time Streaming & IoT Projects

### 1. Smart City End-to-End Real-Time Data Pipeline
- **📌 Topic / Domain:** IoT & Smart City Telemetry (GPS, Vehicles, Weather, Cameras)
- **🛠️ Tech Stack:** `Apache Kafka` `Spark Streaming` `AWS S3` `AWS Glue` `Athena` `Redshift` `Docker`
- **💡 Project Info:** Simulates a vehicle traveling between cities while capturing real-time IoT sensor data (speed, GPS coordinates, weather conditions, emergency incidents) and streaming it into an AWS Lakehouse for live tracking.
- **📺 YouTube Link:** [Watch Tutorial by CodeWithYu](https://www.youtube.com/watch?v=Vv_fvwF41_0) - https://www.youtube.com/watch?v=Vv_fvwF41_0

### 2. Stock Market Real-Time Data Analysis Using Kafka
- **📌 Topic / Domain:** FinTech & Live Equity Trading
- **🛠️ Tech Stack:** `Python` `Apache Kafka` `AWS EC2` `AWS S3` `AWS Glue` `Amazon Athena`
- **💡 Project Info:** Builds a real-time stock ticker producer that streams market fluctuations through Kafka hosted on EC2, lands raw events in S3, catalogs schemas via Glue, and runs live SQL queries using Athena.
- **📺 YouTube Link:** [Watch Tutorial by Darshil Parmar](https://www.youtube.com/watch?v=KerNf0NANMo) - https://www.youtube.com/watch?v=KerNf0NANMo

### 3. Uber 2026 Streaming Lakehouse Architecture
- **📌 Topic / Domain:** Ride-Sharing & Mobility Analytics
- **🛠️ Tech Stack:** `Azure Databricks` `Spark Structured Streaming` `Delta Live Tables` `Azure Event Hubs`
- **💡 Project Info:** End-to-end streaming architecture handling continuous ride requests, dynamic surge pricing events, and driver telemetry using Azure Databricks and Medallion architecture.
- **📺 YouTube Link:** [Watch Tutorial by Ansh Lamba](https://www.youtube.com/watch?v=5KIbhHo6GJA) - https://www.youtube.com/watch?v=5KIbhHo6GJA

### 4. End-to-End Realtime Data Streaming Pipeline
- **📌 Topic / Domain:** User Generation & Event Driven Architecture
- **🛠️ Tech Stack:** `Apache Airflow` `Python` `Apache Kafka` `Zookeeper` `Spark Streaming` `Cassandra` `Docker`
- **💡 Project Info:** Fetches live user data from an external REST API, orchestrates ingestion via Airflow into Kafka, processes streams using Spark, and writes low-latency records to Apache Cassandra.
- **📺 YouTube Link:** [Watch Tutorial by CodeWithYu](https://www.youtube.com/watch?v=GqAcTrqKcrY) - https://www.youtube.com/watch?v=GqAcTrqKcrY

### 5. Real-Time E-Commerce Event Streaming Pipeline
- **📌 Topic / Domain:** Retail & E-Commerce Clickstream/Orders
- **🛠️ Tech Stack:** `Apache Kafka` `Python` `Spark Streaming` `Cloud Storage`
- **💡 Project Info:** Captures live customer cart additions, checkouts, and payment events in real time to detect abandoned carts and calculate rolling revenue metrics.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](https://www.youtube.com/watch?v=e9GMjtayUnM) - https://www.youtube.com/watch?v=e9GMjtayUnM

### 6. Smart Grid Real-Time Energy Telemetry Project
- **📌 Topic / Domain:** Energy & Utilities IoT
- **🛠️ Tech Stack:** `Apache Kafka` `Apache Flink` `PostgreSQL` `Docker` `Python`
- **💡 Project Info:** Processes high-throughput smart meter power consumption readings using stateful stream processing in Apache Flink to detect grid overload anomalies in real time.
- **📺 YouTube Link:** [Watch Tutorial by CodeWithKaush](https://www.youtube.com/watch?v=Suot7_-FVPY) - https://www.youtube.com/watch?v=Suot7_-FVPY

### 7. Real-Time Streaming with Apache Flink
- **📌 Topic / Domain:** Financial Transactions & Fraud Detection
- **🛠️ Tech Stack:** `Apache Flink` `Apache Kafka` `Elasticsearch` `Kibana` `Docker`
- **💡 Project Info:** Demonstrates low-latency event-driven processing using Flink and Kafka to aggregate streaming transactions and visualize live operational metrics in Kibana.
- **📺 YouTube Link:** [Watch Tutorial by CodeWithYu](https://www.youtube.com/watch?v=deepQRXnniM) - https://www.youtube.com/watch?v=deepQRXnniM

### 8. End-to-End Spark Streaming with Real-Time Dashboard
- **📌 Topic / Domain:** Live Operational BI & Streaming
- **🛠️ Tech Stack:** `Databricks` `Apache Kafka` `PostgreSQL` `Spark Structured Streaming`
- **💡 Project Info:** Connects a Kafka event bus to Databricks Structured Streaming, performs windowed aggregations, sinks results into PostgreSQL, and powers a real-time analytics dashboard.
- **📺 YouTube Link:** [Watch Tutorial by DataBeli](https://www.youtube.com/watch?v=SsE5ZfxtiOI) - https://www.youtube.com/watch?v=SsE5ZfxtiOI

### 9. Spark, Kafka & Cassandra Streaming Pipeline
- **📌 Topic / Domain:** NoSQL High-Velocity Ingestion
- **🛠️ Tech Stack:** `Apache Spark` `Apache Kafka` `Apache Cassandra` `Scala/Python`
- **💡 Project Info:** Focuses on integrating distributed message queues with wide-column NoSQL storage for high-write-throughput applications.
- **📺 YouTube Link:** [Watch Tutorial by Data Engineering](https://www.youtube.com/watch?v=wNnTNTVdglM) - https://www.youtube.com/watch?v=wNnTNTVdglM

### 10. Master Real-Time Pipelines with Kafka & Flink Bootcamp Project
- **📌 Topic / Domain:** Web Traffic & Sessionization
- **🛠️ Tech Stack:** `Apache Kafka` `Apache Flink` `PostgreSQL` `SQL`
- **💡 Project Info:** A comprehensive 3-hour project course building stateful Flink jobs that sessionize web traffic events and compute real-time user engagement metrics.
- **📺 YouTube Link:** [Watch Tutorial by DataExpert](https://www.youtube.com/watch?v=dzB0HMtMIfI) - https://www.youtube.com/watch?v=dzB0HMtMIfI

### 11. Real-Time Data Streaming Pipeline with Kafka, Spark & Elasticsearch
- **📌 Topic / Domain:** Search Indexing & Real-Time Log Telemetry
- **🛠️ Tech Stack:** `Apache Kafka` `Apache Spark` `Elasticsearch` `Kibana` `Docker`
- **💡 Project Info:** Builds an end-to-end streaming architecture that ingests high-velocity event streams via Kafka, transforms payloads with Spark Structured Streaming, and indexes records into Elasticsearch for real-time visualization.
- **📺 YouTube Link:** [Watch Tutorial by Ceyhun Akar | Data Engineering](http://www.youtube.com/watch?v=RQ7nnobb1N0) - http://www.youtube.com/watch?v=RQ7nnobb1N0

### 12. Spotify Real-Time Audio & Listener Data Analysis
- **📌 Topic / Domain:** Music Streaming Telemetry & User Activity
- **🛠️ Tech Stack:** `Spotify API` `Apache Kafka` `PySpark` `Cloud Storage` `Python`
- **💡 Project Info:** Streams live user playback events and track metadata to compute real-time top charts, genre trends, and listener engagement metrics.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](http://www.youtube.com/watch?v=_Ug5yTW5X4U) - http://www.youtube.com/watch?v=_Ug5yTW5X4U

### 13. Real-Time Streaming Pipeline with Kafka, Flink & Postgres
- **📌 Topic / Domain:** Event-Driven Microservices & Stateful Stream Processing
- **🛠️ Tech Stack:** `Apache Kafka` `Apache Flink` `PostgreSQL` `Docker` `Java/Python`
- **💡 Project Info:** Implements a low-latency streaming pipeline capturing continuous event streams in Kafka, performing stateful aggregations in Apache Flink, and sinking analytical tables into PostgreSQL.
- **📺 YouTube Link:** [Watch Tutorial by ByteCoach](http://www.youtube.com/watch?v=FoypLT2W91c) - http://www.youtube.com/watch?v=FoypLT2W91c

### 14. Kafka + Debezium Change Data Capture (CDC) to Medallion Lake
- **📌 Topic / Domain:** Database Change Data Capture (CDC) & Lakehouse Replication
- **🛠️ Tech Stack:** `Apache Kafka` `Debezium` `PostgreSQL` `Medallion Architecture` `Docker`
- **💡 Project Info:** Captures row-level database operations (`INSERT`, `UPDATE`, `DELETE`) from transactional tables in real time using Debezium connectors and propagates changes across Bronze, Silver, and Gold layers.
- **📺 YouTube Link:** [Watch Tutorial by ITumeleng Shange](http://www.youtube.com/watch?v=BgOF3QT9zoM) - http://www.youtube.com/watch?v=BgOF3QT9zoM

### 15. Real-Time Data Pipeline with Amazon MSK (Managed Kafka)
- **📌 Topic / Domain:** Cloud-Managed Event Streaming on AWS
- **🛠️ Tech Stack:** `Amazon MSK` `Apache Kafka` `AWS S3` `AWS Glue` `Python`
- **💡 Project Info:** Configures and deploys a production-ready Apache Kafka cluster using Amazon Managed Streaming for Apache Kafka (MSK) to ingest and route real-time cloud telemetry.
- **📺 YouTube Link:** [Watch Tutorial by AWS Made Easy](http://www.youtube.com/watch?v=G87fm-tjhmY) - http://www.youtube.com/watch?v=G87fm-tjhmY

### 16. Debezium CDC Pipeline: PostgreSQL to Kafka Hands-On
- **📌 Topic / Domain:** Real-Time Transactional Log Tailing
- **🛠️ Tech Stack:** `Debezium` `PostgreSQL` `Apache Kafka` `Kafka Connect` `Docker`
- **💡 Project Info:** Demonstrates three practical methods to configure Debezium CDC with PostgreSQL write-ahead logs (WAL) to stream database mutations into Kafka topics with zero data loss.
- **📺 YouTube Link:** [Watch Tutorial by Khanh Nguyen J](http://www.youtube.com/watch?v=updVdEuQvcE) - http://www.youtube.com/watch?v=updVdEuQvcE

### 17. Kafka Crash Course & Hands-On Microservices Streaming Project
- **📌 Topic / Domain:** Distributed Messaging & Event-Driven Systems
- **🛠️ Tech Stack:** `Apache Kafka` `Python / Node.js` `Docker` `Kafka CLI`
- **💡 Project Info:** Builds a multi-service producer/consumer application from scratch, demonstrating topic partitioning, consumer groups, offset management, and fault-tolerant message delivery.
- **📺 YouTube Link:** [Watch Tutorial by TechWorld with Nana](http://www.youtube.com/watch?v=B7CwU_tNYIE) - http://www.youtube.com/watch?v=B7CwU_tNYIE

---

## ☁️ 2. AWS Cloud Data Engineering Projects

### 18. YouTube Trending Video Analytics on AWS
- **📌 Topic / Domain:** Social Media & Content Analytics
- **🛠️ Tech Stack:** `AWS S3` `AWS Glue` `AWS Lambda` `Amazon Athena` `Amazon QuickSight` `IAM`
- **💡 Project Info:** Ingests multi-region YouTube trending datasets (JSON & CSV), triggers serverless Lambda functions to convert raw data into Parquet, catalogs tables in Glue, and builds executive dashboards in QuickSight.
- **📺 YouTube Link:** [Watch Tutorial by Darshil Parmar](https://www.youtube.com/watch?v=yZKJFKu49Dk) - https://www.youtube.com/watch?v=yZKJFKu49Dk

### 19. Reddit Data Pipeline Engineering on AWS
- **📌 Topic / Domain:** Social Media Sentiment & Community Trends
- **🛠️ Tech Stack:** `Reddit API` `Apache Airflow` `Celery` `PostgreSQL` `AWS S3` `AWS Glue` `Athena` `Redshift`
- **💡 Project Info:** Extracts top subreddit posts via the Reddit API using Airflow, stages raw data in S3, transforms structures with AWS Glue, and loads curated tables into Amazon Redshift.
- **📺 YouTube Link:** [Watch Tutorial by CodeWithYu](https://www.youtube.com/watch?v=LSlt6iVI_9Y) - https://www.youtube.com/watch?v=LSlt6iVI_9Y

### 20. Superstore Retail Analytics on AWS
- **📌 Topic / Domain:** Retail & Supply Chain Analytics
- **🛠️ Tech Stack:** `AWS S3` `AWS Glue` `Athena` `PySpark` `SQL`
- **💡 Project Info:** Beginner-friendly end-to-end AWS cloud pipeline that takes raw retail sales data, cleanses and models it using PySpark in AWS Glue, and performs analytical reporting.
- **📺 YouTube Link:** [Watch Tutorial by Ankit Bansal](https://www.youtube.com/watch?v=52CWagk3-jw) - https://www.youtube.com/watch?v=52CWagk3-jw

### 21. End-to-End AWS Cloud & PySpark Pipeline in 40 Minutes
- **📌 Topic / Domain:** E-Commerce Customer Analytics
- **🛠️ Tech Stack:** `AWS S3` `EMR / Glue` `PySpark` `Redshift`
- **💡 Project Info:** Fast-paced, practical project demonstrating how to write production-grade PySpark transformations on AWS cloud storage and expose clean marts for BI tools.
- **📺 YouTube Link:** [Watch Tutorial by Date with Data](https://www.youtube.com/watch?v=yIc5a7C8aHs) - https://www.youtube.com/watch?v=yIc5a7C8aHs

### 22. AWS Masterclass Data Engineering Pipeline
- **📌 Topic / Domain:** Enterprise Cloud Data Warehousing
- **🛠️ Tech Stack:** `AWS S3` `AWS Glue` `AWS Lambda` `Step Functions` `Redshift`
- **💡 Project Info:** Covers the core AWS data engineering ecosystem from scratch, culminating in an automated serverless ETL pipeline with orchestration and monitoring.
- **📺 YouTube Link:** [Watch Tutorial by Darshil Parmar](https://www.youtube.com/watch?v=yvAWbbQa8eE) - https://www.youtube.com/watch?v=yvAWbbQa8eE

### 23. Serverless Data Pipeline on AWS
- **📌 Topic / Domain:** Automated File Processing
- **🛠️ Tech Stack:** `AWS S3` `AWS Lambda` `AWS Glue` `Amazon Athena`
- **💡 Project Info:** Demonstrates event-driven data engineering where file uploads to S3 automatically trigger transformation workflows without managing any servers.
- **📺 YouTube Link:** [Watch Tutorial by learn by doing it](https://www.youtube.com/watch?v=UUyzdduUN_8) - https://www.youtube.com/watch?v=UUyzdduUN_8

### 24. Production-Grade AWS Data Engineering Portfolio Project
- **📌 Topic / Domain:** Full-Stack Cloud Data Architecture
- **🛠️ Tech Stack:** `AWS S3` `IAM` `Glue` `PySpark` `Athena` `CI/CD`
- **💡 Project Info:** Walks through security, IAM roles, partitioning strategies, and cost-effective query optimization required in real enterprise AWS environments.
- **📺 YouTube Link:** [Watch Tutorial by Data Engineer Academy](https://www.youtube.com/watch?v=BjUgDWbF1Rs) - https://www.youtube.com/watch?v=BjUgDWbF1Rs

### 25. Cloud Data Warehouse with AWS Glue, S3 & Amazon Redshift
- **📌 Topic / Domain:** Enterprise Cloud Data Warehousing
- **🛠️ Tech Stack:** `AWS Glue` `AWS S3` `Amazon Redshift` `PySpark` `IAM`
- **💡 Project Info:** Designs and implements an end-to-end dimensional data warehouse on AWS by extracting raw files from S3, running PySpark ETL jobs in Glue, and loading star-schema tables into Redshift.
- **📺 YouTube Link:** [Watch Tutorial by DSwithBappy](http://www.youtube.com/watch?v=ww2dhCYqJNI) - http://www.youtube.com/watch?v=ww2dhCYqJNI

### 26. Serverless AWS Data Pipeline with S3, Lambda, Glue & QuickSight
- **📌 Topic / Domain:** Event-Driven Cloud BI & Reporting
- **🛠️ Tech Stack:** `AWS S3` `AWS Lambda` `AWS Glue` `Amazon QuickSight` `Python`
- **💡 Project Info:** Automates data ingestion and transformation using event-driven AWS Lambda triggers, Glue crawlers, and interactive QuickSight business intelligence dashboards.
- **📺 YouTube Link:** [Watch Tutorial by Tech With Yeshwanth](http://www.youtube.com/watch?v=qntqGk3zgXw) - http://www.youtube.com/watch?v=qntqGk3zgXw

### 27. Infrastructure-as-Code AWS ETL Pipeline with Terraform
- **📌 Topic / Domain:** DevOps & Reproducible Cloud Data Infrastructure
- **🛠️ Tech Stack:** `Terraform` `AWS Glue` `AWS S3` `Amazon Athena` `PySpark`
- **💡 Project Info:** Provisions an entire production-ready AWS ETL pipeline (S3 buckets, IAM policies, Glue jobs, and Athena workgroups) declaratively using Terraform Infrastructure-as-Code (IaC).
- **📺 YouTube Link:** [Watch Tutorial by KloudRank](http://www.youtube.com/watch?v=wg_otl9Wc50) - http://www.youtube.com/watch?v=wg_otl9Wc50

### 28. AWS Real-Time Streaming Ingestion with Kinesis & Firehose
- **📌 Topic / Domain:** Real-Time Cloud Log & Event Ingestion
- **🛠️ Tech Stack:** `Amazon Kinesis Data Streams` `Kinesis Firehose` `AWS S3` `Amazon Redshift`
- **💡 Project Info:** Captures real-time streaming data using Amazon Kinesis, buffers and transforms records on the fly with Firehose, and delivers curated datasets into S3 and Redshift.
- **📺 YouTube Link:** [Watch Tutorial by Md Musfikur Rahman](http://www.youtube.com/watch?v=VZ0LsBzQb4Y) - http://www.youtube.com/watch?v=VZ0LsBzQb4Y

### 29. Airlines Data Ingestion & Processing Pipeline on AWS
- **📌 Topic / Domain:** Aviation Operations & Flight Delay Analytics
- **🛠️ Tech Stack:** `AWS S3` `AWS Glue` `AWS Step Functions` `Amazon Redshift` `Athena`
- **💡 Project Info:** Processes large-scale airline booking and flight telemetry datasets using orchestrated AWS Step Functions, Glue PySpark jobs, and Redshift warehousing.
- **📺 YouTube Link:** [Watch Tutorial by GrowDataSkills](http://www.youtube.com/watch?v=35Du026h-KY) - http://www.youtube.com/watch?v=35Du026h-KY

### 30. Transactional Data Lake on AWS S3 with Apache Hudi & Glue
- **📌 Topic / Domain:** Upsert-Heavy Data Lakes & Open Table Formats
- **🛠️ Tech Stack:** `Apache Hudi` `AWS Glue` `AWS S3` `PySpark` `Amazon Athena`
- **💡 Project Info:** Builds an ACID-compliant transactional data lake on S3 using Apache Hudi and AWS Glue to handle record-level upserts, deletes, and incremental queries.
- **📺 YouTube Link:** [Watch Tutorial by Soumil Shah](http://www.youtube.com/watch?v=5zF4jc_3rFs) - http://www.youtube.com/watch?v=5zF4jc_3rFs

---

## 🔷 3. Azure & Microsoft Fabric Data Engineering Projects

### 31. Spotify End-to-End Azure Data Engineering Project
- **📌 Topic / Domain:** Music Streaming & Listener Analytics
- **🛠️ Tech Stack:** `Azure Data Factory (ADF)` `Azure Data Lake Gen2` `Azure Databricks` `Synapse Analytics` `PySpark`
- **💡 Project Info:** Builds a complete Medallion architecture (Bronze, Silver, Gold) processing music streaming metadata, artist popularity, and user listening habits on Azure.
- **📺 YouTube Link:** [Watch Tutorial by Ansh Lamba](https://www.youtube.com/watch?v=vJM0wDrTRxI) - https://www.youtube.com/watch?v=vJM0wDrTRxI

### 32. Enterprise Azure Data Engineering Project (From Scratch)
- **📌 Topic / Domain:** Retail & Enterprise ERP Migration
- **🛠️ Tech Stack:** `Azure Data Factory` `ADLS Gen2` `Azure Databricks` `Azure Synapse` `Power BI`
- **💡 Project Info:** Ingests on-premise/API data using ADF, transforms raw datasets via PySpark in Databricks using Delta Lake formats, and serves star-schema models via Synapse to Power BI.
- **📺 YouTube Link:** [Watch Tutorial by Ansh Lamba](https://www.youtube.com/watch?v=0GTZ-12hYtU) - https://www.youtube.com/watch?v=0GTZ-12hYtU

### 33. CI/CD Driven Azure Data Engineering Project with Azure DevOps
- **📌 Topic / Domain:** DevOps & Production Data Pipelines
- **🛠️ Tech Stack:** `Azure DevOps` `Git` `Azure Data Factory` `Azure Databricks` `Key Vault` `ADLS Gen2`
- **💡 Project Info:** Goes beyond basic ETL by implementing enterprise security with Azure Key Vault and automated CI/CD release pipelines across Dev, QA, and Prod environments.
- **📺 YouTube Link:** [Watch Tutorial by Ansh Lamba](https://www.youtube.com/watch?v=ESWqAZP2qA4) - https://www.youtube.com/watch?v=ESWqAZP2qA4

### 34. End-to-End Azure Data Engineering Project by Sumit Sir
- **📌 Topic / Domain:** E-Commerce & Financial Reporting
- **🛠️ Tech Stack:** `Azure Data Factory` `Azure Databricks` `Delta Lake` `Azure Synapse`
- **💡 Project Info:** A comprehensive 5.5-hour masterclass project covering incremental data loading, Slowly Changing Dimensions (SCD), and Unity Catalog governance on Azure.
- **📺 YouTube Link:** [Watch Tutorial by Sumit Mittal](https://www.youtube.com/watch?v=d3Vw3VtKDnc) - https://www.youtube.com/watch?v=d3Vw3VtKDnc

### 35. Azure Data Pipeline: ADF + Databricks + Power BI
- **📌 Topic / Domain:** Sales & Executive BI Reporting
- **🛠️ Tech Stack:** `Azure Data Factory` `Azure Databricks` `PySpark` `Power BI`
- **💡 Project Info:** Connects transactional data sources into ADLS, runs automated PySpark notebooks via ADF pipelines, and builds interactive Power BI dashboards.
- **📺 YouTube Link:** [Watch Tutorial by learn by doing it](https://www.youtube.com/watch?v=rmjVNPJhMXs) - https://www.youtube.com/watch?v=rmjVNPJhMXs

### 36. Beginner Azure SQL to Data Lake Pipeline (Free Account)
- **📌 Topic / Domain:** Database Replication & Cloud Migration
- **🛠️ Tech Stack:** `Azure SQL Database` `Azure Data Factory` `ADLS Gen2` `Databricks`
- **💡 Project Info:** Designed specifically to run within the Azure Free Tier, showing how to provision SQL databases, configure ADF linked services, and automate cloud migrations.
- **📺 YouTube Link:** [Watch Tutorial by Luke Byrne (AI Luke)](https://www.youtube.com/watch?v=ygJ11fzq_ik) - https://www.youtube.com/watch?v=ygJ11fzq_ik

### 37. Real Estate Property Valuation Trends on Azure
- **📌 Topic / Domain:** Real Estate & Housing Market Analytics
- **🛠️ Tech Stack:** `Azure Data Factory` `Azure Databricks` `Power BI` `ADLS Gen2`
- **💡 Project Info:** Analyzes property valuation trends, regional price indices, and historical sales data using Azure's modern data warehouse stack.
- **📺 YouTube Link:** [Watch Tutorial by Om Bijwani](https://www.youtube.com/watch?v=uwrSEthOolU) - https://www.youtube.com/watch?v=uwrSEthOolU

### 38. Microsoft Fabric Real-Time Stock Market Analytics
- **📌 Topic / Domain:** SaaS Lakehouse & Financial Analytics
- **🛠️ Tech Stack:** `Microsoft Fabric` `OneLake` `Eventstreams` `KQL Database` `Power BI DirectLake`
- **💡 Project Info:** Showcases Microsoft Fabric's unified analytics platform by ingesting real-time stock market feeds into OneLake and visualizing them instantly via DirectLake mode.
- **📺 YouTube Link:** [Watch Tutorial by DataCraft with Chitwinder](https://www.youtube.com/watch?v=gBNodr-A60I) - https://www.youtube.com/watch?v=gBNodr-A60I

### 39. E-Commerce Lakehouse on Azure Databricks
- **📌 Topic / Domain:** Online Retail & Customer Retention
- **🛠️ Tech Stack:** `Azure Databricks` `ADLS Gen2` `Delta Lake` `PySpark` `Spark SQL`
- **💡 Project Info:** Implements Bronze, Silver, and Gold layers for an e-commerce platform to track customer lifetime value (CLV), product return rates, and regional sales performance.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](https://www.youtube.com/watch?v=H9cK7ELbjLg) - https://www.youtube.com/watch?v=H9cK7ELbjLg

### 40. Enterprise Azure Pipeline with GitHub CI/CD, Logic Apps & Key Vault
- **📌 Topic / Domain:** Automated Enterprise Cloud Security & Alerting
- **🛠️ Tech Stack:** `Azure Data Factory` `Azure Databricks` `GitHub Actions` `Azure Logic Apps` `Azure Key Vault`
- **💡 Project Info:** Builds a 5.5-hour production-grade Azure data pipeline featuring automated failure email alerts via Logic Apps, secret management in Key Vault, and GitHub CI/CD integration.
- **📺 YouTube Link:** [Watch Tutorial by DataBeli](http://www.youtube.com/watch?v=MFK7M9RS85I) - http://www.youtube.com/watch?v=MFK7M9RS85I

### 41. End-to-End Azure ETL: On-Prem SQL to ADLS, Databricks & Synapse
- **📌 Topic / Domain:** Hybrid Cloud Database Migration
- **🛠️ Tech Stack:** `SQL Server` `Azure Data Factory` `ADLS Gen2` `Azure Databricks` `Azure Synapse` `Power BI`
- **💡 Project Info:** Walks through migrating relational SQL databases into Azure Data Lake using ADF, transforming tables across Medallion layers in Databricks, and serving reports in Power BI.
- **📺 YouTube Link:** [Watch Tutorial by DataToCrunch](http://www.youtube.com/watch?v=XYQU5ZMuMuE) - http://www.youtube.com/watch?v=XYQU5ZMuMuE

### 42. Healthcare Analytics Pipeline on Azure Databricks & Data Factory
- **📌 Topic / Domain:** Clinical Operations & Patient Claims Analytics
- **🛠️ Tech Stack:** `Azure Data Factory` `Azure Databricks` `PySpark` `Delta Lake` `ADLS Gen2`
- **💡 Project Info:** Ingests and standardizes multi-source healthcare datasets (patient admissions, medical billing, provider networks) into a governed Azure Lakehouse architecture.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](http://www.youtube.com/watch?v=01LVHch-1x0) - http://www.youtube.com/watch?v=01LVHch-1x0

### 43. End-to-End Microsoft Fabric Lakehouse & Data Factory Project
- **📌 Topic / Domain:** Unified SaaS Analytics & Medallion Lakehouse
- **🛠️ Tech Stack:** `Microsoft Fabric` `OneLake` `Fabric Data Factory` `Spark Notebooks` `Power BI`
- **💡 Project Info:** Builds a complete Lakehouse in Microsoft Fabric from scratch, combining Fabric pipelines, PySpark notebook transformations, and DirectLake semantic models.
- **📺 YouTube Link:** [Watch Tutorial by Pathfinder Analytics](http://www.youtube.com/watch?v=Av44Nrhl05s) - http://www.youtube.com/watch?v=Av44Nrhl05s

### 44. Azure Synapse Analytics Full Course & End-to-End Project
- **📌 Topic / Domain:** Serverless & Dedicated SQL Pool Data Warehousing
- **🛠️ Tech Stack:** `Azure Synapse Analytics` `Synapse Pipelines` `ADLS Gen2` `Spark Pools` `SQL`
- **💡 Project Info:** Covers the entire Azure Synapse ecosystem by building an end-to-end data warehouse utilizing both serverless SQL pools for ad-hoc exploration and dedicated pools for BI.
- **📺 YouTube Link:** [Watch Tutorial by learn by doing it](http://www.youtube.com/watch?v=cxefJazlYkY) - http://www.youtube.com/watch?v=cxefJazlYkY

### 45. Beginner Azure Synapse Data Engineering Project (Free Tier)
- **📌 Topic / Domain:** Cost-Effective Cloud Data Warehousing
- **🛠️ Tech Stack:** `Azure Synapse Analytics` `ADLS Gen2` `SQL` `Power BI`
- **💡 Project Info:** Demonstrates how to architect and deploy a complete Azure Synapse pipeline and analytical reporting layer while staying within Azure free account limits.
- **📺 YouTube Link:** [Watch Tutorial by Luke Byrne (AI Luke)](http://www.youtube.com/watch?v=P00UEQR2coM) - http://www.youtube.com/watch?v=P00UEQR2coM

---

## 🌐 4. Google Cloud Platform (GCP) & BigQuery Projects

### 46. Uber Data Analytics End-to-End Project on GCP
- **📌 Topic / Domain:** Mobility & Trip Fare Analytics
- **🛠️ Tech Stack:** `Google Cloud Storage (GCS)` `Mage AI` `Compute Engine` `BigQuery` `Looker Studio` `Python`
- **💡 Project Info:** Models raw NYC TLC / Uber trip records into a dimensional star schema (Fact & Dimension tables), orchestrates transformations using Mage on GCP, and visualizes KPIs in Looker Studio.
- **📺 YouTube Link:** [Watch Tutorial by Darshil Parmar](https://www.youtube.com/watch?v=WpQECq5Hx9g) - https://www.youtube.com/watch?v=WpQECq5Hx9g

### 47. Real-Time Healthcare Data Engineering Project on GCP
- **📌 Topic / Domain:** Healthcare & Electronic Health Records (EHR)
- **🛠️ Tech Stack:** `GCP Cloud Storage` `Dataproc` `PySpark` `BigQuery` `Cloud Composer (Airflow)`
- **💡 Project Info:** Handles sensitive healthcare patient records, insurance claims, and hospital admission workflows using GCP's native big data processing and warehousing tools.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](https://www.youtube.com/watch?v=r8dalB4A5ko) - https://www.youtube.com/watch?v=r8dalB4A5ko

### 48. GCP & Apache Airflow Automated Data Pipeline
- **📌 Topic / Domain:** Automated Cloud Batch ETL
- **🛠️ Tech Stack:** `Google Cloud Platform` `Apache Airflow` `BigQuery` `Cloud Storage` `Python`
- **💡 Project Info:** Demonstrates how to orchestrate multi-step data ingestion and transformation tasks landing into Google BigQuery using Apache Airflow operators.
- **📺 YouTube Link:** [Watch Tutorial by GrowDataSkills](https://www.youtube.com/watch?v=IBydayIGCbQ) - https://www.youtube.com/watch?v=IBydayIGCbQ

### 49. Legacy Talend to GCP Cloud Data Migration Project
- **📌 Topic / Domain:** Legacy ETL Modernization
- **🛠️ Tech Stack:** `Talend` `Google Cloud Storage` `BigQuery` `Cloud Dataflow` `SQL`
- **💡 Project Info:** Simulates a real-world enterprise migration project moving legacy on-premise Talend ETL workflows into scalable Google Cloud native pipelines.
- **📺 YouTube Link:** [Watch Tutorial by Shubham Wadekar](https://www.youtube.com/watch?v=uytORh6ZACU) - https://www.youtube.com/watch?v=uytORh6ZACU

### 50. Streaming Data Pipeline with Cloud Pub/Sub, Dataflow & BigQuery
- **📌 Topic / Domain:** Serverless Real-Time Cloud Streaming
- **🛠️ Tech Stack:** `Google Cloud Pub/Sub` `Cloud Dataflow (Apache Beam)` `BigQuery`
- **💡 Project Info:** Builds a zero-ops serverless streaming pipeline on GCP where Pub/Sub messages are continuously processed by Apache Beam runners on Dataflow and streamed into BigQuery.
- **📺 YouTube Link:** [Watch Tutorial by TechTrapture](https://www.youtube.com/watch?v=Unbx59eHL5I) - https://www.youtube.com/watch?v=Unbx59eHL5I

### 51. Complete PySpark ETL Pipeline on GCP Dataproc
- **📌 Topic / Domain:** Distributed Batch Processing on GCP
- **🛠️ Tech Stack:** `GCP Dataproc` `PySpark` `Google Cloud Storage` `BigQuery`
- **💡 Project Info:** Provisions managed Spark clusters on GCP Dataproc to process large-scale datasets from GCS buckets and write aggregated outputs directly to BigQuery tables.
- **📺 YouTube Link:** [Watch Tutorial by Data Engineering With KD](https://www.youtube.com/watch?v=d39hSL9IvEY) - https://www.youtube.com/watch?v=d39hSL9IvEY

### 52. IRCTC Real-Time Railway Data Pipeline on Google Cloud
- **📌 Topic / Domain:** Railway Ticketing & Live Train Telemetry
- **🛠️ Tech Stack:** `Google Cloud Pub/Sub` `Cloud Dataflow` `BigQuery` `Google Cloud Storage` `Python`
- **💡 Project Info:** Simulates live Indian Railways (IRCTC) ticket bookings, PNR status updates, and train delay events streaming through GCP Pub/Sub and Dataflow into BigQuery.
- **📺 YouTube Link:** [Watch Tutorial by GrowDataSkills](http://www.youtube.com/watch?v=1miroeyFqls) - http://www.youtube.com/watch?v=1miroeyFqls

### 53. End-to-End GCP Pipeline with Cloud Composer, Dataflow & Looker
- **📌 Topic / Domain:** Event-Driven Cloud Warehousing & BI
- **🛠️ Tech Stack:** `Cloud Composer (Airflow)` `Cloud Functions` `GCS` `Cloud Dataflow` `BigQuery` `Looker`
- **💡 Project Info:** Integrates serverless Cloud Functions and Apache Airflow on GCP to trigger Dataflow batch jobs, populate BigQuery marts, and power Looker dashboards.
- **📺 YouTube Link:** [Watch Tutorial by SkillVane Trainings](http://www.youtube.com/watch?v=_AZxCuD1EUw) - http://www.youtube.com/watch?v=_AZxCuD1EUw

### 54. Orchestrated GCP Data Pipeline with Airflow, Dataproc & BigQuery
- **📌 Topic / Domain:** Managed Spark Orchestration on GCP
- **🛠️ Tech Stack:** `Apache Airflow` `GCP Dataproc` `PySpark` `BigQuery` `Google Cloud Storage`
- **💡 Project Info:** Automates the spin-up of ephemeral GCP Dataproc Spark clusters via Airflow DAGs, executes PySpark transformations, and loads curated tables into BigQuery.
- **📺 YouTube Link:** [Watch Tutorial by PathNex - Shaping Careers](http://www.youtube.com/watch?v=6wKtDocNPpY) - http://www.youtube.com/watch?v=6wKtDocNPpY

### 55. Quality-Checked ELT Pipeline with BigQuery, Airflow, dbt & Soda
- **📌 Topic / Domain:** Data Quality Engineering & Observability on GCP
- **🛠️ Tech Stack:** `Google BigQuery` `Apache Airflow` `dbt` `Soda Core` `Docker`
- **💡 Project Info:** Implements automated data quality assertions and schema checks using Soda Core alongside dbt transformations and Airflow orchestration on Google BigQuery.
- **📺 YouTube Link:** [Watch Tutorial by Data with Marc](http://www.youtube.com/watch?v=DzxtCxi4YaA) - http://www.youtube.com/watch?v=DzxtCxi4YaA

### 56. Zero-to-Hero dbt Cloud & Google BigQuery Data Pipeline
- **📌 Topic / Domain:** Cloud Analytics Engineering on GCP
- **🛠️ Tech Stack:** `dbt Cloud` `Google BigQuery` `SQL` `Jinja` `Git`
- **💡 Project Info:** Connects dbt Cloud directly to Google BigQuery to build modular staging and dimensional models, automated tests, and scheduled production jobs.
- **📺 YouTube Link:** [Watch Tutorial by CK Data Tech](http://www.youtube.com/watch?v=Zl6OVJdqAc8) - http://www.youtube.com/watch?v=Zl6OVJdqAc8

### 57. Hybrid Streaming Pipeline: GCP, Kafka, PySpark & Airflow
- **📌 Topic / Domain:** Distributed Streaming & Cloud Orchestration
- **🛠️ Tech Stack:** `Google Cloud Platform` `Apache Kafka` `PySpark` `Apache Airflow` `BigQuery`
- **💡 Project Info:** Combines open-source Kafka streaming and PySpark processing with GCP storage and BigQuery warehousing under unified Airflow orchestration.
- **📺 YouTube Link:** [Watch Tutorial by ruthvik_yadav](http://www.youtube.com/watch?v=Cb2BpFoL30g) - http://www.youtube.com/watch?v=Cb2BpFoL30g

---

## 🧱 5. Databricks & Lakehouse Architecture Projects

### 58. FMCG Domain Lakehouse Using Databricks Free Edition
- **📌 Topic / Domain:** Fast-Moving Consumer Goods (Supply Chain & OTIF Metrics)
- **🛠️ Tech Stack:** `Databricks Free Edition` `PySpark` `Delta Lake` `Spark SQL` `Medallion Architecture`
- **💡 Project Info:** Built around a realistic FMCG business scenario where a company acquires a smaller competitor and needs to consolidate messy supply chain data into a unified Lakehouse without needing a paid cloud credit card.
- **📺 YouTube Link:** [Watch Tutorial by codebasics](https://www.youtube.com/watch?v=U6ZUKWdfSLY) - https://www.youtube.com/watch?v=U6ZUKWdfSLY

### 59. Finance Domain End-to-End Project in Databricks
- **📌 Topic / Domain:** Banking, Loans & Credit Risk Analytics
- **🛠️ Tech Stack:** `Databricks` `PySpark` `Delta Lake` `Unity Catalog` `SQL`
- **💡 Project Info:** Processes banking transactions, loan repayments, and customer credit profiles across Bronze, Silver, and Gold layers with full source code included.
- **📺 YouTube Link:** [Watch Tutorial by DataBeli](https://www.youtube.com/watch?v=aEGan35iBbE) - https://www.youtube.com/watch?v=aEGan35iBbE

### 60. Full End-to-End Data Engineering Project in Databricks
- **📌 Topic / Domain:** Data Lakehouse Fundamentals
- **🛠️ Tech Stack:** `Databricks` `PySpark` `Delta Tables` `Notebooks` `Dashboards`
- **💡 Project Info:** A concise, high-impact walkthrough taking raw data files, transforming them through a structured Lakehouse pipeline, and building native Databricks visualizations.
- **📺 YouTube Link:** [Watch Tutorial by Alex The Analyst](https://www.youtube.com/watch?v=SSz7HiyQN1M) - https://www.youtube.com/watch?v=SSz7HiyQN1M

### 61. Live Cricket API Data Engineering Project with PySpark
- **📌 Topic / Domain:** Sports Analytics & Live Match Telemetry
- **🛠️ Tech Stack:** `REST API` `Python` `PySpark` `Databricks` `Delta Lake`
- **💡 Project Info:** Fetches live cricket match scores, player statistics, and ball-by-ball commentary from a sports API and flattens complex nested JSON structures using PySpark.
- **📺 YouTube Link:** [Watch Tutorial by Be a Programmer](https://www.youtube.com/watch?v=XYG8o5MrvhU) - https://www.youtube.com/watch?v=XYG8o5MrvhU

### 62. World Wide Importers (WWI) Medallion Architecture Project
- **📌 Topic / Domain:** Wholesale Distribution & Inventory Management
- **🛠️ Tech Stack:** `Databricks` `Spark SQL` `PySpark` `Delta Lake`
- **💡 Project Info:** Implements the classic World Wide Importers enterprise dataset into a modern Bronze-Silver-Gold Lakehouse architecture with incremental merge operations.
- **📺 YouTube Link:** [Watch Tutorial by TechLake](https://www.youtube.com/watch?v=1mUzjlG-d5g) - https://www.youtube.com/watch?v=1mUzjlG-d5g

### 63. Delta Live Tables (DLT) Full Masterclass Project in Databricks
- **📌 Topic / Domain:** Declarative Streaming & CDC Lakehouse Pipelines
- **🛠️ Tech Stack:** `Databricks` `Delta Live Tables (DLT)` `Auto Loader` `PySpark` `Unity Catalog`
- **💡 Project Info:** Builds declarative streaming pipelines using Delta Live Tables (DLT), implementing Auto Loader cloud file ingestion, data quality expectations, and automated Change Data Capture (`APPLY CHANGES INTO`).
- **📺 YouTube Link:** [Watch Tutorial by Ansh Lamba](http://www.youtube.com/watch?v=PhezTpntdyY) - http://www.youtube.com/watch?v=PhezTpntdyY

### 64. Spark Declarative Pipelines Project in Databricks Free Edition
- **📌 Topic / Domain:** Modern Declarative ETL on Databricks
- **🛠️ Tech Stack:** `Databricks Free Edition` `Spark Declarative Pipelines` `Delta Lake` `PySpark` `SQL`
- **💡 Project Info:** Demonstrates how to build reliable, maintainable Bronze-Silver-Gold data pipelines using Spark Declarative Pipelines in Databricks without requiring a paid cloud subscription.
- **📺 YouTube Link:** [Watch Tutorial by codebasics](http://www.youtube.com/watch?v=bIIC44n2Dss) - http://www.youtube.com/watch?v=bIIC44n2Dss

### 65. Multi-Source Retail Lakehouse (Salesforce + Postgres) in Databricks
- **📌 Topic / Domain:** CRM & ERP Data Consolidation
- **🛠️ Tech Stack:** `Databricks Free Edition` `Salesforce` `PostgreSQL` `PySpark` `Delta Lake`
- **💡 Project Info:** Extracts and unifies customer CRM records from Salesforce with transactional order data from PostgreSQL into a centralized Databricks Medallion Lakehouse.
- **📺 YouTube Link:** [Watch Tutorial by DataBeli](http://www.youtube.com/watch?v=QHwszePV3GY) - http://www.youtube.com/watch?v=QHwszePV3GY

### 66. Walmart End-to-End Lakehouse with Airflow, dbt & Databricks
- **📌 Topic / Domain:** Big-Box Retail Inventory & Sales Analytics
- **🛠️ Tech Stack:** `Databricks` `dbt` `Apache Airflow` `PySpark` `Delta Lake`
- **💡 Project Info:** Combines Apache Airflow orchestration with dbt SQL/Jinja transformations running on top of a Databricks Spark SQL warehouse for Walmart retail analytics.
- **📺 YouTube Link:** [Watch Tutorial by Ansh Lamba](http://www.youtube.com/watch?v=ZEE-jNAthB0) - http://www.youtube.com/watch?v=ZEE-jNAthB0

### 67. PySpark x dbt End-to-End Big Data Engineering Project
- **📌 Topic / Domain:** Hybrid Spark & Analytics Engineering
- **🛠️ Tech Stack:** `PySpark` `dbt` `Databricks` `Delta Lake` `SQL`
- **💡 Project Info:** Bridges heavy distributed PySpark data cleansing with modular dbt dimensional modeling and testing in a unified Lakehouse workflow.
- **📺 YouTube Link:** [Watch Tutorial by Ansh Lamba](http://www.youtube.com/watch?v=cq7Uv7ctGjw) - http://www.youtube.com/watch?v=cq7Uv7ctGjw

### 68. Medallion Architecture with Databricks Lakeflow
- **📌 Topic / Domain:** Unified Data Ingestion, Quality & Orchestration
- **🛠️ Tech Stack:** `Databricks Lakeflow` `Delta Lake` `Unity Catalog` `PySpark` `SQL`
- **💡 Project Info:** Uses Databricks Lakeflow to ingest raw data, enforce data quality constraints, compute Gold aggregations, and orchestrate multi-task Lakehouse workflows.
- **📺 YouTube Link:** [Watch Tutorial by Thomas Hass](http://www.youtube.com/watch?v=yy9H4mlOG6I) - http://www.youtube.com/watch?v=yy9H4mlOG6I

### 69. End-to-End Retail Analytics Pipeline Using PySpark
- **📌 Topic / Domain:** Retail Sales, Customer Segmentation & KPIs
- **🛠️ Tech Stack:** `PySpark` `Databricks` `Spark SQL` `Parquet / Delta Lake`
- **💡 Project Info:** Executes end-to-end data cleaning, complex window functions, joins, and aggregations in PySpark to answer critical retail business intelligence questions.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](http://www.youtube.com/watch?v=QAxY2rLz3_o) - http://www.youtube.com/watch?v=QAxY2rLz3_o

---

## ❄️ 6. Snowflake & dbt (Modern Data Stack) Projects

### 70. Stock Market Analytics with Snowflake, dbt & Airflow
- **📌 Topic / Domain:** Financial Market Data Warehousing
- **🛠️ Tech Stack:** `Snowflake` `dbt (Data Build Tool)` `Apache Airflow` `Python` `SQL`
- **💡 Project Info:** Extracts daily market prices via Python, orchestrates loading into Snowflake using Airflow, and runs modular dbt models with automated data quality tests.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](https://www.youtube.com/watch?v=JCDrvXwh4BQ) - https://www.youtube.com/watch?v=JCDrvXwh4BQ

### 71. Healthcare ELT Pipeline: Oracle to Snowflake + dbt (SCD Type 2 & CDC)
- **📌 Topic / Domain:** Healthcare Database Replication & History Tracking
- **🛠️ Tech Stack:** `Oracle DB` `Snowflake` `dbt` `Streams & Tasks` `SQL`
- **💡 Project Info:** Implements Change Data Capture (CDC) and Slowly Changing Dimensions (SCD Type 2) using dbt snapshots and Snowflake to preserve historical patient and provider changes.
- **📺 YouTube Link:** [Watch Tutorial by Time Variant](https://www.youtube.com/watch?v=Eaz2r7mw1hA) - https://www.youtube.com/watch?v=Eaz2r7mw1hA

### 72. Legacy ETL to dbt on Snowflake Migration Project
- **📌 Topic / Domain:** Data Warehouse Modernization
- **🛠️ Tech Stack:** `Snowflake` `dbt Core / Cloud` `SQL` `Jinja` `Git`
- **💡 Project Info:** Shows how to refactor monolithic stored procedures and legacy ETL jobs into clean, version-controlled, testable dbt staging, intermediate, and mart models on Snowflake.
- **📺 YouTube Link:** [Watch Tutorial by Data Engineering Simplified](https://www.youtube.com/watch?v=cEZYNAa5sHg) - https://www.youtube.com/watch?v=cEZYNAa5sHg

### 73. Snowflake Medallion Architecture with Snowpark & Streamlit
- **📌 Topic / Domain:** Python-in-Snowflake & Interactive Data Apps
- **🛠️ Tech Stack:** `Snowflake` `Snowpark Python` `Snowflake Notebooks` `Streamlit`
- **💡 Project Info:** Builds an entire data engineering pipeline and interactive front-end web application without ever leaving the Snowflake ecosystem using Snowpark and native Streamlit.
- **📺 YouTube Link:** [Watch Tutorial by Cloudlearningyard](https://www.youtube.com/watch?v=-tVB_2Sp_8o) - https://www.youtube.com/watch?v=-tVB_2Sp_8o

### 74. E-Commerce Analytics Engineering Project Using dbt
- **📌 Topic / Domain:** Retail Revenue & Customer Cohort Modeling
- **🛠️ Tech Stack:** `dbt` `Cloud Data Warehouse` `SQL` `YAML Testing` `Documentation`
- **💡 Project Info:** Focuses on analytics engineering best practices: building modular SQL transformations, writing custom schema tests, generating lineage graphs, and documenting business metrics.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](https://www.youtube.com/watch?v=Osy_9KoUvgY) - https://www.youtube.com/watch?v=Osy_9KoUvgY

### 75. dbt Full Course with 2 Real-World Portfolio Projects
- **📌 Topic / Domain:** Job Market & Analytics Engineering
- **🛠️ Tech Stack:** `dbt Core` `Snowflake / DuckDB / BigQuery` `SQL` `Git`
- **💡 Project Info:** An 8+ hour comprehensive project build that walks through setting up dbt from scratch and completing two end-to-end dimensional modeling projects.
- **📺 YouTube Link:** [Watch Tutorial by Luke Barousse](https://www.youtube.com/watch?v=1Bf049kXV2g) - https://www.youtube.com/watch?v=1Bf049kXV2g

### 76. Swiggy Food Delivery Data Pipeline in Snowflake
- **📌 Topic / Domain:** Food Delivery Logistics & Order Analytics
- **🛠️ Tech Stack:** `Snowflake` `Snowpipe` `Streams & Tasks` `Stages` `SQL`
- **💡 Project Info:** Builds an end-to-end Snowflake pipeline for Swiggy food delivery operations using external stages, continuous Snowpipe ingestion, Streams for CDC, and Tasks for automated SCD merges.
- **📺 YouTube Link:** [Watch Tutorial by Data Engineering Simplified](http://www.youtube.com/watch?v=IktHL33Wgug) - http://www.youtube.com/watch?v=IktHL33Wgug

### 77. Airbnb End-to-End Data Engineering Project (dbt + Snowflake + AWS)
- **📌 Topic / Domain:** Hospitality & Short-Term Rental Marketplace
- **🛠️ Tech Stack:** `Snowflake` `dbt` `AWS S3` `Jinja` `SQL`
- **💡 Project Info:** Stages raw Airbnb listings, hosts, and review datasets in AWS S3, loads them into Snowflake, and builds a complete dimensional data warehouse using dbt macros, snapshots, and tests.
- **📺 YouTube Link:** [Watch Tutorial by Ansh Lamba](http://www.youtube.com/watch?v=3SZSDKEZqoA) - http://www.youtube.com/watch?v=3SZSDKEZqoA

### 78. Netflix Content & Viewership Analytics Project with dbt
- **📌 Topic / Domain:** Media Streaming & Content Catalog Analytics
- **🛠️ Tech Stack:** `dbt` `Snowflake` `SQL` `Jinja` `Git`
- **💡 Project Info:** Models Netflix movies, TV shows, ratings, and release trends using dbt staging, intermediate, and mart layers with automated documentation and lineage graphs.
- **📺 YouTube Link:** [Watch Tutorial by Darshil Parmar](http://www.youtube.com/watch?v=zZVQluYDwYY) - http://www.youtube.com/watch?v=zZVQluYDwYY

### 79. Hotel Booking End-to-End Data Engineering Project in Snowflake
- **📌 Topic / Domain:** Travel, Hospitality & Reservation Analytics
- **🛠️ Tech Stack:** `Snowflake` `SQL` `Snowflake Tasks` `Streams` `Dimensional Modeling`
- **💡 Project Info:** Transforms raw hotel reservation, cancellation, and guest demographic logs into clean analytical star schemas inside Snowflake to optimize occupancy and revenue metrics.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](http://www.youtube.com/watch?v=cSOTxxvqwyE) - http://www.youtube.com/watch?v=cSOTxxvqwyE

### 80. Code-Along Modern ELT Pipeline in 1 Hour (dbt, Snowflake, Airflow)
- **📌 Topic / Domain:** Modern Data Stack ELT Fundamentals
- **🛠️ Tech Stack:** `Snowflake` `dbt Core` `Apache Airflow` `Cosmos` `Docker`
- **💡 Project Info:** A fast-paced, hands-on build setting up Snowflake RBAC roles, developing modular dbt fact models, and scheduling the dbt DAG inside Apache Airflow.
- **📺 YouTube Link:** [Watch Tutorial by jayzern](http://www.youtube.com/watch?v=OLXkGB7krGo) - http://www.youtube.com/watch?v=OLXkGB7krGo

### 81. Declarative Real-Time Pipelines with Snowflake Dynamic Tables
- **📌 Topic / Domain:** Declarative Incremental Warehousing in Snowflake
- **🛠️ Tech Stack:** `Snowflake` `Dynamic Tables` `SQL` `Medallion Architecture`
- **💡 Project Info:** Replaces complex Streams and Tasks choreography with declarative Snowflake Dynamic Tables that automatically manage incremental refreshes and target lag across Medallion layers.
- **📺 YouTube Link:** [Watch Tutorial by Cloudlearningyard](http://www.youtube.com/watch?v=-lzs9fi1W60) - http://www.youtube.com/watch?v=-lzs9fi1W60

---

## 🔄 7. Workflow Orchestration (Airflow, Dagster, Prefect)

### 82. Amazon Books E-Commerce Scraping & Airflow ETL Pipeline
- **📌 Topic / Domain:** Web Scraping & Pricing Intelligence
- **🛠️ Tech Stack:** `Apache Airflow` `Python` `BeautifulSoup / Requests` `PostgreSQL` `Docker`
- **💡 Project Info:** Scrapes book metadata, ratings, and pricing from Amazon, cleanses the extracted records in Python, and schedules daily inserts into PostgreSQL using an Airflow DAG.
- **📺 YouTube Link:** [Watch Tutorial by Sunjana in Data](https://www.youtube.com/watch?v=3xyoM28B40Y) - https://www.youtube.com/watch?v=3xyoM28B40Y

### 83. Automated Local Modern Data Stack (Airflow, dbt, Postgres, Superset)
- **📌 Topic / Domain:** 100% Open-Source Analytics Stack
- **🛠️ Tech Stack:** `Apache Airflow` `dbt` `PostgreSQL` `Apache Superset` `Docker` `WSL2`
- **💡 Project Info:** Builds a complete, zero-cost modern data stack locally on your machine using Docker Compose, connecting Airflow and dbt to PostgreSQL and visualizing data in Apache Superset.
- **📺 YouTube Link:** [Watch Tutorial by Calvin Yoon](https://www.youtube.com/watch?v=vMgFadPxOLk) - https://www.youtube.com/watch?v=vMgFadPxOLk

### 84. Asset-Based Data Orchestration Project with Dagster
- **📌 Topic / Domain:** Software-Defined Assets & Data Lineage
- **🛠️ Tech Stack:** `Dagster` `Python` `DuckDB / Snowflake` `dbt`
- **💡 Project Info:** Introduces modern declarative orchestration using Dagster's Software-Defined Assets, showing how to manage dependencies, partitions, and observability cleaner than traditional task schedulers.
- **📺 YouTube Link:** [Watch Tutorial by jayzern](https://www.youtube.com/watch?v=Xe8wYYC2gWQ) - https://www.youtube.com/watch?v=Xe8wYYC2gWQ

### 85. Resilient Python Data Pipeline with Prefect
- **📌 Topic / Domain:** Pythonic Workflow Orchestration
- **🛠️ Tech Stack:** `Prefect` `Python` `REST APIs` `SQL Database`
- **💡 Project Info:** Transforms standard Python extraction scripts into fault-tolerant, scheduled production workflows with automatic retries, logging, and notifications using Prefect decorators.
- **📺 YouTube Link:** [Watch Tutorial by CodeSeoul](https://www.youtube.com/watch?v=FxRZ9zo6GmI) - https://www.youtube.com/watch?v=FxRZ9zo6GmI

### 86. End-to-End Flight Operations Data Pipeline Using Apache Airflow
- **📌 Topic / Domain:** Aviation Schedules & Airport Operations
- **🛠️ Tech Stack:** `Apache Airflow` `Python` `PostgreSQL` `REST API` `Docker`
- **💡 Project Info:** Orchestrates an aviation pipeline using Apache Airflow that extracts live flight status and airport telemetry, performs data validation, and loads analytical tables.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](http://www.youtube.com/watch?v=9PxRPulvLCg) - http://www.youtube.com/watch?v=9PxRPulvLCg

### 87. End-to-End ETL Pipeline Using Apache Airflow & Astronomer (Astro CLI)
- **📌 Topic / Domain:** Space / NASA API Telemetry & Containerized Orchestration
- **🛠️ Tech Stack:** `Apache Airflow` `Astronomer (Astro CLI)` `PostgreSQL` `Docker` `Python`
- **💡 Project Info:** Uses the Astronomer CLI and TaskFlow API in Airflow to build a containerized ETL pipeline that pulls daily astronomical payloads, transforms JSON data, and loads Postgres.
- **📺 YouTube Link:** [Watch Tutorial by Krish Naik](http://www.youtube.com/watch?v=Y_vQyMljDsE) - http://www.youtube.com/watch?v=Y_vQyMljDsE

### 88. Cloud-Native Data Engineering on Kubernetes with Airflow
- **📌 Topic / Domain:** Container Orchestration & Scalable Data Infrastructure
- **🛠️ Tech Stack:** `Kubernetes (K8s)` `Apache Airflow` `Docker` `Helm` `Python`
- **💡 Project Info:** Deploys and scales Apache Airflow on a Kubernetes cluster using the KubernetesExecutor so every ETL task runs in its own isolated, auto-scaled pod.
- **📺 YouTube Link:** [Watch Tutorial by CodeWithYu](http://www.youtube.com/watch?v=ISftrpAImHA) - http://www.youtube.com/watch?v=ISftrpAImHA

### 89. Open-Source ELT Stack with MinIO, Airbyte, dbt & Postgres
- **📌 Topic / Domain:** Self-Hosted Open-Source Data Integration
- **🛠️ Tech Stack:** `Airbyte` `MinIO (S3 Compatible)` `dbt` `PostgreSQL` `Docker Compose`
- **💡 Project Info:** Combines Airbyte connectors for automated ingestion, MinIO for local S3-compatible object storage, and dbt + PostgreSQL for open-source warehouse modeling.
- **📺 YouTube Link:** [Watch Tutorial by BI Insights Inc](http://www.youtube.com/watch?v=nbkrbPFSppQ) - http://www.youtube.com/watch?v=nbkrbPFSppQ

### 90. Docker & Docker Compose Workflows for Data Engineering
- **📌 Topic / Domain:** Reproducible Local Data Pipelines & Containerization
- **🛠️ Tech Stack:** `Docker` `Docker Compose` `PostgreSQL` `pgAdmin` `Python`
- **💡 Project Info:** Teaches how to network multiple data engineering services (Python ingestion containers, Postgres databases, and management UIs) with persistent volumes via Docker Compose.
- **📺 YouTube Link:** [Watch Tutorial by DataTalksClub ⬛](http://www.youtube.com/watch?v=lP8xXebHmuE) - http://www.youtube.com/watch?v=lP8xXebHmuE

### 91. End-to-End Dagster Data Platform Speedrun
- **📌 Topic / Domain:** Declarative Data Asset Orchestration
- **🛠️ Tech Stack:** `Dagster` `dbt` `DuckDB` `Python`
- **💡 Project Info:** Demonstrates how to unify Python ingestion scripts and dbt models into a single asset lineage graph with automated scheduling and materialization in Dagster.
- **📺 YouTube Link:** [Watch Tutorial by Dagster](http://www.youtube.com/watch?v=NaaF7sw1W_8) - http://www.youtube.com/watch?v=NaaF7sw1W_8

---

## 🦆 8. Next-Gen & AI Data Engineering (Iceberg, DuckDB, LLMs)

### 92. Zomato AI Data Analytics & End-to-End AI Data Engineering
- **📌 Topic / Domain:** Food Delivery Analytics & GenAI Integration
- **🛠️ Tech Stack:** `Python` `Cloud Data Warehouse` `LLMs / AI Agents` `SQL` `Vector Embeddings`
- **💡 Project Info:** Combines traditional structured data engineering with AI capabilities on food delivery datasets (orders, restaurant reviews, delivery times) to enable intelligent natural-language analytics.
- **📺 YouTube Link:** [Watch Tutorial by Darshil Parmar](https://www.youtube.com/watch?v=kYwaNMQ3XT8) - https://www.youtube.com/watch?v=kYwaNMQ3XT8

### 93. Weather Data Lakehouse Pipeline with Apache Iceberg
- **📌 Topic / Domain:** Meteorological Telemetry & Open Table Formats
- **🛠️ Tech Stack:** `Apache Iceberg` `PySpark` `REST Weather API` `S3 / MinIO` `Docker`
- **💡 Project Info:** Implements an open lakehouse architecture using Apache Iceberg table formats, demonstrating schema evolution, time travel, and hidden partitioning on live weather data.
- **📺 YouTube Link:** [Watch Tutorial by Data with Jay](https://www.youtube.com/watch?v=T_6gpuG4PQY) - https://www.youtube.com/watch?v=T_6gpuG4PQY

### 94. High-Performance Local Lakehouse with DuckDB & MotherDuck
- **📌 Topic / Domain:** In-Process OLAP & Serverless Analytics
- **🛠️ Tech Stack:** `DuckDB` `MotherDuck` `Python` `Parquet` `SQL`
- **💡 Project Info:** Demonstrates how to process millions of rows of Parquet data directly on a laptop in seconds using DuckDB and sync analytical tables to the cloud with MotherDuck.
- **📺 YouTube Link:** [Watch Tutorial by MotherDuck](https://www.youtube.com/watch?v=3pLKTmdWDXk) - https://www.youtube.com/watch?v=3pLKTmdWDXk

### 95. DuckDB & dbt End-to-End Local Lakehouse Pipeline
- **📌 Topic / Domain:** Zero-Cost In-Process Analytics Engineering
- **🛠️ Tech Stack:** `DuckDB` `dbt-duckdb` `MotherDuck` `Parquet` `SQL`
- **💡 Project Info:** Pairs `dbt-duckdb` with local Parquet files and MotherDuck cloud sync to execute lightning-fast dimensional modeling and testing with zero cloud warehouse spin-up costs.
- **📺 YouTube Link:** [Watch Tutorial by MotherDuck](http://www.youtube.com/watch?v=SpfEQQXBGMQ) - http://www.youtube.com/watch?v=SpfEQQXBGMQ

### 96. End-to-End GenAI & RAG Data Pipeline in Databricks
- **📌 Topic / Domain:** Enterprise Vector Search & Unstructured Data Engineering
- **🛠️ Tech Stack:** `Databricks` `Databricks Vector Search` `Delta Lake` `LangChain` `LLMs`
- **💡 Project Info:** Builds an automated unstructured data pipeline in Databricks that chunks documents, generates vector embeddings, syncs indexes with Delta tables, and serves a RAG application.
- **📺 YouTube Link:** [Watch Tutorial by Data Engineering with Azure](http://www.youtube.com/watch?v=q8oE9YLv3GY) - http://www.youtube.com/watch?v=q8oE9YLv3GY

### 97. Production RAG Pipeline: Data Ingestion to Vector DB from Scratch
- **📌 Topic / Domain:** Document ETL & Vector Database Indexing
- **🛠️ Tech Stack:** `Python` `LangChain` `FAISS / ChromaDB` `Vector Embeddings` `PDF Parsers`
- **💡 Project Info:** Focuses on the data engineering side of RAG: extracting multi-format documents (PDF, TXT, HTML), designing chunking strategies, generating embeddings, and indexing into vector stores.
- **📺 YouTube Link:** [Watch Tutorial by Krish Naik](http://www.youtube.com/watch?v=MykcjWPJ6T4) - http://www.youtube.com/watch?v=MykcjWPJ6T4

### 98. Agentic RAG Pipeline with LangGraph & Vector Databases
- **📌 Topic / Domain:** Agentic AI Workflows & Self-Correcting Retrieval
- **🛠️ Tech Stack:** `LangGraph` `ChromaDB` `Python` `LLMs` `State Graphs`
- **💡 Project Info:** Orchestrates a stateful, multi-step Agentic RAG pipeline using LangGraph that grades retrieved vector documents, rewrites queries on the fly, and prevents hallucinations.
- **📺 YouTube Link:** [Watch Tutorial by AI Bites](http://www.youtube.com/watch?v=oo4OeE3yVBI) - http://www.youtube.com/watch?v=oo4OeE3yVBI

### 99. Building Autonomous Data Agents (Demo Project)
- **📌 Topic / Domain:** AI Agents for Automated SQL & Pipeline Triage
- **🛠️ Tech Stack:** `Python` `AI Agents` `LLMs` `SQL` `Data Warehouse APIs`
- **💡 Project Info:** Demonstrates how to build AI Data Agents capable of inspecting database schemas, writing optimized analytical SQL queries, and automating routine data engineering tasks.
- **📺 YouTube Link:** [Watch Tutorial by Darshil Parmar](http://www.youtube.com/watch?v=v4u6Ym6MWeQ) - http://www.youtube.com/watch?v=v4u6Ym6MWeQ

### 100. Databricks Free Edition End-to-End Data + AI Project
- **📌 Topic / Domain:** Unified Lakehouse + Machine Learning / AI Workflows
- **🛠️ Tech Stack:** `Databricks Free Edition` `PySpark` `Delta Lake` `MLflow` `Unity Catalog` `GenAI`
- **💡 Project Info:** Bridges Medallion data engineering with AI/ML deployment in Databricks, taking raw datasets through Bronze/Silver/Gold layers into feature engineering and AI insights.
- **📺 YouTube Link:** [Watch Tutorial by codebasics](http://www.youtube.com/watch?v=761SQ9Hxbic) - http://www.youtube.com/watch?v=761SQ9Hxbic

---

## 💡 How to Use This List to Get Hired
1. **Pick 3 Complementary Projects:** Choose **1 Batch Cloud Project** (AWS/Azure/GCP), **1 Modern Data Stack Project** (Snowflake/Databricks + dbt + Airflow/Dagster), and **1 Real-Time Streaming or AI Data Pipeline Project** (Kafka + Spark/Flink or LangGraph/RAG).
2. **Don't Just Copy-Paste:** Swap out the tutorial's API or dataset with a unique domain (e.g., if the tutorial uses Spotify data, adapt the exact same architecture to Steam Gaming, Strava Fitness, or Indian Premier League data).
3. **Document Your Architecture:** Always include an architecture diagram (using Excalidraw or Draw.io), setup instructions in your `README.md`, and CI/CD / Dockerization so recruiters can review your work easily.