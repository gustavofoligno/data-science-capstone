SpaceX Data Science Capstone Project
This repository contains all the materials and code for the SpaceX Data Science Capstone project. The goal of this project is to predict the success of SpaceX's Falcon 9 first stage landings using machine learning and data analysis techniques. The repository includes data collection, cleaning, exploratory data analysis (EDA), visualization, and predictive modeling.

Table of Contents
Project Overview
Repository Structure
Notebooks and Files
Results and Insights
Getting Started
Authors

Project Overview
The project was designed to answer key business questions about SpaceX's cost efficiency and landing success rates. The analysis includes:

Data collection from APIs.
Data wrangling and cleaning.
Exploratory Data Analysis (EDA).
Visualizations using Plotly and Folium.
Predictive modeling using Logistic Regression, Support Vector Machines (SVM), Decision Trees, and K-Nearest Neighbors (KNN).

Repository Structure

SpaceX-Data-Science-Capstone/
│
├── firstpython.py                            # Introductory script for basic Python operations
├── jupyter-labs-webscraping.ipynb            # Data scraping techniques
├── jupyter-labs-spacex-data-collection-api-v2.ipynb  # Collecting SpaceX data via APIs
├── labs-jupyter-spacex-Data wrangling-v2.ipynb       # Data cleaning and wrangling
├── jupyter-labs-eda-dataviz-v2.ipynb         # Exploratory Data Analysis with visualizations
├── jupyter-labs-eda-sql-coursera_sqllite.ipynb # EDA using SQL
├── SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb # Machine learning and predictions
├── README.md                                 # Project documentation

Notebooks and Files
Data Collection
jupyter-labs-webscraping.ipynb: Demonstrates web scraping techniques to gather data.
jupyter-labs-spacex-data-collection-api-v2.ipynb: Collects SpaceX data using REST APIs.
Data Wrangling
labs-jupyter-spacex-Data wrangling-v2.ipynb: Cleans and preprocesses the raw data, handling missing values and engineering features.
Exploratory Data Analysis
jupyter-labs-eda-dataviz-v2.ipynb: Provides visual insights using libraries such as Matplotlib and Plotly.
jupyter-labs-eda-sql-coursera_sqllite.ipynb: Explores the data using SQL queries.
Predictive Modeling
SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb: Trains and evaluates machine learning models including:
Logistic Regression
SVM
Decision Trees
K-Nearest Neighbors (KNN)
Results and Insights
Logistic Regression, SVM, and KNN achieved an accuracy of 83.33%.
Decision Trees achieved an accuracy of 77.78%.
Key insights include the relationship between payload mass, orbit type, and landing success.

Getting Started
Clone the repository:
git clone https://github.com/username/spacex-data-capstone.git
Install the required Python libraries:
pip install -r requirements.txt
Open the Jupyter notebooks to reproduce the analysis:
jupyter notebook

Authors
Gustavo Foligno - Data Scientist
