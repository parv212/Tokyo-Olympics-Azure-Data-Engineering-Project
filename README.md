# Tokyo-Olympics-Azure-Data-Engineering-Project

In my Tokyo Olympics-Azure-Data-Engineering project, I developed a data pipeline using Azure Data Factory to process Tokyo Olympics data. Initially, I sourced CSV files from my GitHub repository and ingested them into Azure Data Lake Storage Gen2, structuring the files hierarchically for efficient data management.

The project's next phase involved data transformation. For this, I utilized Azure Databricks, integrating it with Azure to perform necessary data manipulations. Key tasks included validating and correcting column data types and leveraging PySpark for its efficiency in big data processing.

Post-transformation, the cleansed data was stored back into Azure Data Lake. This re-storage was crucial for maintaining an analysis-ready dataset.

Finally, I used Azure Synapse Analytics to build a relational database for data analysis. Here, I employed SQL for data querying and analysis, enabling in-depth insights into the Tokyo Olympics dataset. This step was critical in transforming raw data into a structured format for comprehensive analysis.
