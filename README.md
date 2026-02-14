# adf-to-adls-ingestion
GitHub → Azure Data Factory → ADLS → Databricks Auto Loader → Databricks Notebooks → Processed Tables.

GitHub (raw files)
        |
        v
Azure Data Factory (ingestion)
        |
        v
Azure Data Lake Storage Gen2 (Bronze)
        |
        v
Databricks Auto Loader
        |
        v
Databricks Notebooks (transformations)
        |
        v
Silver / Gold Delta Tables
