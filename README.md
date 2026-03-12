Tobacco Use and Health Risk Analysis using Big Data
📌 Project Overview

This project focuses on analyzing behavioral patterns and health risks associated with tobacco usage using large-scale healthcare datasets. The objective is to identify demographic trends, consumption patterns, and risk factors related to tobacco use.

The analysis uses Big Data technologies such as Hadoop, Apache Spark, and Google Cloud Platform to process and analyze large datasets obtained from the Behavioral Risk Factor Surveillance System (BRFSS). The results help identify high-risk demographic groups and provide insights that can support public health strategies and tobacco control initiatives.

🎯 Objective

To analyze tobacco usage trends across multiple demographic groups

To identify high-risk populations based on age, gender, and education levels

To process large healthcare datasets using Big Data technologies

To generate insights that can assist public health decision-making

📊 Dataset Description

Source: CDC Behavioral Risk Factor Surveillance System (BRFSS) & STATE Tobacco Activities Tracking and Evaluation System

Dataset Type: Healthcare survey data related to tobacco consumption

Years Covered: 2011 – 2019

Key Attributes

Tobacco usage prevalence

Frequency of tobacco consumption

Quit attempts

Demographic attributes (age, gender, education level)

The dataset provides valuable information to analyze behavioral patterns of tobacco consumption and identify potential health risks among different population groups.

🧠 System Architecture

This project uses a Big Data processing pipeline to manage and analyze large healthcare datasets.

Key Components

Google Cloud Platform (GCP)

Google Cloud Storage

Hadoop Ecosystem

Apache Spark

Hive

BigQuery

Dataproc Cluster

The architecture enables scalable data ingestion, processing, and analysis for large datasets.

⚙️ Project Workflow
1. Data Acquisition

Data was collected from the BRFSS Survey Dataset, which provides nationwide behavioral health information related to tobacco use.

2. Data Storage

The dataset was stored in Google Cloud Storage, using a storage bucket created for managing the tobacco dataset.

3. Big Data Infrastructure Setup

A Google Cloud Dataproc cluster was created with Hadoop, Hive, and Spark services enabled to support distributed processing of the dataset.

4. Data Cleaning

Data preprocessing was performed using PySpark, including:

Handling missing values

Standardizing data formats

Filtering relevant attributes

5. Data Preprocessing

Using BigQuery, unnecessary columns were removed and a cleaned dataset schema was created for further analysis.

6. Data Analysis

Analytical queries were performed to identify trends in tobacco usage across different demographic groups.

📈 Key Insights
Gender-Based Analysis

The analysis revealed that males consistently show higher tobacco usage rates compared to females, indicating potential gender-based health risk differences.

Age-Based Analysis

The 25–44 age group showed the highest average tobacco consumption, indicating increased addiction risks among young adults.

Year-Based Analysis

Certain years, particularly 2013, showed peaks in tobacco usage trends, suggesting possible environmental or policy influences affecting tobacco consumption.

🛠️ Technologies & Tools Used
Programming

Python

SQL

Big Data Technologies

Hadoop

Apache Spark

Hive

Cloud Platform

Google Cloud Platform (GCP)

Google Cloud Storage

BigQuery

Dataproc

Data Processing Tools

PySpark

OpenRefine


👥 Team Members

Nandini Nagiri

Vamshi Kalyan Yerramilli

Vijay Venkatarao Goparaju

Bala Phaneendra Pothuri

Jaya Sai Krishna Paleru

📚 References

CDC Behavioral Risk Factor Surveillance System (BRFSS)

CDC STATE Tobacco Activities Tracking and Evaluation System

Public Health Research on Tobacco Usag
