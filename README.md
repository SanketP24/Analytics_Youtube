# Analytics_Youtube
Project Overview:

This project is aimed at securely managing, streamlining, and analyzing structured and semi-structured data from YouTube videos, focusing on video categories and trending metrics.

Project Goals:

Data Ingestion: Develop a mechanism to ingest data from diverse sources.
ETL System: Transform raw data into the proper format for analysis.
Data Lake: Establish a centralized repository to store data from multiple sources.
Scalability: Ensure the system can scale with increasing data size.
Cloud Integration: Utilize AWS for processing vast amounts of data efficiently.
Reporting: Create a dashboard for obtaining insights from the collected data.

Services Used:
Amazon S3: Object storage service providing scalability, data availability, security, and performance.
AWS IAM: Identity and access management for secure management of AWS services and resources.
QuickSight: Scalable, serverless, machine learning-powered business intelligence (BI) service.
AWS Glue: Serverless data integration service for data discovery, preparation, and analytics.
AWS Lambda: Computing service for running code without managing servers.
AWS Athena: Interactive query service for querying data stored in Amazon S3.
Dataset Used:

The project utilizes a Kaggle dataset containing statistics (CSV files) on daily popular YouTube videos over several months. Each day, up to 200 trending videos are published for various locations. The dataset includes video title, channel title, publication time, tags, views, likes/dislikes, description, comment count, and category_id, which varies by region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

