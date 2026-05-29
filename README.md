# Capital Markets Risk Platform

## Overview

A production grade real time trade surveillance and risk analytics platform built using modern data engineering technologies and cloud-native architecture principles.

This platform simulates enterprise-scale financial data processing workloads including trade ingestion, streaming analytics, ETL orchestration, data quality validation, and warehouse reporting.

## Architecture

The platform implements a modern medallion lakehouse architecture:

* Bronze Layer → Raw ingestion
* Silver Layer → Cleansed and enriched data
* Gold Layer → Business analytics and reporting

## Technology Stack

* PySpark
* Kafka
* Apache Airflow
* Docker
* Delta Lake
* PostgreSQL
* AWS style lakehouse architecture
* GitHub Actions

## Key Features

* Real-time streaming pipelines
* Batch ETL processing
* Trade surveillance analytics
* Risk aggregation pipelines
* Data quality validation
* Workflow orchestration
* CI/CD integration
* Lakehouse architecture patterns

## Project Goals

* Simulate enterprise-grade financial data engineering workloads
* Demonstrate scalable distributed data processing
* Implement production engineering best practices
* Showcase modern cloud-native data platform architecture
