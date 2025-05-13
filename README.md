# Data-analysis-with-matplotlib

# Source:
owid-covid-data.csv

Columns used:
date, location, total_cases, total_deaths, new_cases, new_deaths, total_vaccinations,
people_vaccinated_per_hundred, people_fully_vaccinated_per_hundred

# Process Overview
Load and Clean Data

Removed missing or irrelevant entries

Converted date column to datetime

Handled missing values with .fillna() and .interpolate()

Filtered Countries

Focused on: Kenya, United States, India

Derived Metrics

Calculated death rate: total_deaths / total_cases

# Visualizations
Line Charts

Total cases over time

Total deaths over time

New daily cases

Bar Charts

Top countries by total cases

% vaccinated population

Pie Chart

Share of vaccinated population (%)

Heatmap

Correlation between cases, deaths, and vaccination metrics

# 💡 Key Insights
The United States had the fastest vaccine rollout.

India steadily increased coverage despite its population size.

Kenya had the lowest vaccination rate among the three.

The U.S. consistently reported the highest case counts.

Death rates varied widely, possibly due to reporting differences.

#  Tools Used
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook

# How to Run
Clone this repo:

bash
Copy
Edit
git clone https://github.com/your-username/covid-analysis.git
