# Customer-Behavior-Analytics-Scalable-ETL-Pipeline-on-GCP-Using-PySpark
E-commerce companies often struggle with understanding customer behavior across multiple platforms (app, web, call center). This project builds a scalable data pipeline that unifies, cleans, and analyzes raw event data from multiple sources — enabling personalized product recommendations, churn detection, and regional trend analysis.

**Technologies Used**
- PySpark – for distributed data processing

- GCP Dataproc – for scalable Spark jobs

- Google Cloud Storage (GCS) – raw data input

- BigQuery – warehousing & SQL-based analytics

- Apache Airflow – pipeline orchestration

- Python + SQL – logic and queries


This project replicates a real-world data engineering scenario for an e-commerce company looking to understand customer behavior across mobile/web platforms. The goal is to build a fault-tolerant, scalable ETL pipeline that:
- Ingests raw event logs from GCS
- Transforms them into clean, enriched datasets using PySpark
- Loads structured data into BigQuery for downstream analytics
- Supports reporting dashboards and ML-driven use cases (e.g., churn prediction)

Use Cases:
- Identify top user cohorts by platform, location, or behavior
- Spot trends in purchase funnels and user engagement
- Enable data scientists to train predictive models with clean data
