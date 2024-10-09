# Retail-Sales-Forecasting

## Overview

This project simulates a real-world experience where I applied data analysis and database management techniques during my internship. The goal is to forecast retail sales using various time series models (ARIMA, VAR, SARIMA) and manage data efficiently using PostgreSQL. This simulation reflects the type of work I carried out during my internship.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Data Simulation](#data-simulation)
- [Time Series Modeling](#time-series-modeling)
- [Database Management with PostgreSQL](#database-management-with-postgresql)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Project Structure

Retail-Sales-Forecasting/ │ ├── data/ # Folder containing simulated datasets ├── notebooks/ # Jupyter Notebooks with detailed analysis and modeling ├── scripts/ # Python scripts for data generation and model automation ├── sql/ # SQL scripts for database management (PostgreSQL) ├── .venv/ # Virtual environment (added to .gitignore, not included in repo) ├── requirements.txt # Python dependencies ├── README.md # Project documentation └── LICENSE # License file

## Data Simulation

The dataset simulates weekly retail sales (e.g., chicken sales) over several years, with additional variables such as temperature and promotional activity. The goal is to recreate a realistic scenario where external factors (like weather or promotions) influence sales trends.

## Time Series Modeling

### ARIMA

- The ARIMA model is used for univariate analysis on sales data to understand past sales behavior and make predictions based solely on historical values.

### VAR (Vector AutoRegression)

- The VAR model includes multiple variables such as temperature and promotions to forecast sales. This approach is effective when multiple time series influence each other.

### SARIMA

- The SARIMA model incorporates seasonality, capturing recurring patterns (e.g., annual cycles) in the sales data, providing a comprehensive forecasting solution.

## Database Management with PostgreSQL

The project includes database management tasks, where a PostgreSQL database is designed and deployed to store and manage sales and log data efficiently. The schema design is structured to allow for easy integration of daily logs and data analysis.

## Usage

1. **Clone the repository**:
2. **Install the dependencies**:
3. **Run the Jupyter Notebooks** in the `/notebooks` folder to see the detailed analysis and modeling.
4. **Simulate Data**: Use the scripts in the `/scripts` folder to generate and manipulate datasets.
5. **Database Setup**: SQL scripts in the `/sql` folder help set up and manage the PostgreSQL database.

## Dependencies

- Python 3.8+
- pandas
- numpy
- matplotlib
- statsmodels
- SQLAlchemy (for database interaction)
- PostgreSQL

## License

This project is licensed under the MIT License. See the LICENSE file for details.
