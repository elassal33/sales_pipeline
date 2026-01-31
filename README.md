# Sales Data Pipeline (PySpark / Databricks)

## Overview
Designed and implemented a **scalable sales data pipeline** using PySpark on Databricks, following the **Bronze → Silver → Gold** architecture. The pipeline ingests sales data from multiple sources, performs automated transformations, and delivers clean, analytics-ready datasets for reporting and BI. The workflow is fully automated using **Databricks Jobs**.

## Architecture
- **Bronze Layer**: Ingest raw, unprocessed sales data from various sources into Delta Lake.  
- **Silver Layer**: Clean, standardize, and transform the data to ensure consistency and quality.  
- **Gold Layer**: Build **dimension and fact tables** optimized for analytics and BI reporting, enabling fast and accurate insights.  

## Tech Stack
**PySpark · Delta Lake · Databricks · Databricks Jobs**

## Outcome
Delivered a **production-ready, automated pipeline** capable of handling large-scale sales datasets, providing clean, structured, and aggregated tables for business intelligence and analytical use cases. The creation of **dimension and fact tables** in the Gold layer enhanced query performance and simplified downstream reporting.
