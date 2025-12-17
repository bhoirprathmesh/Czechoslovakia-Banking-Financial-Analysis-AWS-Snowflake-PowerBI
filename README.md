# 🏦 Czechoslovakia Banking Financial Data Analysis
---
🔗 Live Preview : (Working Phase)
https://app.powerbi.com/reportEmbed?reportId=c6909367-06ca-4834-ac5a-91838cc301a0&autoAuth=true&ctid=d1244466-1f7c-462f-810c-84815a170943

## 📌 Overview
The **Czechoslovakia Banking Financial Data Analysis** project focuses on analyzing historical banking data to uncover insights into customer behavior, financial performance, and operational efficiency.  
The dataset represents anonymized banking transactions and customer details collected over multiple years, enabling in-depth exploratory and analytical reporting.

This project demonstrates an **end-to-end data analytics pipeline**, starting from raw data storage to interactive dashboard visualization.

---

## 🎯 Business Problem
The banking institution aims to leverage its historical financial data to:

- Understand customer demographics and regional distribution
- Analyze account usage and transaction behavior
- Evaluate loan performance and financial trends over time
- Identify profitability drivers and cost optimization opportunities
- Support data-driven decision-making for introducing new financial products

The challenge is to integrate large-scale financial data from multiple sources and transform it into actionable business insights.

---

## 📊 Dataset Overview
The **Czechoslovakia Banking Financial Dataset** contains structured financial and demographic information provided in the source PDF.  
The dataset includes the following core tables:

- **Account** – Account details, creation date, account type, and linked clients  
- **Card** – Card issuance details and card types  
- **Client** – Customer demographic information such as birthdate, gender, and district  
- **Disposition** – Relationship between clients and accounts (owner, authorized user, etc.)  
- **District** – Regional demographic and economic indicators  
- **Loan** – Loan details including amount and issue date  
- **Order** – Standing orders and payment instructions  
- **Transaction** – Detailed transaction records including type and amount  

The data is anonymized and spans multiple years, making it suitable for financial trend and performance analysis.

---

## 🛠 Tools & Technologies
The following tools and platforms were used in this project:

- **AWS S3** – Cloud storage for raw Excel banking data  
- **Snowflake** – Cloud data warehouse for data ingestion, transformation, and querying  
- **Power BI** – Data visualization and interactive dashboard creation  
- **SQL** – Data modeling, transformations, and analytical queries  
- **Excel** – Initial data source and validation  

---

## 🔄 Approach
1. **Data Storage**  
   - Raw banking financial data (Excel files) was stored securely in **AWS S3**.

2. **Data Ingestion**  
   - Data from AWS S3 was ingested into **Snowflake** for centralized storage and processing.

3. **Data Transformation & Modeling**  
   - Data cleaning, formatting, and relational modeling were performed using SQL in Snowflake.

4. **Data Visualization**  
   - Cleaned and structured data was connected to **Power BI**.
   - Interactive dashboards were built to analyze financial trends, customer demographics, and banking performance.

---

## 📈 Outcome
- Built a scalable cloud-based data pipeline  
- Enabled business-friendly dashboards for decision-makers  
- Delivered insights into customer behavior, regional trends, and financial performance  

---

## 📂 Data Source
- Czech Financial Dataset (Anonymized Transactions)  
  Source: Data World
  Link: https://data.world/lpetrocelli/czech-financial-dataset-real-anonymized-transactions

