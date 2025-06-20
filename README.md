# Fintect-data-analysis-project

Dataset: fintech_data.csv
This dataset contains 1,200 transaction records from a fictional fintech company operating across multiple cities. It includes information about transaction type, customer account type, transaction channels, transaction amounts, fees, and net amounts, along with timestamps and branch data.

🎯 Project Objective
The goal of this project was to practice beginner to intermediate-level data analysis using Python and Pandas. You explored financial transactions over time, segmented data by cities, channels, and services, and visualized transaction trends to gain meaningful business insights.

📌 Dataset Columns
Date: The transaction date

Branch_ID: Branch where the transaction occurred

City: City location of the branch

Service_Type: Type of financial service (e.g. Money Transfer, Bill Payment)

Account_Type: Account category (Individual or Business)

Transaction_Amount: Total amount of the transaction

Transaction_Fee: Fee charged for the transaction

Currency: Transaction currency (NGN or USD)

Net_Amount: Amount received after deducting the fee

Channel: Platform used for the transaction (Mobile App, Web Portal, Agent Network)

🔧 Key Analysis Tasks Performed
📊 Exploratory Data Analysis
Loaded and cleaned the data

Converted the Date column to datetime

Verified data types and checked for missing values

📈 Visualizations
Line chart: Daily transaction trends over time

Bar chart: Total transaction amount by city

📑 Aggregations & Groupings
Grouped data by City to find transaction volumes

Grouped by Service_Type and Account_Type to summarize usage

Calculated total and average Transaction_Amount and Net_Amount per branch or channel

🧠 Insights
Identified high-performing cities and branches

Measured total fees generated (implied revenue)

Highlighted service types and account types with the most activity

📌 Tools Used
Pandas for data wrangling and analysis

Matplotlib for visualizations

Datetime functions for temporal analysis
