# ☁️ Big Data Storage and Data Warehousing with AWS

## 🎓 Project Overview

This project was developed as part of my coursework at the University of Dundee. It focuses on designing a cloud-based data storage and analytics workflow using AWS services.

The project demonstrates how transactional retail data can be stored, modeled, and analyzed using:

* Amazon S3
* Amazon DynamoDB
* Amazon Redshift

It covers cloud storage, NoSQL design, SQL-based warehousing, and multidimensional analysis using data cubes.

---

## 🚀 Key Features

* Uploaded and managed transactional dataset in Amazon S3
* Imported data into DynamoDB for NoSQL storage
* Designed partition key strategy for query access
* Evaluated efficient and inefficient DynamoDB queries
* Loaded data into Amazon Redshift for SQL analysis
* Created data cubes and rollups for analytical queries

---

## 🛠️ Technologies Used

* AWS S3
* AWS DynamoDB
* Amazon Redshift
* SQL
* PartiQL

---

## ⚙️ Project Workflow

### 1. Cloud Storage with Amazon S3

The dataset was first uploaded to an Amazon S3 bucket for cloud-based storage and access.

### 2. NoSQL Modeling with DynamoDB

The dataset was imported into DynamoDB and modeled for efficient retrieval.
The project also explored:

* Partition key design
* Query performance
* Secondary indexes (GSI)

### 3. Data Warehousing with Redshift

The data was loaded into Amazon Redshift for analytical SQL queries, including:

* category analysis
* regional order analysis
* profit analysis
* customer segment insights

### 4. Data Cubes and Rollups

Data cubes were created to improve performance for repeated analytical queries and multidimensional summaries.

---

## 📊 Example Analytical Questions Answered

* How many product categories exist in the dataset?
* How many orders were there in each region?
* Which product category had the highest sales?
* Which states had the highest and lowest profit?
* Which sub-category had the most critical-priority orders?
* What was the total sales amount for the Small Business segment?

---

## 📂 Project Structure

```text
.
├── store.csv
├── README.md
└── AC51047 Assessment 1 Big Data Storage and Data warehousing.pdf
```

---

## 💡 What I Learned

* Designing cloud-based storage workflows
* Working with NoSQL databases in AWS
* Understanding partition keys and indexing in DynamoDB
* Performing SQL-based analysis in Redshift
* Building data cubes for faster multidimensional analysis

---

## 🔮 Future Improvements

* Add automated ETL pipeline for loading data
* Implement more optimized DynamoDB indexing strategies
* Visualize results with dashboards
* Use AWS Glue for data cataloging and transformation

---

## 👤 Author

Sarraj Alsammak
University of Dundee

---

> This project demonstrates my ability to work with cloud storage, NoSQL databases, and data warehousing solutions using AWS.
