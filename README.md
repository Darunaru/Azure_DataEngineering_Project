# Olympic Azure Data Engineering Project

## Introduction
Built an end-to-end data pipeline solution in Azure, including data ingestion, storing, transforming, and analysing and then visualize Olympics-related data using Power BI, enabling data-driven insights and informed decision-making.

## Azure Services

**Azure Data Factory:** 
- It  is employed for the purpose of data ingestion, enabling us to efficiently gather data from various sources and transfer it to the desired destination. In our project, ADF is responsible for importing Olympics data from external sources.

**Azure Data Lake Storage Gen2:**
- It is where the ingested data is housed. This platform offers scalability and security for storing large data volumes, facilitating effective data management, access, and analysis.

**Azure Databricks:**
- It is utilized for data transformation, employing PySpark. Databricks provides a collaborative environment for data engineers and data scientists to collaborate on big data projects. In our project, PySpark is used to clean, reshape, and process the raw Olympics data into a more usable format.

**Azure Synapse Analytics:**
- It is employed to extract valuable insights from the transformed data. It allows us to run SQL queries on the data warehouse to uncover meaningful information, including trends, patterns, and insights related to the Olympics data.
