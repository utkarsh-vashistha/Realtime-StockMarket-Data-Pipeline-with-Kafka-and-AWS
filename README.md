# Realtime-StockMarket-Data-Pipeline-with-Kafka-and-AWS

This project implements a real-time data crawling pipeline for stock market data using Kafka, AWS S3, EC2, and Athena.

## Overview

The aim of this project is to create a robust and scalable data pipeline that collects real-time stock market data, processes it, and stores it in AWS S3. The stored data can then be queried using AWS Athena for further analysis and insights.

## Architecture

1. **Kafka**: Used for real-time data ingestion from various stock market data sources.
2. **AWS S3**: Serves as the primary storage for processed data.
3. **AWS EC2**: Hosts the Kafka brokers, Zookeeper, and data processing services.
4. **AWS Athena**: Enables SQL-based querying of data stored in S3.
5. **Crawler**: Custom-built crawler that fetches stock market data and pushes it to Kafka.

## Features

- Real-time data ingestion with Kafka
- Scalable and fault-tolerant architecture
- Efficient data storage in AWS S3
- Powerful querying capabilities with AWS Athena
- Deployment and orchestration using AWS EC2

## Prerequisites

- AWS account with access to S3, EC2, and Athena
- Kafka and Zookeeper setup
- Python

