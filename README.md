# Data Analytics Portfolio Project

## Overview
This project is a comprehensive data analytics portfolio showcasing various SQL queries and data visualization techniques using a Brazilian e-commerce dataset. The project utilizes Python, MySQL, and several data analysis libraries to perform queries ranging from basic to advanced complexity.

## Project Structure
The project consists of two main Python scripts and a set of SQL queries:

1. `data_analytics_portfolio_project.py`: The main script containing SQL queries and data visualizations.
2. `csv_to_sql.ipynb`: A Jupyter notebook for importing CSV data into a MySQL database.
3. `Questions.txt`: A file containing the list of queries categorized by complexity.

## Setup and Installation

### Prerequisites
- Python 
- MySQL Server
- Required Python libraries: pandas, matplotlib, seaborn, mysql-connector-python

### Database Setup
1. Create a MySQL database named `ecommerce`.
2. Use the `csv_to_sql.ipynb` script to import the CSV files into the MySQL database.

### Running the Project
1. Ensure your MySQL server is running.
2. Update the database connection details in both Python scripts if necessary.
3. Run `data_analytics_portfolio_project.py` to execute the queries and generate visualizations.

## Features

### Basic Queries
- List unique customer cities
- Count orders placed in 2017
- Calculate total sales per product category
- Analyze installment-based payments
- Count customers by state

### Intermediate Queries
- Monthly order analysis for 2018
- Average products per order by city
- Revenue contribution by product category
- Price-purchase correlation analysis
- Seller revenue ranking

### Advanced Queries
- Moving average of customer order values
- Cumulative monthly sales
- Year-over-year sales growth rate
- Customer retention rate analysis
- Top-spending customer identification

## Data Visualization
The project includes various data visualization techniques using matplotlib and seaborn:
- Bar plots
- Pie charts
- Correlation heatmaps

## Notes
- The project uses a Brazilian e-commerce dataset. Ensure you have the necessary permissions to use this data.
- Some queries may take time to execute depending on the size of your dataset and your system's capabilities.

## Future Improvements
- Implement more advanced statistical analyses
- Create an interactive dashboard for real-time data exploration
- Optimize queries for better performance on larger datasets

## Contributors
Maninder Maan
