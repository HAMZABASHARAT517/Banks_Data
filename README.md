# Banks_Data-ETL-Pipeline

📅 Mar 2025 – Apr 2025 | University of Central Punjab

Overview
The Banks_Data-ETL-Pipeline is a comprehensive financial data engineering project focused on analyzing the **top 10 global banks by market capitalization**. The goal of this project is to design a **scalable, automated, and reliable ETL pipeline** that extracts raw market data, transforms it into meaningful insights, and loads it into structured formats suitable for reporting and analytics.

This project demonstrates the full workflow of a real-world data engineering pipeline, from data extraction to analysis, and shows best practices such as modular coding, logging, and version control.

---

Project Goals
- Build an **end-to-end ETL pipeline** for financial data.
- Provide multi-currency insights for top banks.
- Enable comparison of bank rankings across different regions.
- Implement **logging and error handling** for robust operations.
- Store data in CSV and SQL databases to support reporting and advanced analytics.

---

Workflow
1. Extract
   - Collect market capitalization data of the top 10 banks from structured sources such as Wikipedia and financial reports.
   - Fetch additional exchange rate data for multiple currencies.
2. Transform
   - Convert the extracted USD values into EUR, GBP, and INR using live exchange rates.
   - Clean and standardize data for consistency.
   - Handle missing or inconsistent entries to ensure high-quality datasets.
3. Load
   - Save transformed datasets into CSV files for quick access and reporting.
   - Load data into SQLite/PostgreSQL for advanced SQL queries and analytics.
4. Analytics
   - Run SQL queries to extract insights such as top banks by market cap in each currency.
   - Compare rankings across different regions to identify trends.

---

Challenges & Solutions
- Challenge: Handling inconsistent data formats and missing values.
  Solution: Applied data validation and cleaning using pandas.
- Challenge: Ensuring currency conversion was accurate and consistent.
  Solution: Integrated live exchange rates and automated calculations for multiple currencies.
- Challenge: Maintaining a robust ETL workflow with logging and error tracking.
  Solution: Added modular functions and comprehensive logging to monitor each stage.

---

Skills and Tools
- Python – pandas for ETL scripting and data manipulation
- CSV / JSON handling for structured data storage
- SQLite & PostgreSQL for relational data storage
- SQL queries for reporting and financial analysis
- ETL workflow design and automation
- Modular coding, logging, and Git/GitHub version control

---

Usage
1. Clone the repository:

