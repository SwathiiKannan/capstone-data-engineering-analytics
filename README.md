# 🏁 Capstone Data Engineering & Analytics Project

An **end-to-end data engineering and analytics pipeline** built using Python, Apache Airflow, PostgreSQL and Power BI. The project covers everything from raw data ingestion to visualization.

---

## 🔁 Full End-to-End Data Pipeline Flow

1️⃣ Raw Excel File
↓
2️⃣ Clean using pandas (Python script)
↓
3️⃣ Load Clean Data to PostgreSQL (Data Warehouse)
↓
4️⃣ Schedule & Orchestrate using Apache Airflow
↓
5️⃣ Query using SQL (in PostgreSQL)
↓
6️⃣ Visualize in Power BI


## 🎯 Project Objective

To build a complete data pipeline and dashboard using a real-world dataset.  
This includes:

- Data ingestion
- ETL processing using Python & pandas
- Workflow orchestration using Apache Airflow
- Data warehousing-ready structure
- SQL querying for analysis
- Dashboarding using Power BI

---

## 🛠️ Tech Stack

- **Languages**: Python, SQL  
- **Tools & Libraries**:
  - `pandas`, `openpyxl` – for data transformation
  - `Apache Airflow` – for orchestration
  - `Power BI` – for dashboards
- **IDE**: VS Code  
- **Version Control**: Git + GitHub  
- **Data Storage**: PostgreSQL (Data Warehouse), Local filesystem
- **Environment**: Python 3.12 + pip packages (`requirements.txt`)

---

## 📦 Dataset Description

A global sales dataset containing over 51,000 transactions including customer, product, sales, and logistics data.

- **Source**: Kaggle – [Global Superstore 2016](https://www.kaggle.com/datasets)
- **Format**: `.xlsx` Excel file
- **Size**: 51,290 Rows × 24 Columns

### 🔑 Key Features

- `Order Date`, `Ship Date`: Order and shipping timeline
- `Customer ID`, `Segment`, `Region`, `Country`, etc.: Demographics
- `Product ID`, `Category`, `Sub-Category`: Product information
- `Sales`, `Discount`, `Profit`, `Shipping Cost`: Financial metrics
- `Ship Mode`, `Order Priority`: Order logistics

---

### 🧠 Use Cases

- Analyze **sales trends** globally
- Segment **customer behavior** by region
- Assess **profitability by product** and geography
- Evaluate **shipping efficiency** and delivery performance

---

### ⚠️ Data Quality Notes

- `Postal Code` is 80% missing → excluded from final model
- Other columns are well-structured with minimal cleanup needed
- Missing values handled with standard pandas operations (`dropna`, `fillna`)

---

## 🗂️ Project Structure


 





