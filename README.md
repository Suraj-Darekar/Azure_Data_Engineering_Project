# Azure_Data_Engineering_Project
#### <ins>Project Objective</ins>

The objective of this data engineering project was to establish an end-to-end solution for processing and transforming data from an on-premise SQL Server database named "Pizza_Sales" to a refined form using Azure services. The project involved leveraging Azure Data Factory (ADF) for data ingestion, storing the raw data in Azure Data Lake within a designated container named "raw" in Azure Blob Storage. Subsequently, Azure Databricks was employed for data transformation, ensuring the conversion of raw data into its cleanest form. Finally, the transformed data was visualized using Microsoft Power BI. 

#### <ins>Architecture Diagram</ins>
![Untitled](https://github.com/Suraj-Darekar/Azure_Data_Engineering_Project/assets/140320836/3555e222-070c-40c1-af44-e4156c4c589f)

#### Components and Data flow:

•	SQL Server: 
Extracting tables from an on-premise SQL Server database named "Pizza_Sales." 

![Capture](https://github.com/Suraj-Darekar/Azure_Data_Engineering_Project/assets/140320836/aa780a05-8356-4ceb-9c4e-ed0308a58b2f)

• Azure Data Factory (ADF):
Utilized for the critical task of ingesting data from the on-premise SQL Server database. ADF facilitated the creation of a robust and scalable data pipeline, ensuring the seamless transfer of data to Azure Blob Storage. The objective here was to establish a reliable mechanism for scheduled and automated data movement.

• Azure Blob Storage - Raw Container:
A dedicated container named "raw" was created to store the raw data ingested from SQL Server. This container served as the initial repository for the Pizza_Sales data, providing a centralized and scalable storage solution.

![a](https://github.com/Suraj-Darekar/Azure_Data_Engineering_Project/assets/140320836/63d27e5c-75ba-4353-bcd3-c10bf9b9ac85)

• Azure Databricks:
Used to process the raw data stored in Azure Blob Storage, applying necessary transformations to achieve the cleanest form of data. Databricks notebooks were employed to execute ETL (Extract, Transform, Load) processes, enhancing data quality and usability.

![image](https://github.com/Suraj-Darekar/Azure_Data_Engineering_Project/assets/140320836/1222052d-e077-4ce7-9d31-e2fbf20ae191)

• Power BI:
Finally, the transformed data was visualized using Microsoft Power BI. To create insightful and interactive dashboards that present the transformed data in a meaningful way. 

![image](https://github.com/Suraj-Darekar/Azure_Data_Engineering_Project/assets/140320836/d077986e-69ec-4078-93cd-da9946e90f1b)

