# Walmart Data Engineering & Analytics Project


##  Project Overview

This project demonstrates an **end-to-end data pipeline** using the Walmart sales dataset.  
The goal is to **collect, clean, process, analyze, and store data** in a relational database for business insights and reporting.

The project uses **Python** for data processing and **MySQL** for analytical querying, following real-world **ETL (Extract, Transform, Load)** and **SQL-based business analysis** practices.

```

## 🧩 Project Architecture (Pipeline)



Kaggle Walmart Dataset
↓
API / CSV
↓
Python (Pandas)

Data Cleaning

Data Processing
↓
MySQL Database (RDBMS)
↓
SQL Queries for Business Analysis 

```
##  Dataset Description

- **Source:** Kaggle – Walmart Sales Dataset  
- **Format:** CSV  

### Data Includes:
- Store and branch information  
- Product categories  
- Sales, revenue, and profit  
- Date and time attributes  
- Quantity, pricing, and payment methods  

```
##  Technologies Used

### Programming & Libraries
- **Python**
- **Pandas** – Data manipulation and cleaning  
- **SQLAlchemy** – Database ORM  
- **PyMySQL** – MySQL connector  

### Database
- **MySQL (RDBMS)**  

### Tools
- Jupyter Notebook  
- Kaggle Dataset  
- Git & GitHub  

```
##  Features

- Data ingestion from Kaggle dataset  
- Data cleaning and preprocessing using Pandas  
- Handling missing and inconsistent values  
- Loading structured data into MySQL  
- Performing **advanced SQL queries** for business insights  

```

##  Data Processing Steps

### 1️⃣ Extract
- Download Walmart dataset from Kaggle  
- Load CSV file into Pandas DataFrame  

### 2️⃣ Transform
- Remove duplicates  
- Handle missing values  
- Convert date and time formats  
- Rename columns for consistency  

### 3️⃣ Load
- Create MySQL database and tables  
- Insert cleaned data using SQLAlchemy & PyMySQL  

```

##  MySQL Business Queries & Analysis

After loading the cleaned data into MySQL, multiple **analytical SQL queries** were executed to solve real-world business problems.

###  Key SQL Analyses Performed
- Total number of transactions and records  
- Distribution of payment methods  
- Quantity sold by payment method  
- Branch-wise and city-wise sales analysis  
- Highest-rated product categories per branch  
- Busiest day of the week for each branch  
- Total profit calculation per category  
- Preferred payment method per branch  
- Sales distribution by time shifts  
- Year-over-year revenue comparison  
- Top 5 cities by total revenue  
- Monthly sales trend analysis  
- Average transaction value per branch  

 **All SQL queries are available in:**  
`mysql_queries.sql`

```

## 🗂️ Project Structure

Walmart-Project/
│
├── Walmart.csv
├── walmart_clean_data.csv
├── project.ipynb
├── mysql_queries.sql
├── requirements.txt
├── project-pipeline.jpg
└── README.md

```

##  How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Walmart-Project.git
cd Walmart-Project
2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Setup MySQL

Create a MySQL database

Update database credentials in the Python script

4️⃣ Run the Notebook
jupyter notebook project.ipynb

5️⃣ Execute SQL Queries

Open mysql_queries.sql

Run queries in MySQL Workbench or CLI

📈 Output

Cleaned Walmart sales dataset

Structured data stored in MySQL

Actionable business insights using SQL

 Use Cases

Retail sales analysis

Business intelligence reporting

Data engineering practice

SQL analytics & decision-making

Python–MySQL integration learning

Future Enhancements

Power BI / Tableau dashboards

Automated ETL using Apache Airflow

REST API for query access

Machine learning models for sales forecasting

👤 Author

Gunnala Krishna Prasad
B.Tech Computer Science Student
Data Engineering & Full Stack Enthusiast


