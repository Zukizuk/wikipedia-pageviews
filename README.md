# Data Engineering Lab Project: Wikipedia Analytics & Kafka Streaming

## Introduction

This project consists of two main components: a Wikipedia pageviews analysis system using Apache Spark and a data streaming pipeline using Apache Kafka. The project demonstrates practical implementation of big data processing and real-time streaming analytics.

## Components and Technologies

### Lab Exercise 1: Wikipedia Pageviews Analysis

- **Google Cloud Platform (GCP)**
  - Dataproc for managed Spark cluster
  - BigQuery for data warehousing
- **Apache Spark**
  - PySpark for data processing
  - Spark SQL for data transformation
- **Jupyter Notebooks**
- **Pandas** for data visualization

### Lab Exercise 2: Kafka Streaming Pipeline

- **Apache Kafka**
  - Kafka Streams API
  - Console Producer/Consumer
- **Java** for stream processing
- **Google Compute Engine** for Kafka cluster deployment

## Setup Instructions

### Wikipedia Analysis Setup

1. Create a Dataproc cluster with Jupyter & Component Gateway enabled on GCP
2. Configure Apache Spark and Jupyter Notebooks
3. Ensure BigQuery access is properly configured

### Kafka Pipeline Setup

1. Launch Compute Engine instance
2. Install and configure Kafka cluster
3. Set up required topics for data streaming

## Project Structure

### Wikipedia Analysis Component

- Data ingestion from BigQuery
- Filtering for English Wikipedia (desktop and mobile)
- Page view analysis and aggregation
- Data export to BigQuery
- Visualization using Pandas

### Kafka Streaming Component

- Topic creation and management
- Data producer implementation
- Stream processing configuration
- Consumer setup for output inspection

## Key Features

- Real-time data processing capabilities
- Scalable data analysis framework
- Cross-platform compatibility
- Integrated visualization tools
- BigQuery integration for data persistence

## Prerequisites

- GCP account with necessary permissions
- Cloud Skills Boost account
- Basic understanding of:
  - SQL
  - Python
  - Big data concepts

## Contributing

This project was completed as part of Week 4 Labs, due November 25th, 2024.

## License

This project is for educational purposes only.
