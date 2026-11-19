# Data Engineering Capstone Project

An end-to-end Data Engineering project focused on large-scale data processing and data integration using **Databricks, Apache Spark, PySpark, Hive, and Apache Kafka**.

## Project Overview

This capstone project demonstrates a data processing pipeline designed to extract, transform, and publish structured Master Data Management (MDM) records.

The pipeline uses PySpark to process data from Hive source tables, apply business transformations, filter records using runtime parameters, and prepare structured messages for downstream integration through Apache Kafka.

The project focuses on scalable data processing, data consistency, transformation logic, and reliable data delivery.

## Architecture & Workflow

1. **Data Source:** Read structured MDM datasets from Hive tables.
2. **Data Ingestion:** Load source data into Spark DataFrames.
3. **Data Filtering:** Apply runtime-based filtering using `load_date`.
4. **Data Transformation:** Perform joins, filtering, data cleansing, and schema handling using PySpark.
5. **Data Integration:** Process multiple business entities and prepare structured JSON payloads.
6. **Kafka Publishing:** Publish processed records to appropriate Kafka topics using message keys and values.
7. **Data Reliability:** Handle processing failures, retries, duplicate records, and data consistency.

## Key Features

- Large-scale processing of 500+ business entities.
- PySpark-based data transformations and integration.
- Hive-based structured data ingestion.
- Runtime-driven incremental data processing.
- DataFrame joins, filtering, and Spark SQL operations.
- JSON payload generation for downstream systems.
- Kafka topic-based event publishing.
- Error handling and data consistency considerations.

## Technology Stack

| Technology | Purpose |
|---|---|
| Databricks | Data engineering development environment |
| Apache Spark | Distributed data processing |
| PySpark | Data transformation and processing |
| Python | Programming language |
| SQL | Data querying and manipulation |
| Hive | Source data management |
| Apache Kafka | Event streaming and integration |

## Core Data Engineering Concepts

- Spark transformations and actions
- DataFrame operations and joins
- Distributed processing and partitioning
- Runtime parameterization
- Incremental data processing
- Kafka topics, partitions, keys, and values
- JSON serialization
- Error handling and retry mechanisms
- Data quality and consistency

## Project Objectives

- Understand end-to-end enterprise data pipeline development.
- Process structured data efficiently using distributed computing.
- Integrate multiple source entities into standardized outputs.
- Develop practical experience with Spark and Kafka-based data integration.
- Understand scalability and reliability challenges in data engineering.

## Learning Outcomes

Through this project, I developed practical understanding of PySpark, Apache Spark, data transformation workflows, Hive integration, Kafka publishing, and distributed data processing concepts.

## Author

**Mayank**

Data Engineering | Python | PySpark | SQL | Databricks

---

*This repository documents my Data Engineering capstone project and practical learning in big data processing and data integration.*
