# 🚀 BIG DATA PIPELINE USING GOOGLE CLOUD DATAPROC

---

## 📌 OVERVIEW

This project implements an end-to-end big data processing pipeline using **Google Cloud Platform (GCP)** with **Dataproc (Hadoop + Spark)**.  
The pipeline covers data ingestion, cleaning, transformation, integration, optimization, and data serving in a distributed cloud environment.

---

## 🏗 ARCHITECTURE

**GCS → Dataproc (Hadoop + Spark) → Processing → Optimized Output → External Storage / Visualization**

---

## 1️⃣ DATA INGESTION & EXPLORATION

- Created a Dataproc cluster (Spark + Hadoop)  
- Uploaded CSV files to **Google Cloud Storage (GCS)**  
- Loaded data into Spark DataFrames from GCS/HDFS  
- Extracted and validated schema using `printSchema()` and `describe()`  
- Performed exploratory analysis and LDA (if applicable)

---

## 2️⃣ DATA CLEANING & TRANSFORMATION

- Handled missing/null values  
- Standardized date formats  
- Applied normalization and scaling for numerical features  
- Performed feature engineering to create derived columns  

---

## 3️⃣ DATA INTEGRATION & AGGREGATION

- Joined multiple datasets using Spark SQL  
- Aggregated metrics (count, sum, average, etc.)  
- Removed duplicates and resolved schema inconsistencies  

---

## 4️⃣ PERFORMANCE OPTIMIZATION

- Applied data partitioning for better parallelism  
- Used caching for iterative operations  
- Tuned Spark configurations for efficient job execution  

---

## 5️⃣ DATA SERVING

- Exported processed data to GCS / external databases  
- Created visualizations to analyze trends and patterns  

---

## ⚙️ TECH STACK

- Google Cloud Dataproc  
- Apache Spark  
- Hadoop (HDFS)  
- Spark MLlib  
- PySpark  
