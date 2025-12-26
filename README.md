# 🏦 Czechoslovakia Banking Financial Data Analysis
---
🔗 Live Preview :
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

---

## 🔍 Key Insights from Dashboards

### 📊 Executive Overview
- The bank serves **~5,000 clients** across **4,500+ accounts** with over **1 million transactions**.
- The **overall loan default rate is 11.14%**, indicating moderate credit risk.
- **Profitability fluctuates year-over-year**, with strong performance in **2018 and 2021**.
- **Hl. m. Praha** is the top-performing district in terms of account volume.
- Account types (**Savings, Salary, NRI**) are evenly distributed, ensuring revenue diversification.

---

### 👥 Demographic Analysis
- Client concentration is highest in **Hl. m. Praha**, followed by Karvina and Ostrava.
- Gender distribution is **balanced across districts**, indicating inclusive customer reach.
- Customers aged **50+ form the largest segment**, while **Under-25** is the smallest.
- Regional analysis highlights opportunities for **youth-focused banking products**.

---

### 📈 Bank Performance Over Time
- Transaction volumes show **steady long-term growth** with seasonal fluctuations.
- Profit trends indicate **financial resilience despite short-term volatility**.
- Peaks in **new account openings** align with periods of higher profitability.
- Performance dips around 2019–2020 suggest external or operational impacts.

---

### 💳 Account Usage & Profitability
- **Savings accounts** have the highest transaction volume.
- **NRI accounts generate the highest profit**, despite lower transaction counts.
- Average balances remain **consistent across all account types**.
- High transaction frequency does not always translate to higher profitability.

---

### 🏦 Cards & Loans: Profitability vs Risk
- **Gold cards dominate (~74%)**, making them the most popular card type.
- Card holders contribute significantly to revenue, generating **₹27.83M in profit**.
- Most loans are **running or successfully completed**, reflecting effective credit policies.
- Loan default rates vary by district, enabling **region-based risk assessment**.

---

### 💸 Expense & Cost Analysis
- **Withdrawals and remittances** are the primary contributors to operational expenses.
- Expense trends closely follow transaction volumes.
- **Salary accounts incur higher average transaction costs**.
- Cost optimization in high-volume operations can improve overall profitability.

---

## 🧾 Final Conclusion
This project demonstrates a complete **cloud-based banking analytics solution** using **AWS S3, Snowflake, and Power BI**.  
The analysis delivers insights into **customer behavior, financial performance, loan risk, and operational efficiency**.

Key takeaways include:
- Strong and diversified customer base
- Profitable card services and stable loan portfolio
- Opportunities in youth acquisition and cost optimization


