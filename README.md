# Telecom Customer Churn Analytics Platform

## Overview

This project demonstrates an end-to-end ETL pipeline built using the Hadoop ecosystem to analyze telecom customer churn data.

## Objective

To ingest customer data from MySQL into Hadoop, process and validate the data using Hive, and perform churn analysis to generate business insights.

## Technologies Used

- MySQL
- Sqoop
- Hadoop (HDFS)
- Hive
- HiveQL
- Linux
- Cloudera

## ETL Workflow

```
MySQL
   ↓
 Sqoop
   ↓
 HDFS
   ↓
 Hive External Tables
   ↓
 HiveQL Analysis
```

## Features

- Imported telecom customer data from MySQL into HDFS using Sqoop.
- Created Hive External Tables for structured data analysis.
- Performed data cleansing, validation, and transformation using HiveQL.
- Optimized Hive queries using partitioning and bucketing.
- Automated ETL tasks using Linux shell scripting.
- Performed source-to-target data validation.
- Generated customer churn insights using HiveQL queries.

## Project Structure

```
telecom-customer-churn-analytics/
│
├── dataset/
├── mysql/
├── sqoop/
├── hive/
├── shell/
├── screenshots/
└── README.md
```

## Author

**Manali Nitin Kulkarni**
