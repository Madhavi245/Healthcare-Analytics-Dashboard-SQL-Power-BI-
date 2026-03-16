🏥 Healthcare Analytics Dashboard – SQL & Power BI

This project presents an end-to-end healthcare data analytics solution built using SQL Server and Power BI. The goal is to transform raw hospital admission data into a structured analytical model and create an interactive dashboard that provides insights into patient trends, hospital performance, and billing analysis.

The project demonstrates data cleaning, dimensional modelling (Star Schema), SQL-based data transformation, and Power BI dashboard visualization.

📌 Project Objectives

The main objectives of this project are:

Clean and transform raw healthcare data using SQL.

Build a data warehouse schema for efficient analytics.

Create an interactive Power BI dashboard for hospital performance monitoring.

Generate insights into patient admissions, billing patterns, and healthcare service performance.

🧹 Data Preparation (SQL Server)

The raw dataset contains hospital admission records including patient information, diagnosis, billing amount, and admission dates.

Key data preparation tasks include:

Data cleaning and validation

Handling missing values

Removing duplicate records

Creating structured dimension tables

Building a central fact table for analytical queries

⭐ Data Model – Star Schema

To improve performance and simplify analysis, the dataset was transformed into a Star Schema.

Dimension Tables

dim_patient – Patient information such as gender and patient details

dim_doctor – Doctor information

dim_department – Hospital department details

dim_date – Admission and discharge date attributes

Fact Table

fact_admissions

Billing Amount

Admission Date

Discharge Date

Foreign keys linking all dimensions

This structure supports fast reporting and scalable analytics.

📊 Power BI Dashboard Features

The interactive Power BI dashboard provides the following insights:

Key Metrics (KPIs)

Total Patients

Total Revenue

Average Billing Amount

Average Length of Stay

Visualizations

Monthly patient admission trends

Gender-based patient analysis

Top 5 doctors by patients

Revenue by Insurance provider

Admissions by Type

🛠 Tools & Technologies

SQL Server Management Studio (SSMS)

SQL

Power BI

Data Modeling (Star Schema)

Data Visualization
