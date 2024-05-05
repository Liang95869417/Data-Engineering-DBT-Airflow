# Data-Engineering-DBT-Airflow
---
This project illustrates the process of constructing and automating an ETL pipeline using Airflow DAGs to process and transfer data into BigQuery. It employs various tools including Astro, DBT, GCP, Airflow, and Metabase to facilitate different stages of the pipeline development and execution.

# Project Goals
---
- The field of data engineering is rapidly evolving with the introduction of new tools and technologies. To stay current, it's essential to explore and utilize these tools firsthand. In this project, I've employed several cutting-edge tools to develop a robust and efficient data pipeline. It's well-known that incorporating multiple tools can complicate integration due to dependencies or, more dauntingly, "dependency hell." However, this challenge also provides a deeper insight into the architecture's intricacies.

- Data Ingestion: Implement a pipeline to continuously extract incoming data and store it in GCP BigQuery.

- Data Quality: Utilize Soda to conduct thorough data quality checks using YAML files for configuration.

- Data Transformation: Employ DBT for data modeling and to transform the dataset into a star schema format.

- Data Loading: Use the data pipeline to transfer the processed data into GCP BigQuery.

- Data Reporting/Analytics: Leverage Metabase to construct dashboards that facilitate reporting and analytics.

# Data Architecture
