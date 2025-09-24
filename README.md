# 📊 YouTube Analytics Pipeline on AWS

An end-to-end **data engineering pipeline** designed to process, store, and analyze YouTube trending video data.  
This project demonstrates how to build a **scalable cloud-native analytics system** using AWS services — from ingestion to interactive reporting.

---

## 🎯 Project Goals
- ✅ **Data Ingestion** – Collect data from multiple sources  
- ✅ **ETL System** – Transform raw data into a structured format  
- ✅ **Data Lake** – Centralized storage for large datasets  
- ✅ **Scalability** – Ensure growth with increasing data  
- ✅ **Cloud Processing** – Leverage AWS for large-scale data handling  
- ✅ **Reporting** – Build interactive dashboards for insights  

---

## ☁️ AWS Services Used
- 🔹 **Amazon S3** – Scalable object storage for raw and processed data  
- 🔹 **AWS IAM** – Secure identity and access management  
- 🔹 **Amazon QuickSight** – Business intelligence & visualization dashboards  
- 🔹 **AWS Glue** – Serverless ETL for data transformation  
- 🔹 **AWS Lambda** – Event-driven compute for automation  
- 🔹 **Amazon Athena** – Interactive querying on S3 data  

---

## 📂 Dataset
- Source: [YouTube Trending Video Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)  
- Contains daily statistics on trending YouTube videos across multiple regions.  

---

## 🔄 Pipeline Overview
1. **Data Ingestion**  
   - Load raw CSV datasets from Kaggle into Amazon S3.  

2. **ETL with AWS Glue**  
   - Transform raw JSON/CSV data into a structured format (Parquet/ORC).  
   - Clean and normalize columns for analysis.  

3. **Data Lake on S3**  
   - Store both raw and curated datasets in a centralized data lake.  

4. **Query with Athena**  
   - Use SQL queries directly on S3 datasets without moving data.  

5. **Automation with Lambda**  
   - Trigger ETL jobs and reporting workflows based on events.  

6. **Visualization with QuickSight**  
   - Build interactive dashboards showing YouTube trends (views, likes, categories, regional analysis).  

---

## 📊 Sample Insights
- Top video categories per region  
- Trends in likes, comments, and engagement  
- Comparison of regional viewing habits  

---

## 🚀 Future Enhancements
- Integrate with **Kafka/Kinesis** for real-time streaming ingestion  
- Deploy dashboards to stakeholders via secure QuickSight sharing  
- Add predictive analytics using AWS SageMaker  

---

## 🛠 Tech Stack
- **Languages:** Python, SQL  
- **Frameworks:** PySpark (ETL)  
- **Cloud:** AWS (S3, Glue, Athena, Lambda, QuickSight)  

---

✨ This pipeline enables **efficient processing, scalable storage, and powerful visualization** of YouTube trends — turning raw data into **actionable insights**.
