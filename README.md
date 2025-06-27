# capstone-data-engineering-analytics
End-to-end data engineering & analytics project

## Project Objective
To build an end-to-end data pipeline and dashboard using real world dataset.
This project will invlove data ingestion,ETL, data warehousing, SQL Querying, BI Dashboarding.

## Tech Stack
- **Languages**: Python, SQL
- **Data Storage**: Data Lake
- **ETL Tools**:
- **Data Modelling**:
- **BI Tool**: Power BI
- **Orchestration**:
- **Version Control**:

## Dataset Description
This dataset captures global sales transactions including customer info, product details, sales amounts, and shipping data over multiple years. It combines categorical, numerical, and datetime fields, making it ideal for diverse analyses.
- **Source**: The data was sourced from Kaggle's "global_superstore_2016.xlsx" dataset.
- **Format**: Excel Files (.xlsx)
- **Size**: 51,290 Rows X 24 Columns
- **Features Overview**:
  - `Order Date`, `Ship Date`: Dates related to customer orders and shipping.
  - `Customer ID`, `Customer Name`: Customer identity information.
  - `Segment`, `Region`, `Country`, `City`, `State`: Customer demographics and regional data.
  - `Product ID`, `Product Name`, `Category`, `Sub-Category`: Product details.
  - `Sales`, `Quantity`, `Discount`, `Profit`, `Shipping Cost`: Key sales and financial metrics.
  - `Ship Mode`, `Order Priority`: Logistics and prioritization details.
- **Key Use Cases**:
  - Evaluate global sales performance and trends
  - Segment customers by purchase behavior and demographics
  - Analyze shipping efficiency and delivery timelines
  - Measure profitability by product and region
- **Data Quality**:
  - The Postal Code column has 80% missing values and should be used cautiously or excluded in location-based analyses.
  - Other data fields are clean and well-structured, supporting reliable exploratory analysis and visualization.
 
## Data Storage
The raw dataset is stored in **Azure Data Lake Storage Gen2**, providing a centralized location for all raw data and scalable capacity to accommodate future data growth.

  - **Storage Account**: `capstonestorage79`
  - **Container Name**: `raw-data-globalsuperstore`
  - **File(s)**: `global_superstore_20161.xlsx`

This serves as the landing zone for raw data before the ETL process begins. Files were uploaded manually using the Azure Portal interface. The hierarchical namespace was enabled during storage account creation to support Data Lake Gen2 features.

Public access is disabled to maintain security. Data is accessed programmatically using Python during the ETL process. Below is a screenshot showing the file stored in the Azure container:
![Azure Blob Properties Screenshot](./Screenshots/azure_storage.png?raw=true)





