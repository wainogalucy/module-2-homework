# Aviation Accident Analysis

## Project Overview
This project analyzes aviation accident data to identify key factors that influence aircraft safety and accident severity. The goal is to extract meaningful insights that can help improve decision-making around aircraft selection and operational safety.

The analysis focuses on patterns in injury severity, aircraft damage, weather conditions, and phase of flight.


## Dataset
The dataset used in this project is `AviationData.csv`, which contains records of aviation accidents including:
- Aircraft category and damage level  
- Injury counts (fatal, serious, minor, uninjured)  
- Weather conditions  
- Phase of flight  
- Event dates  


## Data Cleaning & Preparation
The dataset was cleaned and processed by:
- Filtering for airplanes only  
- Removing amateur-built aircraft  
- Restricting analysis to events within the last 40 years  
- Handling missing values  
- Standardizing categorical columns  


## Feature Engineering
The following derived metrics were created:

- **Total.Passengers** → Estimated total number of people onboard  
- **Serious_Fatal_Rate** → Fraction of passengers with serious or fatal injuries  
- **Aircraft_Destroyed** → Binary indicator of whether an aircraft was completely destroyed  


## Analysis Performed
The project explores aviation safety from multiple perspectives:

### Weather Conditions
- Comparison of accident severity under VMC vs IMC conditions  
- IMC conditions show higher injury and destruction rates  

### Phase of Flight
- Analysis of risk across takeoff, cruise, and landing phases  
- Takeoff and landing show higher accident severity  

###  Aircraft Damage
- Evaluation of aircraft destruction frequency  
- Relationship between damage level and accident outcomes  


## Key Insights
- Poor weather conditions (IMC) are associated with more severe accidents  
- Takeoff and landing are the most critical and high-risk flight phases  
- Aircraft destruction and injury severity vary significantly across conditions  


## Tools Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  


## Objective
To transform raw aviation accident data into clear, actionable insights that improve understanding of aviation safety risks and support better operational decision-making.


