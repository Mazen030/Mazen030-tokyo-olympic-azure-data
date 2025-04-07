# 🏅 Olympic Data Analytics Project (Azure End-to-End Pipeline)
This project demonstrates a complete end-to-end data engineering pipeline built on Microsoft Azure. The goal is to collect, process, analyze, and visualize Olympic Games data using modern cloud-based tools and best practices.

# 🚀 Project Overview
This project leverages Azure's powerful data services to ingest, transform, and visualize Olympic data in a scalable and structured way. It follows a modular and enterprise-level data pipeline pattern, from raw data ingestion to dashboard analytics.
# 🔧 Tools & Technologies Used

Data Integration:	Azure Data Factory \
Raw Data Storage:	Azure Data Lake Gen 2 \
Data Transformation:	Azure Databricks \
Analytics & Querying:	Azure Synapse Analytics \
Visualization:	Power BI
# 📊 Pipeline Architecture
![image](https://github.com/user-attachments/assets/3cf32a81-94a1-49b5-9cd2-b594c2ed07f7) 
Here's how the data flows through the pipeline:

Data Source \
Raw Olympic data (CSV, JSON, etc.) is sourced from internal or public datasets. 

Data Ingestion – Azure Data Factory \
Data Factory is used to orchestrate and automate data movement from source to storage. 

Raw Storage – Azure Data Lake Gen2 \
The raw data is stored in a data lake for durability and scalability. \

Data Transformation – Azure Databricks \
Using Databricks notebooks (Apache Spark), raw data is cleaned, transformed, and enriched. \

Transformed Data Storage – Azure Data Lake Gen2 \
The output of the transformation stage is saved in a separate folder for curated datasets. 

Analytics – Azure Synapse Analytics \
Transformed data is queried and analyzed for business insights using Synapse SQL Pools. 

Dashboard & Reporting \
Data is visualized through tools like Power BI
