# Spotify-end-to-end-etl-pipeline-data-engineering

This project is an end-to-end data pipeline that extracts music data from the Spotify API and processes it using AWS cloud services. The final output is a fully queryable dataset, visualized using Power BI for analysis and insights.

---

## 🚀 Features

- **Spotify API Integration** – Extract track, artist, and album data using Python
- **Data Lake on S3** – Store raw and transformed data in structured S3 buckets
- **Serverless Processing with AWS Lambda** – Transform data automatically
- **Orchestration with CloudWatch** – Schedule and trigger Lambda functions
- **Schema Detection with AWS Glue** – Crawl and catalog S3 data
- **Query Engine with Athena** – Perform SQL queries directly on S3
- **Visualization with Power BI** – Analyze and visualize data

---

## 🛠️ Technologies Used

- Python
- Spotify Web API
- AWS S3
- AWS Lambda
- AWS CloudWatch
- AWS Glue
- AWS Athena
- Power BI


#ARCHITECTURE DIAGRAM 
![ETL ARCHITECTURE](spotify-end-to-end-etl-pipeline/ETL_ARCHITECTURE.png)
