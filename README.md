# Stock Market Kafka Real Time Data Engineering Project

## Introduction 
Execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

Used different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Process
- Kafka server is deployed in AWS EC2 instance 
- Streaming data is created from a dataset using pandas library
- Connected to EC2 instance through SSH to run the kafka server and zoo-keeper
- Streaming data is created by producer and received by consumer
- Consumer writes the data to AWS S3 instance
- Crawler is created in AWS Glue to traverse all the data and use to query in AWS Athena

## Architecture 
<img src="Architecture.jpg">

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka


