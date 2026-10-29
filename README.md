# PRSQL-02: Medical Data History (SQL Project)

## 📌 Project Overview
This project contains an advanced SQL assignment focused on querying and managing a medical database using MySQL Workbench. The analysis involves complex database operations across multiple relational tables, including patients, doctors, admissions, and province names.

## 🗄️ Database Schema & Relational Structure
* **Patients Table:** Stores personal demographics, contact details, physical attributes (height, weight), allergies, and regional mapping (`province_id`).
* **Doctors Table:** Contains medical professional details, including names and specialties.
* **Admissions Table:** Tracks hospital admissions, discharge dates, attending doctors, and medical diagnoses.
* **Province Names Table:** Maps province IDs to full province names.

## 🛠️ Key SQL Techniques & Queries Implemented
* **Filtering & Conditions:** Used `WHERE`, `LIKE`, `BETWEEN`, and `IS NULL` to filter specific patient demographics and medical history.
* **Data Updates & Manipulation:** Performed `UPDATE` operations to handle null values (e.g., setting default values like 'NKA' for allergies).
* **String & Date Functions:** Implemented `CONCAT`, `UPPER`, `LOWER`, `LENGTH`, `YEAR`, and `DAY` for text manipulation and date-based extraction.
* **Joins & Unions:** Used `INNER JOIN` across multiple tables to map patients with their respective doctors and diagnoses, along with `UNION` operations.
* **Aggregations & Grouping:** Applied `GROUP BY`, `HAVING`, `COUNT`, `SUM`, `MAX`, `MIN`, and `DISTINCT` to analyze data trends, patient counts by city/weight groups, and allergy popularity.
* **Conditional Logic:** Utilized `CASE WHEN` statements to categorize data (e.g., calculating obesity status based on BMI and segregating patient counts by gender).

## 📁 Repository Contents
* `PTID-CDA-OCT-26-11137_Medical_Data_History.pdf`: Comprehensive project report featuring 34 executed SQL queries, schema diagrams, and MySQL Workbench execution screenshots.
