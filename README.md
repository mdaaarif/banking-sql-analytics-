# Banking Data Analytics – End-to-End Project

## Project Overview
This project demonstrates an end-to-end data analytics workflow using a real-world banking dataset. The solution covers the complete lifecycle of data analytics — from raw data ingestion and transformation to SQL-driven analysis and interactive dashboarding.

The architecture is designed around a SQL-centric pipeline, where both Python analysis and Power BI dashboards are dynamically connected to a MySQL database, reflecting industry-standard analytics practices.

---

## Business Objective
Banks handle large volumes of customer and transaction data that must be analyzed efficiently to support decision-making.  
This project focuses on:
- Understanding customer distribution and account behavior
- Analyzing balances and transaction trends
- Enabling structured, query-driven analytics through SQL
- Delivering insights via interactive dashboards

---

## Tools & Technologies
- Python – Data cleaning, preprocessing, and exploratory analysis
- Pandas & NumPy – Data manipulation and transformation
- Matplotlib & Seaborn – Exploratory visualizations
- MySQL – Central relational database for structured storage and querying
- Power BI – Interactive dashboards connected directly to SQL
- Jupyter Notebook – Step-by-step analysis and transformation
- GitHub – Version control and documentation

---

## End-to-End Workflow
1. Raw banking data ingested from CSV and Excel formats  
2. Data cleaned and explored using Python  
3. Structured tables created and loaded into MySQL  
4. Python notebooks fetch data directly from SQL for analysis  
5. Power BI dashboards built on a live SQL connection  
6. Insights visualized and documented with screenshots  

---

## Dataset & Schema
- Source: Public banking dataset adapted for analytical use
- Storage: Relational schema implemented in MySQL  

Key entities include:
- Customers
- Accounts
- Transactions
- Balances
- Account types

---

## Analytical Tasks Performed
- Customer count and segmentation analysis  
- Account type distribution and balance comparison  
- Transaction trend analysis over time  
- SQL-based aggregations and KPI calculations  
- Cross-validation of insights using Python and Power BI  

---

## Power BI Dashboard
The Power BI dashboard connects directly to the MySQL database and provides insights on:
- Total customers and account balances  
- Distribution of account types  
- Customer segmentation patterns  
- Transaction and balance trends  

All visuals are powered by live SQL queries to ensure consistency and scalability.

---

## Python Analysis
The Jupyter Notebook includes:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Visualizations using Matplotlib and Seaborn
- SQL-backed data fetching (no static CSV dependency)

---

## Repository Structure
