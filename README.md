# Top Ranked Product/Category in each store

## Overview

This project aims to analyze the top-ranked product categories and products across different supercenters each year. It demonstrates my Data Engineering, ETL, Python, AWS RDS, and Tableau skills while providing actionable insights through data visualization.

### Project Highlights
* ETL Pipeline Development: Built an automated ETL pipeline to extract, transform, and load sales data.
* AWS RDS Integration: Utilized AWS RDS for MySQL as the backend data storage.
* Data Analysis: Focused on identifying top-performing products and categories across various stores.
* Tableau Dashboard: Developed an interactive dashboard to visualize trends and insights.

### Tools & Technologies
* Programming Languages: Python
* Database: MySQL (AWS RDS)
* Data Visualization: Tableau
* APIs: Kaggle API
* Data Formats: CSV, Excel
* Libraries: Pandas, SQLAlchemy, Requests

### Workflow

1. Data Extraction
   * Connected to the Kaggle API to search and download datasets matching the keyword 'sales'.
   * Unzipped and stored the files locally for further processing.

2. Data Transformation
   * Parsed CSV and Excel files to extract relevant information.
   * Filtered and retained necessary columns.
   * Assigned unique store_id values to each supercenter.

3. Data Loading
   * Established a connection to an AWS RDS MySQL instance using Python.
   * Loaded the transformed data into database tables for structured storage.

4. Data Visualization
   * Connected Tableau to the MySQL database.
   * Designed an interactive dashboard to:
       - Display yearly trends for top-ranked products and categories.
   * Provide insights into sales performance across supercenters.

### Key Results
* Successfully identified high-performing products and categories across multiple supercenters.
* Created a user-friendly Tableau dashboard enabling quick data exploration and decision-making.
