# 🏦 Core Banking Data Pipeline

> End-to-end data engineering project simulating a *core banking transaction pipeline,* *focused on data quality, governance and auditability*.

---

## 📖 Overview
This project simulates how *banks and fintechs* process financial transactions through a structured and reliable *data pipeline*.

It covers the full data lifecycle — from ingestion to analytics-ready tables — following *real-world data engineering best practices* commonly used in the financial sector.

---

## 🎯 Project Goals
✔ Simulate a core banking transaction flow  
✔ Build a reliable and auditable pipeline  
✔ Apply validation rules for financial data  
✔ Model data using fact and dimension tables  
✔ Prepare data for

---

## 🧱 Architecture
Data Sources ↓ Ingestion Layer ↓ Validation & Transformation ↓ Relational Database ↓ Analytics Ready Tables

---

## 🔄 Pipeline Flow
1. *Ingestion*
   - Simulated transaction, account and customer data (CSV/JSON)

2. *Validation & Transformation*
   - Standardization of dates and monetary values  
   - Detection of invalid, duplicated or inconsistent records  

3. *Storage*
   - Relational database (PostgreSQL/MySQL)  
   - Dimensional modeling (Star Schema)

4. *Analytics Layer*
   - Clean and structured tables ready for analysis and reporting  

---

## 🗃️ Data Model
### Fact Table
- fact_transactions

### Dimension Tables
- dim_customers
- dim_accounts
- dim_transaction_types
- dim_time

This structure supports *efficient querying* and *business analysis*.

---

## 🛠️ Tech Stack
- *Python* – data processing
- *SQL* – data modeling and queries
- *PostgreSQL / MySQL*
- *Git & GitHub*
- *Docker* (optional)

---

## ✅ Data Quality & Governance
The pipeline enforces:
- Validation rules for financial transactions  
- Duplicate detection  
- Consistency and integrity checks  
- Clear documentation and data dictionary  

These practices are critical in *banking environments*.

---

## 🤝 Collaboration
This is a *collaborative project, developed by contributors from **Portugal and Brazil*, simulating international teamwork in data engineering projects.

---

## 🚀 Future Improvements
- Workflow orchestration (Airflow / Prefect)  
- Open Banking API simulation  
- Monitoring & alerting  
- Cloud deployment (AWS / GCP / Azure)

---

## 🏷️ Tags
data-engineering banking etl financial-data python sql
