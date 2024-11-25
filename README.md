
# Project 1: Acquiring and Processing Information on the World's Largest Banks

## Description
This project implements an ETL (Extract, Transform, Load) process to acquire, process, and analyze data on the world's largest banks. It uses data scraping, data transformation, and database operations to derive insights from the data.

## Features
-  **Logging**: Logs the execution stages to a file.
-  **Data Extraction**: Scrapes data from a website containing the list of the world's largest banks.
-  **Data Transformation**: Converts market capitalization data into different currencies.
-  **Data Loading**:
   - Saves the processed data to a CSV file.
   - Stores the data in a SQLite database.
- **Query Execution**: Runs SQL queries to retrieve and analyze data.

## Requirements
- Python 3.x
- Libraries: `requests`, `sqlite3`, `numpy`, `pandas`, `bs4`
- Input: Exchange rates in a CSV file (`exchange_rate.csv`)

## Usage
- Configure the input paths (`exchange_rate.csv`) and output paths in the script.
- Run the script to perform ETL operations.
- View logs in `code_log.txt` and results in `Largest_banks_data.csv`.



# Project 2: ETL Operations on Country-GDP Data


## Description
This project performs ETL operations on GDP data of countries, sourced from a website. The data undergoes extraction, transformation, and loading into CSV and database formats, enabling further analysis.

## Features
- **Logging**: Logs ETL stages to a log file.
- **Data Extraction**: Extracts GDP data from a Wikipedia page.
- **Data Transformation**: Converts GDP data from millions to billions and renames columns for clarity.
- **Data Loading**:
   - Saves the processed data to a CSV file.
   - Loads the data into a SQLite database.
- **Query Execution**: Executes SQL queries to filter data based on GDP thresholds.

## Requirements
- Python 3.x
- Libraries: `requests`, `sqlite3`, `numpy`, `pandas`, `bs4`
- Output: Processed data in a CSV file (`Countries_by_GDP.csv`).

## Usage
- Update the URL and column attributes in the script as needed.
- Run the script to perform ETL operations.
- Logs are saved in `etl_project_log.txt`, and results are stored in `Countries_by_GDP.csv`.




