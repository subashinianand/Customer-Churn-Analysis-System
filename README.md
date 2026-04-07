Customer Churn Analysis System (Synthetic Data)
 Project Overview
Customer churn is a major challenge for businesses like banks, telecom companies, and subscription services. When customers 
stop using a service, it leads to revenue loss and increased costs.This project focuses on building a Customer Churn Analysis 
System using synthetic data and performing Exploratory Data Analysis (EDA) to identify patterns, trends, and factors affecting customer churn.

 Objectives
Generate realistic synthetic customer dataset
Perform data cleaning and preprocessing
Analyze customer behavior using statistical methods
Identify high-risk churn segments
Visualize data using graphs and charts
Extract meaningful insights for business decisions

 Dataset Description
The dataset contains 100,000 synthetic customer records with the following columns:

Column Name	Description
Customer_ID	Unique identifier
Age	Customer age (18–70)
Gender	Male / Female
Tenure	Years with company (0–10)
Balance	Account balance (0–200,000)
CreditScore	Credit score (300–900)
EstimatedSalary	Annual income (10,000–150,000)
NumOfProducts	Number of products used (1–4)
IsActiveMember	Yes / No
Churn	0 = No, 1 = Yes
⚙️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn

Project Workflow
1. Data Generation
Created synthetic dataset using NumPy and Pandas
Simulated real-world customer behavior
2. Data Cleaning & Preprocessing
Checked missing values
Removed duplicates
Converted categorical variables into numeric format
3. Descriptive Statistics
Calculated Mean, Median, Mode
Analyzed standard deviation and data distribution
4. Churn Analysis
Identified high churn and low churn customers
Compared churn vs non-churn groups
5. Group-Based Analysis
Age group vs churn
Gender vs churn
Active vs inactive users
Product usage vs churn
6. Relationship Analysis
Balance vs churn
Credit score vs churn
Tenure vs churn
7. Data Visualization
Bar charts
<img width="827" height="613" alt="image" src="https://github.com/user-attachments/assets/77f0fe89-e5d3-496f-8fe8-c73a0e98e196" />

Pie charts
<img width="702" height="503" alt="image" src="https://github.com/user-attachments/assets/7db34e65-da84-4303-97ee-368aa29b6636" />

Histograms
<img width="856" height="608" alt="image" src="https://github.com/user-attachments/assets/ea121e91-8990-4786-8b31-82b021bc92cc" />

Scatter plots
<img width="885" height="652" alt="image" src="https://github.com/user-attachments/assets/5ef72284-3e21-47f5-9832-801aeadb2eeb" />

Box plots 
<img width="859" height="616" alt="image" src="https://github.com/user-attachments/assets/da746346-4a46-42ec-baba-551e2cabb865" />

Heatmaps
<img width="1014" height="694" alt="image" src="https://github.com/user-attachments/assets/a8d2e511-7600-4571-960d-2bbab9c1b072" />


 Key Insights
 
Customers with low balance and low tenure are more likely to churn
Inactive members show higher churn rates
Customers using fewer products tend to leave more
Lower credit score customers have slightly higher churn probability

 Conclusion
       This project demonstrates how synthetic data can be used to perform meaningful customer churn analysis. 
The insights obtained can help businesses:

Improve customer retention strategies
Identify high-risk customers early
Enhance overall customer satisfaction
