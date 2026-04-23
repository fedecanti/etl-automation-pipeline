# 🔄 ETL Automation Pipeline - Inventory Management

Automated ETL pipeline that processes multiple data sources (CSV/Excel) to generate a clean, consolidated inventory database, reducing data preparation time by 87%.

## 📊 Project Overview

This pipeline automates the extraction, transformation, and loading of network inventory data from multiple sources, including:
- Cable network data
- Transformer installations
- Customer installations
- Geographic data

**Business Impact:**
- ⏱️ Reduced data preparation time from **2 hours to 15 minutes** (~87% reduction)
- 📈 Feeds **8 dashboards** and **10 recurring analyses**
- 📊 Processes **100K-3M records** per run
- ✅ Improved data consistency and accuracy

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** - Data manipulation and transformation
- **NumPy** - Numerical operations
- **OpenPyXL** - Excel file processing
- **PyArrow** - Parquet file generation

## 🗂️ Project Structure

etl-automation-pipeline/
├── notebooks/
│ └── inventory_etl.ipynb # Main ETL notebook
├── data/
│ ├── input/ # Sample input files
│ └── output/ # Generated parquet file
├── requirements.txt
└── README.md


## 🚀 How It Works

### 1. **Extract**
- Reads multiple CSV and Excel files
- Handles different data formats and encodings
- Validates data integrity

### 2. **Transform**
- Data cleaning (missing values, duplicates, outliers)
- Feature engineering (derived attributes)
- Data type conversions
- Normalization and standardization

### 3. **Load**
- Consolidates into single Parquet file
- Optimized for downstream analytics
- Compressed format for efficient storage

## 📈 Key Features

- ✅ Automated data quality checks
- ✅ Error handling and logging
- ✅ Scalable to millions of records
- ✅ Reproducible and version-controlled
- ✅ Well-documented code

## 💻 How to Run

### Prerequisites
```bash
pip install -r requirements.txt
Execution
Place input files in data/input/
Open and run notebooks/inventory_etl.ipynb
Output will be generated in data/output/inventory.parquet
📊 Sample Results
[Aquí podrías poner un screenshot de estadísticas o tabla de ejemplo]

📝 Notes
Sample data provided represents the structure but not real business data
Original implementation processes 100K-3M records across multiple data sources
Pipeline runs weekly to update consolidated inventory
👤 Author
Federico Cantillana - Data Analyst
LinkedIn | Portfolio
