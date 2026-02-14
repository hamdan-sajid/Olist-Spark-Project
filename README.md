Big Data Pipeline using Google Cloud Dataproc
📌 Overview

This project implements an end-to-end big data processing pipeline using Google Cloud Platform with Dataproc (Hadoop + Spark). The pipeline covers data ingestion, cleaning, transformation, integration, optimization, and data serving in a distributed cloud environment.

🏗 Architecture

GCS → Dataproc (Hadoop + Spark) → Processing → Optimized Output → External Storage / Visualization

1️⃣ Data Ingestion & Exploration

Created a Dataproc cluster (Spark + Hadoop).

Uploaded CSV files to Google Cloud Storage (GCS).

Loaded data into Spark DataFrames from GCS/HDFS.

Extracted and validated schema using printSchema() and describe().

Performed initial exploratory analysis and LDA (if applicable).

2️⃣ Data Cleaning & Transformation

Handled missing/null values.

Standardized date formats.

Applied normalization and scaling for numerical features.

Performed feature engineering to create new derived columns.

3️⃣ Data Integration & Aggregation

Joined multiple datasets using Spark SQL.

Aggregated metrics (count, sum, average, etc.).

Removed duplicates and resolved schema inconsistencies.

4️⃣ Performance Optimization

Applied data partitioning for better parallelism.

Used caching for iterative operations.

Tuned Spark configurations for efficient job execution.

5️⃣ Data Serving

Exported processed data to GCS / external databases.

Created visualizations to analyze trends and patterns.
