# Building-Performance-Analysis-NM

Building Performance Analysis

Overview

This project focuses on Building Performance Analysis, which involves evaluating energy consumption patterns and predicting future usage using machine learning techniques. The goal is to optimize energy efficiency and sustainability in building operations. This repository provides the tools and code necessary to analyze energy consumption and generate insights through visualizations.

Objectives

1. Analyze Energy Consumption: Explore historical data to identify trends and patterns in energy usage.


2. Build Predictive Models: Use machine learning algorithms to predict future energy consumption.


3. Identify Key Factors: Determine the impact of variables such as temperature, humidity, and occupancy on energy usage.


4. Visualize Insights: Create visualizations to make the data more understandable and actionable.

Dataset

The dataset used in this project contains the following columns:

Temperature: Indoor/outdoor temperature in degrees Celsius.

Humidity: Relative humidity as a percentage.

Occupancy: Number of occupants in the building.

Day of Week: Day of the week (e.g., Monday, Tuesday).

Hour: Hour of the day (0–23).

Energy Consumption (kWh): Total energy consumed in kilowatt-hours.


Ensure the dataset (building_energy_data.csv) is stored in the repository or accessible in your local working directory before running the code.

Technologies Used

This project leverages the following technologies:

Python Libraries:

Pandas for data manipulation and preprocessing.

Numpy for mathematical computations.

Matplotlib and Seaborn for generating visualizations.

Scikit-learn for machine learning and predictive modeling.


Machine Learning Model:

RandomForestRegressor for predicting energy consumption.

Features of the Repository

1. Data Preprocessing: Scripts to clean and preprocess the dataset.


2. Model Training: A Random Forest model for predicting energy consumption.


3. Performance Metrics: Evaluate the model using RMSE and R² score.


4. Visualizations:

Line plot for energy consumption trends over time.

Bar plot showing average energy usage by hour.

Pie chart for energy consumption distribution by the day of the week.

Gradient bar plot for energy usage by hour.

How to Use

1. Clone the Repository

2. 2. Install Dependencies
Install the required Python libraries

3. Load Dataset

4. Run the Analysis:

Open the Jupyter Notebook Building_Performance_Analysis.ipynb or run the Python script.
Execute the cells/scripts to preprocess the data, train the model, and visualize the results.

5. Interpret the Results:
Review the outputs and visualizations to gain insights into energy consumption patterns and predictions.
