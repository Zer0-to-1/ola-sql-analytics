Ola SQL Analytics 🚖
- 📌 Overview

This project focuses on analyzing Ola ride booking data from Bengaluru using SQL. The goal is to clean, query, and extract meaningful insights from the dataset while supporting the analysis with Power BI visualizations.

Through this project, I aimed to strengthen my SQL query writing, data modeling, and business intelligence skills while working with a real-world styled dataset.

- 📂 Project Structure
ola-sql-analytics/
│
├── data/
│   └── ola_bengaluru.csv          # dataset (sample Ola booking records)
│
├── sql/
│   └── queries.sql                # SQL queries used for analysis
│
├── docs/
│   └── ola_project_report.pdf      # Detailed project report with outcomes
│
├── README.md                      # Project overview

- 🛠️ Tools & Technologies

MySQL Workbench – Data storage and SQL queries

SQL (DDL, DML, Aggregates, Joins, Subqueries, Window Functions)

Power BI – Dashboards & visualization of insights

Excel/CSV – Dataset format

- 📊 Dataset

The dataset contains ride booking information from Ola in Bengaluru, including:

Date & Time

Booking Status

Customer & Vehicle Details

Pickup & Drop Locations

Trip Values (fare, distance, turnaround time, cancellations, ratings, etc.)

- 🔍 Key SQL Queries & Analysis

Some of the main SQL operations performed:

Filtering completed vs. cancelled rides

Identifying peak booking times by hour/day

Analyzing ride distribution by vehicle type

Detecting cancellation patterns (by driver vs. customer)

Average fare, distance, and turnaround time per ride

Customer and driver rating distributions

- 📈 Power BI Insights

Dashboard summarizing ride demand across time and location

Visual breakdown of cancellation reasons

Vehicle type preferences among customers

KPI cards for average fare, distance, and customer ratings

(Screenshots can be added here if you don’t want to upload the .pbix file.)

- 🚀 How to Run

Clone the repository:

git clone https://github.com/<Zer0-to-1>/ola-sql-analytics.git


Import the dataset (ola_bengaluru.csv) into MySQL Workbench.

Run the SQL scripts from sql/queries.sql.

Open the Power BI dashboard (or view screenshots in /docs).

- 📄 Project Report

A detailed report (ola_project_report.pdf) is included in the docs/ folder, covering:

Queries used

Results and interpretations

Visual dashboards

Business insights and recommendations

- 🎯 Outcomes

Improved SQL query writing (aggregation, joins, filtering, grouping).

Derived insights on ride demand, cancellations, and performance metrics.

Created an interactive Power BI dashboard for business intelligence use.

- 🙌 Acknowledgments

This project is part of my Applied Data Analytics journey and demonstrates practical SQL + BI skills on real-world inspired data.
