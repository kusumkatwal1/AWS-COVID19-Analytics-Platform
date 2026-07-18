# AWS-COVID19-Analytics-Platform
AWS COVID-19 Data Pipeline and Analytics Platform project using Amazon S3, AWS Glue, Athena, and Amazon Redshift. The project performs raw data ingestion, PySpark-based ETL transformation, Silver and Gold layer creation, partitioned Parquet storage, Athena analytics, and Redshift BI reporting.

# AWS Services Used
    - Amazon S3
    - AWS Glue
    - AWS Glue Crawler
    - AWS Glue Data Catalog
    - Amazon Athena
    - Amazon Redshift Serverless
    - IAM
    
# Project Architecture
        COVID CSV Files
        ↓
        Amazon S3 Raw Layer 
        ↓ 
        AWS Glue Crawler 
        ↓ 
        AWS Glue Data Catalog 
        ↓ 
        AWS Glue PySpark ETL Job 
        ↓ 
        Silver Layer Partitioned Parquet 
        ↓
        Gold Layer Dimensional Models
        ↓
        Amazon Athena Analytics 
        ↓
        Amazon Redshift Data Warehouse 
        ↓
        SQL BI Reporting

# File Structure 
     - "README.md" - walkthrough about the project
     - "Detailed_AWS_COVID19_Project_Submission_Guide.pdf" - this file contains the step-by-step details for the whole 
         process of the given project.

   
@Kusum Katwal

