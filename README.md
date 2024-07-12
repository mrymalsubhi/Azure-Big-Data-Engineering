# Big Data Engineering on Azure

## Project Overview

This project demonstrates a comprehensive big data pipeline on Azure, utilizing advanced data engineering techniques. Data from multiple sources is ingested, transformed, analyzed, and visualized using Azure’s robust suite of services.

## Key Components

### Data Sources
- AWS RDS: Weekly ingestion of user and post type data.
- Azure Storage Blob: Daily ingestion of post data in Parquet format.

### Architecture

- Azure Data Lake: Centralized storage for all ingested and processed data.
- Azure Data Factory (ADF): Orchestrates data ingestion and transformation workflows.
- Databricks: Executes data transformation and machine learning tasks.
- Azure Synapse: Analyzes data and creates insightful visualizations.


### Data Pipeline

1. Ingestion: Data is ingested from AWS RDS and Azure Blob Storage into Azure Data Lake using ADF.
2. Transformation: Data is cleaned and transformed in Databricks notebooks, preparing it for machine learning.
3. Machine Learning: A Databricks-based ML model classifies post topics and outputs results back to the Data Lake.
4. Visualization: Azure Synapse connects to the Data Lake to generate a dynamic report showcasing the top 10 topics of the day.

### Highlights

- Scalable Architecture: Leveraging Azure Data Lake and Databricks for seamless data processing.
- Automated Workflows: Using Azure Data Factory to schedule and manage data ingestion and transformation.
- Real-Time Insights: Azure Synapse provides timely visualizations of the latest data trends.

### Conclusion

This project showcases the power of Azure’s data services to build a robust and scalable big data pipeline. From ingestion to visualization, each component plays a critical role in transforming raw data into actionable insights.
