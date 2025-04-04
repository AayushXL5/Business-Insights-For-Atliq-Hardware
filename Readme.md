# 📊 Business Insight 360 - AtliQ

## 🏗️ Data Warehousing at AtliQ

AtliQ’s data infrastructure is structured as a **scattered system** composed of multiple **Database Management Systems (DBMS)**, managed by various teams:

### 👨‍💻 Software Engineers manage:
- Sales Software  
- CRM Software  
- Survey data stored as **CSV files** in cloud platforms like SurveyMonkey

### 🧪 Data Engineers handle the **ETL (Extract, Transform, Load)** process:
- **Extract**: Pulling data from different systems  
- **Transform**: Formatting data (e.g., date formats, currency types)  
- **Load**: Storing clean data into a **Data Warehouse** (e.g., **MySQL**, **Snowflake**)

### 📈 Data Analysts are responsible for:
- Performing **data analysis** using the Data Warehouse  
- Creating **reports** and **dashboards** using **Power BI**  
- Delivering insights to support **strategic decision-making**

---

## ❓ Why Use a Data Warehouse?

Data analysis cannot be performed directly on **OLTP systems** (used for real-time transactions), as it may slow down performance for end-users.

Instead, data is moved into a **Data Warehouse** through the **ETL process**, where it’s optimized for:
- Running **complex queries**
- Performing **advanced analysis**
- Avoiding any disruption to live systems

---

## 🧹 Data Preparation in the Data Warehouse

To prepare data for analysis, the following steps are taken:
- **Clean**: Remove blanks, errors, duplicates  
- **Format**: Standardize currencies, dates, etc.  
- **Transform**: Adjust structure for easier analysis (e.g., create date tables)

A dedicated Data Warehouse enables AtliQ to process large-scale data efficiently while ensuring performance, consistency, and quality.

---

## 🗂️ AtliQ’s Data Catalog


- **DBMS Server Names**  
- **Table Names and Descriptions**  
- **Support Contacts for Data Engineering**

We are using the following servers for this project:
- `gdb041`  
- `gdb056`

✅ Once access is granted by the **Data Engineering team**, the data will be **imported into MySQL**, and the **Data Warehouse** setup will begin for reporting and visualization.

---

