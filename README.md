# DataMedix-Health Care Domain Project

Technologies Used - Azure Data Engineering Stack

pROJECT OVERVIEW:

Revenue Cycle Management (RCM) is the process that hospitals use to manage financial operations, from patient appointment scheduling to provider payment.

STEP 1

Migrate Data from On-Prem SQL Server to Azure SQL Database with the help of Microsoft Data Migration Assistant software. 
  - There is another way of migrating data from on-prem to azure where i can utilize the SHIR (self hosted intergrated runtime)
  - 

After successful migrated data from on-prem to Azure SQL Database:
  - Created revelant and necesary resources with our main resource groupo in Azure
      - Azure data factory for ingestion and ochestration
      - Databricks for transformation (Medallion Architecture)
