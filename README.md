# Big Data Data Science - Extract, Transform, Load (ETL)

## Project Overview
The Big Data Data Science Extract, Transform, Load (ETL) project provides a robust architecture for managing large datasets. This project aims to facilitate the extraction of data from various sources, transforming that data into a readable format, and loading it into data warehouses for further analysis. The ETL process is essential for data scientists and analysts for preparing data for insights generation.

## Features
- **Data Extraction**: Supports multiple data sources including databases, APIs, and flat files.
- **Data Transformation**: Includes various transformation functions such as cleaning, normalization, and aggregation.
- **Data Loading**: Capable of loading data into various target systems, including cloud databases and data lakes.
- **Scalability**: Designed to handle large volumes of data efficiently.
- **Logging and Monitoring**: Comprehensive logging features to monitor ETL jobs and track errors.
- **Modularity**: Easily extendable with the ability to add new extractors, transformers, and loaders.

## Installation Instructions
To install the ETL project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Perumallasrinu/big-data-datascience-Extract-Transform-load.git
   cd big-data-datascience-Extract-Transform-load
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage Guide
1. **Configuration**:
   Modify the configuration file `config.yaml` to specify your data sources and target destinations.

2. **Running the ETL Process**:
   You can run the ETL process using the following command:
   ```bash
   python etl.py
   ```

3. **Monitoring & Logging**:
   Check the logs in the `logs/` directory for details on the ETL execution status.

## Project Structure
```
big-data-datascience-Extract-Transform-load/
│
├── config.yaml                # Configuration file for data sources and targets
├── etl.py                     # Main ETL execution script
├── requirements.txt           # Python dependencies
├── logs/                      # Directory for log files
│   └── etl.log                # Log file for ETL process
└── src/                       # Source files
    ├── extract/               # Data extraction modules
    ├── transform/             # Data transformation modules
    └── load/                  # Data loading modules
```

## Data Sources
The project supports extraction from the following data sources:
- SQL Databases (MySQL, PostgreSQL)
- NoSQL Databases (MongoDB)
- REST APIs
- CSV and JSON files

## Related Documentation
- [ETL Process Overview](https://en.wikipedia.org/wiki/Extract,_transform,_load)
- [Apache Airflow for ETL](https://airflow.apache.org/)
- [Data Warehousing Concepts](https://www.oracle.com/database/what-is-data-warehouse.html)

For more information, refer to the official documentation on each component and technology used in this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.