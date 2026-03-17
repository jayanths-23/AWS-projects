# ☁️ AWS Glue ETL Labs – Data Engineering Project

This repository contains hands-on AWS Glue labs demonstrating the design and implementation of **serverless ETL pipelines and data lake architecture** using AWS services.

---

## 🎯 Objective

To build scalable data pipelines using AWS Glue and understand real-world data engineering workflows.

---

<h2>🏗️ Architecture</h2>

<pre>
S3 (Raw Data)
   ↓
AWS Glue Crawler (Schema Discovery)
   ↓
AWS Glue Data Catalog (Metadata Layer)
   ↓
AWS Glue ETL Jobs (PySpark Transformations)
   ↓
S3 (Processed Data - Parquet)
   ↓
Amazon Athena (Query & Analytics)
</pre>
---

## 🔬 What I Implemented

- Created S3-based data lake (raw & curated layers)
- Built Glue Crawlers for schema discovery
- Used Glue Data Catalog for metadata management
- Developed ETL pipelines using Glue Studio & PySpark
- Applied data transformations (filtering, mapping, deduplication)
- Implemented partitioning for performance optimization
- Used job parameters for reusable pipelines
- Built incremental pipelines using job bookmarks
- Performed debugging using CloudWatch logs
- Created workflows and triggers for automation

---

## 🏁 Capstone Project

Built a complete **end-to-end data pipeline**:

- Raw data → processed using Glue ETL
- Stored in optimized Parquet format
- Queried using Athena
- Optional integration with Redshift

---

## 🧠 Skills

AWS Glue • PySpark • S3 • Athena • ETL Pipelines • Data Lakes • CloudWatch • Data Engineering
---

## 🎥 Demo

Each lab includes a short demo video (2–3 mins) showing execution and results.


