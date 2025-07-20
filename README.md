# Transaction Data Analysis Pipeline

## Overview
This project implements a comprehensive data analysis pipeline for e-commerce transactions, featuring:
1. **Data Processing Pipeline**: Cleans and transforms raw transaction data
2. **Analytical Engine**: Derives business insights using PySpark
3. **Data Quality Monitoring**: Includes validation checks

## Technical Components

### 1. Data Processing Pipeline
- **Data Ingestion**: Loads from Delta tables (`transaction` and `products`)
- **Data Joining**: Combines datasets on Product ID
- **Data Cleaning**: Standardizes column names (spaces/special chars to underscores)
- **Storage**: Saves as optimized Delta table (`combined_transaction_data`)

### 2. Analytical Features
- **Customer Analytics**: Average order value calculation
- **Product Analytics**: Popular products/categories identification
- **Channel Analysis**: Web/Mobile/In-Store performance
- **Campaign Tracking**: Marketing campaign effectiveness

## Project Structure
## Project Structure

| Folder/File                     | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| `CELEBAL-PROJECT/`              | **Main project root directory**                                             |
| ├── `notebooks/`                | Contains all Jupyter notebooks for analysis                                |
| │ └── `celebal_project_python_file.ipynb` | Main analysis notebook with PySpark code                                  |
| ├── `data/`                     | Sample data files                                                          |
| │ ├── `transaction/`            | Transaction data source files                                              |
| │ └── `products/`               | Product catalog data files                                                 |
| ├── `README.md`                 | Project documentation (this file)                                          |
| └── `.gitignore`                | Specifies files to exclude from version control                            |

## Installation & Setup

### Prerequisites
- Databricks environment
- PySpark 3.0+
- Delta Lake 1.0+

### Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/SARTHAKMAAN/CELEBAL-PROJECT.git
2. Upload the notebook to your Databricks workspace

---
## Future Enhancements
Real-time dashboard integration

Automated anomaly detection

Predictive analytics for customer behavior

CI/CD pipeline for deployment

Unit testing framework

---

## Author

- Sarthak Maan
- B.Tech Computer Science
- FINAL YEAR STUDENT
