# Data Warehouse & Analytics Project
Welcome to my Data Warehouse and Analytics Project. 🚀

This repository showcases the design and implementation of a modern data warehouse using Microsoft SQL Server, following a Medallion Architecture with Bronze, Silver, and Gold layers.

The project demonstrates an end-to-end data engineering workflow, starting with raw data ingestion and continuing through data cleansing, transformation, dimensional modeling, and analytical reporting.

## Project Overview
The main objective of this project is to build a centralized analytical data warehouse that integrates data from multiple source systems and transforms it into a reliable and business-ready dataset for reporting and analytics.

## The solution follows three main layers:

1-**Bronze Layer**
Stores data ingested from the original source files with minimal transformation. This layer preserves the source data and provides a foundation for downstream processing.

2-**Silver Layer**
Applies data cleansing, validation, standardization, and transformation rules to improve data quality and consistency.

3-**Gold Layer**
Contains business-ready dimensional models designed for analytical workloads. The final model follows a Star Schema consisting of fact and dimension tables.
