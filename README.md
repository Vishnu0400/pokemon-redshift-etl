# pokemon-redshift-etl
# 🧬 Pokemon Combat ETL to Redshift (AWS Glue Project)

This project demonstrates an end-to-end ETL pipeline using **AWS Glue** to load data into **Amazon Redshift Serverless** using private networking.

## 🔧 Tools & Services
- AWS Glue (ETL Job)
- Amazon Redshift Serverless
- S3 (input/output)
- IAM + VPC Endpoints + Security Groups

## 🛠️ Architecture
1. Input data is stored in S3
2. AWS Glue reads & transforms the data
3. Transformed data is written to Redshift Serverless via JDBC
4. Job is triggered manually / scheduled

## 🗃️ Schema
See `schema/create_redshift_table.sql`

## 📂 Glue Job
Script: `glue_job/untipokemon_etl.py`

## 🔐 Redshift Connection
See `config/connection_config.md` for setup details

## 📸 Screenshots
- Glue connection setup
- Redshift endpoint config

## 📝 Notes
- Job tested in private subnet with S3 and Redshift VPC endpoints
