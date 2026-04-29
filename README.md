# 🔄 ETL Automation Pipeline - Network Inventory

Automated ETL pipeline that processes multiple data sources (CSV/Excel) to generate a clean, consolidated network inventory database, reducing data preparation time by 85%.

## 📊 Project Overview

This pipeline automates the extraction, transformation, and loading of medium voltage network inventory data from multiple sources, consolidating them into a single optimized Parquet file.

**Business Impact:**
- ⏱️ Reduced data preparation time from **2 hours to 15 minutes** (~87% reduction)
- 📈 Feeds **8 dashboards** and **10 recurring analyses**
- 📊 Processes **600K records** per run
- ✅ Improved data consistency and accuracy across the organization

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** - Data manipulation and transformation
- **NumPy** - Numerical operations

## 🗂️ Project Structure
```bash
etl-automation-pipeline/
├── README.md
├── requirements.txt
├── notebooks/
│ └── inventory_etl.ipynb # Main ETL notebook
└── data/
  ├── input/ # Sample input files (CSV/Excel)
  └── output/ # Generated parquet file


## 🚀 How It Works

### 1. **Extract**
- Reads multiple CSV and Excel files from different sources
- Handles various data formats and encodings
- Validates data integrity and structure

### 2. **Transform**
- **Data Cleaning:** Handles missing values, duplicates, and outliers
- **Feature Engineering:** Adds derived attributes needed for analysis
- **Data Type Conversions:** Ensures consistent types across sources
- **Normalization:** Standardizes formats and naming conventions

### 3. **Load**
- Consolidates all sources into a single Parquet file
- Optimized for downstream analytics and dashboard consumption
- Compressed format for efficient storage and fast querying

## 📈 Key Features

- ✅ Automated data quality checks
- ✅ Comprehensive error handling and logging
- ✅ Scalable to millions of records
- ✅ Reproducible and version-controlled process
- ✅ Well-documented code with markdown cells

## 💻 How to Run

### Prerequisites


# Install required libraries
pip install -r requirements.txt
Execution
Place input files in data/input/
Open notebooks/inventory_etl.ipynb in Jupyter
Run all cells
Output will be generated in data/output/inventory.parquet

📊 Sample Data
This repository includes sample data that represents the structure of the actual production data. 

The real implementation processes:

Multiple CSV files with cable network data
Excel files with transformer and installation data
600K total records across all sources

🎯 Use Cases
The consolidated inventory database feeds:

Real-time operational dashboards (Power BI)
Predictive maintenance models
Network planning analyses
Regulatory reporting
Asset management systems

📝 Notes
Sample data provided for demonstration purposes
Original pipeline runs weekly to update the consolidated inventory
Parquet format chosen for optimal compression and query performance

👤 Author

Federico Cantillana - Data Analyst & Team Lead
📧 Email: [fede.canti@gmail.com]
🔗 LinkedIn: [linkedin.com/in/fede-canti]
💼 Portfolio: [https://delicate-rise-79a.notion.site/PORTFOLIO-FEDERICO-CANTILLANA-348c0f38a1898064b29ad2f1c93d903c?]
