# Data Engineering YouTube Analysis Project 

## Overview

This project focuses on efficiently managing, organizing, and analyzing YouTube video data based on different video categories and trending metrics. The project handles both structured and semi-structured data to provide insights into YouTube trends.

## Project Goals
1. Data Ingestion — Develop a system to collect data from multiple sources.
2. ETL System — Convert raw data into a usable format for analysis.
3. Data lake — Create a centralized storage system to manage large amounts of data from various sources.
4. Scalability — Ensure the system can handle growing data volumes without performance issues.
5. Cloud Integration — Use cloud services (AWS) to process large datasets that cannot be handled locally.
6. Reporting — Create dashboards to answer key business questions using the analyzed data.
 
## Tools and Services Used
1. Amazon S3: Stores and secures large data sets with scalability and high availability.
2. AWS IAM: Manages secure access to AWS services and resources.
3. QuickSight: A cloud-based business intelligence tool for creating reports and visualizations.
4. AWS Glue: A service to discover, prepare, and combine data for analysis and machine learning.
5. AWS Lambda: Runs code without managing servers, enabling efficient data processing.
6. AWS Athena: An interactive query service to analyze data directly from S3.

## Dataset Used
The dataset used is from Kaggle, which contains daily statistics on popular YouTube videos. It includes up to 200 trending videos each day from different regions. The dataset provides information such as video title, channel, views, likes, dislikes, and comment count. It also includes a category_id for each region, stored in a JSON file.
https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">
 
