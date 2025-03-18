# sqlalchemy-challenge

# Climate Analysis and Flask API Project
This repository contains a Python-based project that performs climate data analysis using SQLite, SQLAlchemy, Pandas, and Flask. The project is divided into Jupyter Notebook data analysis and an interactive Flask API for dynamic data retrieval.

# 📊 Project Overview
***Jupyter Notebook Analysis***
1.Database Connection:

-Establishes a connection to the SQLite database using SQLAlchemy.

-Reflects tables (station, measurement) into SQLAlchemy classes.

-Links Python to the database via SQLAlchemy sessions.

2.Precipitation Analysis:

-Queries and visualizes precipitation data for the last year in the dataset.

-Outputs summary statistics and precipitation trends with Pandas and Matplotlib.

***Station Analysis:***

Identifies the number of stations and the most active station.

Analyzes temperature observations for the most active station.

Creates a histogram for temperature observations over the last year.

# Flask API
***Static Routes:***

/api/v1.0/precipitation: Returns precipitation data for the last year as JSON.

/api/v1.0/stations: Returns all station details as JSON.

/api/v1.0/tobs: Returns temperature observations (TOBS) for the most active station for the last year as JSON.

***Dynamic Routes:***

/api/v1.0/<start>: Calculates min, max, and average temperatures from a given start date to the end of the dataset.

/api/v1.0/<start>/<end>: Calculates min, max, and average temperatures between a given start and end date.

# 🚀 How to Run
Clone the repository.

Install the required libraries: Flask, SQLAlchemy, Pandas, Matplotlib.

Add the provided SQLite database file to the project directory.

Run the Jupyter Notebook to explore the analysis.

Start the Flask application by running the Python script.

Access the Flask API routes on your local server (e.g., http://127.0.0.1:5000).

# Key Features
Efficient database interaction using SQLAlchemy.

Comprehensive precipitation and station analysis.

Dynamic Flask API for customized data queries.

# License
This project is licensed under the MIT License. See the LICENSE file for details.



