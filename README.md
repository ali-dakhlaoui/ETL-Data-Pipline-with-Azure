the data used is about Tokyo Olympics and could be found in Kaggle.
In this project, 3 main steps are conducted:
  #1/ Pipeline for data Ingestion using Azure Data Factory : allow the data to get fetched from github or whatever source holding the data to an Azure Data Lake that contains 'raw-data' folder
  #2/ Using Azure Databricks, the uploaded notebook have the full strategy used to do data transformation, from mounting your databricks workspace and your storage account to data transformation.
  #3/ Loading the transformed data into 'transformed-data' folder in the Azure Data Lake
