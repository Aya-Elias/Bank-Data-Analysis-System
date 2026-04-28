# 🏦 Digilians Bank: Full-Cycle Data Management & Financial Intelligence

## 📌 Project Overview
This project is a comprehensive simulation of a banking data ecosystem. It demonstrates proficiency in **Database Design (ERD)**, **Complex Data Engineering (T-SQL)**, and **Business Intelligence (Power BI)**. The system manages everything from branch operations and employee roles to automated transaction monitoring and customer risk assessment.

## 📁 Detailed File Breakdown

### 1. 🏗️ Data Architecture & Design
* **`ERD.jpg`**: A visual representation of the database's Entity Relationship Diagram, showing the 10+ core entities and their relational constraints.
* **`Schema.png`**: The physical data model showcasing table structures, data types, and the relational mapping between accounts, customers, and branches.

### 2. 💻 Database Engineering (SQL Server)
* **`Database creation.sql`**: The fundamental script that builds the entire environment. It includes:
    * Table definitions for `Branches`, `Customers`, `Accounts`, `Transactions`, `Loans`, `Services`, etc.
    * Enforcement of **Referential Integrity** using Primary/Foreign Keys and specific `ON DELETE/UPDATE` behaviors.
* **`Insertion codes.sql`**: A highly advanced script used for **Data Seeding**. It utilizes:
    * **T-SQL WHILE Loops**: To dynamically generate 500+ realistic records for each table.
    * **Randomization Logic**: To distribute data across different cities (Cairo, Dubai, London, Berlin) and countries.
* **`Question codes.sql`**: The analytical brain of the project. It features:
    * **Advanced Views**: Like `vw_CustomerMaster_J` and `vw_AccountPortfolio_J` for real-time reporting.
    * **Financial Risk Detection**: Logic that flags transactions based on **Statistical Deviations** (Mean + 3x Standard Deviation) or when a debit exceeds 80% of the account balance.

### 3. 📊 Data Visualization & BI
* **`Dashboardd.pbix`**: The master Power BI file that connects all SQL data to interactive visuals.
* **`image_e031b6.png`**: A preview of the analytical dashboard, highlighting key performance indicators (KPIs) like liquidity and credit score distribution.

## 🛠️ Key Technical Competencies
* **Architecture:** Relational Modeling & Database Normalization.
* **Data Engineering:** T-SQL Scripting, Loops, Variables, and Logic-based Data Population.
* **Advanced Analytics:** Using Statistical functions (STDEV, AVG) for anomaly detection in financial data.
* **Data Storytelling:** Building end-to-end dashboards for executive decision-making.

---
**Connect with me on [LinkedIn](YOUR_LINKEDIN_URL_HERE) to discuss Data Engineering & Analytics!**
