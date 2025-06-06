# 🧬 Pokemon Combat ETL to Redshift (AWS Glue Project)

Welcome to this end-to-end ETL project where we move and transform Pokémon combat data using **AWS Glue**, and load it into **Amazon Redshift Serverless** — all within a secure, private cloud setup.

---

## 🔧 What’s Used in This Project
We built this pipeline using the following AWS services:

- 🛠 **AWS Glue** – for transforming and moving the data
- 🛢 **Amazon Redshift Serverless** – our cloud data warehouse
- 📦 **Amazon S3** – for storing input files
- 🔐 **IAM, VPC, Endpoints, Security Groups** – to keep everything secure and connected

---

## 🧭 How the Pipeline Works

1. 📥 We start with a CSV file of Pokémon combat stats in an S3 bucket.
2. 🧹 Glue picks it up, processes the data, and applies any needed transformations.
3. 🎯 The final, cleaned data is written into a Redshift Serverless table using JDBC.
4. 🚀 The job can be triggered manually or scheduled as needed.

---




