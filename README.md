Hospital Management SQL Project


Introduction

This project simulates a hospital management system using structured data and SQL queries. The purpose is to analyze hospital data, gain meaningful insights, and practice SQL operations including joins, filtering, grouping, and aggregations.

Problem Statement

Hospitals deal with large amounts of data related to patients, doctors, and appointments. Managing this data efficiently and extracting valuable insights is crucial for improving patient care and operational efficiency. This project addresses how structured query language (SQL) can be used to perform such analysis.

Datasets

The project includes three CSV files:

Patients.csv: Patient demographic data.

Doctors.csv: Details about each doctor, including their specialty.

Appointments.csv: Records of patient appointments including date, time, and reasons.

Data Cleaning

Ensured all IDs are unique and properly formatted.

Checked for null values and missing data.

Verified all foreign key relationships are consistent.

Standardized formats (e.g., date format in Appointments.csv).

Questions

Doctors who haven’t conducted any appointments.

Patients with more than 2 appointments in a day.

Appointments for reasons like 'Fever' or 'Cough'.

Doctor with the highest number of female patients.

Patients with appointments from different specialties.

Youngest patient with at least one appointment.

Specialty with the most appointments.

Count of male and female patients each doctor treated.

Appointments in the last 7 days.

Doctors who have weekend appointments.

Data Insights

Identified idle doctors who have never been assigned to patients.

Determined peak days and reasons for appointments.

Highlighted gender patterns in doctor-patient interactions.

Found patients who frequently visit multiple departments.

Conclusion
This project demonstrates the power of SQL in extracting actionable insights from structured hospital data. With the help of relational databases, we can analyze healthcare operations and improve decision-making.

Tool Used
MySQL for database creation, query execution, and analysis.

Excel for initial data inspection and formatting.


License
This project is open-source and free to use for learning and educational purposes.




