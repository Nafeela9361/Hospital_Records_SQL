# Hospital Records Management -SQL

## 📌 Project Overview

This project is a **Hospital Records Management System** developed using **MySQL**. It demonstrates how SQL can be used to store, manage, analyze, and extract meaningful insights from hospital patient records.

The database contains information about patients, including demographics, diseases, health indicators, treatment costs, admission and discharge dates, and smoking status.

## 🗄️ Database Structure

**Database:** `Hospital`
**Table:** `PatientRecords`
**Records:** 200 patient records

### Columns

| Column        | Description                          |
| ------------- | ------------------------------------ |
| PatientID     | Unique patient identification number |
| PatientName   | Patient's name                       |
| Gender        | Patient's gender                     |
| Age           | Patient's age                        |
| City          | Patient's city                       |
| Disease       | Diagnosed disease                    |
| BloodPressure | Blood pressure reading               |
| Cholesterol   | Cholesterol level                    |
| BMI           | Body Mass Index                      |
| SmokingStatus | Smoking status                       |
| TreatmentCost | Cost of treatment                    |
| AdmissionDate | Hospital admission date              |
| DischargeDate | Hospital discharge date              |

## 🔍 SQL Concepts Demonstrated

This project covers a wide range of SQL concepts:

* Database and table creation
* Data insertion using `INSERT INTO`
* Data retrieval using `SELECT`
* Filtering using `WHERE`
* Sorting using `ORDER BY`
* Grouping using `GROUP BY`
* Aggregate functions:

  * `COUNT()`
  * `SUM()`
  * `AVG()`
  * `MAX()`
  * `MIN()`
* Subqueries
* `ROUND()` for numerical formatting
* `DATEDIFF()` for calculating hospital stay duration
* Percentage calculations
* Disease-wise and city-wise analysis
* Conditional filtering
* Ranking results using `LIMIT`

## 📊 Analysis Performed

The project contains **50 SQL queries** covering:

### Patient Analysis

* Total number of registered patients
* Average, youngest, and oldest patient age
* Male and female patient distribution
* Gender percentages
* Patient contribution by city

### Disease Analysis

* Most and least common diseases
* Heart Disease and Diabetes patient counts
* Hypertension percentage
* Average age by disease
* Disease distribution across cities
* City with the highest number of Heart Disease patients

### Treatment Cost Analysis

* Total treatment revenue
* Average, maximum, and minimum treatment costs
* Disease generating the highest/lowest revenue
* Average treatment cost by disease
* Highest-cost patient
* City generating the highest treatment revenue
* Patients whose treatment cost is above average

### Hospital Stay Analysis

* Average hospital stay
* Maximum and minimum stay duration
* Patient with the longest stay
* Disease with the longest/shortest average stay
* Average stay by city
* Patients staying more than 10 days
* Patients staying less than 5 days
* Percentage of patients staying above the average duration

### Health Indicator Analysis

* Average blood pressure
* Average cholesterol
* Average BMI
* Patients with high blood pressure
* Patients with high cholesterol
* Patients with BMI above 30
* Disease with the highest average BP, cholesterol, and BMI

### Smoking Analysis

* Number of smokers and non-smokers

## 🎯 Learning Outcomes

Through this project, I practiced:

* Writing SQL queries for real-world healthcare data
* Performing exploratory data analysis using SQL
* Working with aggregate functions and subqueries
* Analyzing data using grouping and filtering
* Calculating percentages and averages
* Performing date-based calculations
* Extracting business and healthcare insights from structured data

## 🛠️ Tools & Technologies

* **Database:** MySQL
* **Language:** SQL
* **Dataset:** Hospital Patient Records
* **Environment:** MySQL Workbench

## 📁 Project Structure

```text
Hospital-Records-Management/
│
├── Hospital_Records.sql
└── README.md
```

## 🚀 How to Run

1. Open **MySQL Workbench**.
2. Create/open the SQL script.
3. Execute the database and table creation statements.
4. Insert the patient records.
5. Run the SQL queries from Q1–Q50 to perform the analysis.

## 👩‍💻 Author

**Nafeela Beer**
