Barcelona Road Accidents Analysis
This project analyzes road accident data from Barcelona to identify patterns, trends, and insights related to traffic safety in the city.

Project Overview
The analysis focuses on understanding the characteristics and distribution of road accidents in Barcelona through data cleaning and exploratory data analysis (EDA).

Dataset
The dataset (Barca_accidents_opendata.csv) contains road accident records from Barcelona with the following key columns:
Location: district_id, district_name, neighborhood_id, neighborhood_name, street_code, street_name, postal_code
Time: weekday_name, weekday
Incident Details: cause_incident
Casualties: n_deaths, n_wounded_mild, n_wounded_severe, n_victims
Vehicles: n_vehicles
Coordinates: utm_coordinate_x, utm_coordinate_y, longitude, latitude
Identification: case_id

Methodology
Data Cleaning: Handled missing values, standardized formats, and removed inconsistencies
Exploratory Data Analysis:

Temporal analysis (weekday patterns)
Geographical distribution by districts and neighborhoods
Accident severity analysis (deaths vs. mild/severe injuries)
Casualty and vehicle correlation analysis
Incident cause categorization

Technologies Used

Python
Pandas for data manipulation
Matplotlib/Seaborn for visualization
Jupyter Notebooks for analysis

