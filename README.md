# plpWeek8Project
# COVID-19 Data Analysis Project



## Overview
This project analyzes global COVID-19 trends including cases, deaths, and vaccination progress across multiple countries. The analysis is performed using Python data tools in a Jupyter Notebook environment, producing visualizations and insights suitable for reporting.

## Features
- **Data Collection**: Loads from Our World in Data with local fallback
- **Exploratory Analysis**: Examines dataset structure and statistics
- **Time Series Visualization**: Tracks cases, deaths, and vaccinations
- **Comparative Analysis**: Compares metrics across countries
- **Interactive Elements**: Optional widgets for customized exploration
- **Geographic Visualization**: Choropleth map of cases per million

## Requirements
- Python 3.7+
- Jupyter Notebook/Lab
- Required packages:
  ```bash
  pip install pandas matplotlib seaborn plotly ipywidgets
  jupyter nbextension enable --py widgetsnbextension

  Dataset
Uses the Our World in Data COVID-19 Dataset:

Automatically downloads during first run

Saves local copy (owid-covid-data.csv) for offline use

Includes cases, deaths, vaccinations, and demographic data

How to Use
1. Clone the repository or download the notebook
2. Install required packages
3. Launch Jupyter Notebook:
4. Run all cells sequentially
Analysis Sections
1. Data Collection & Loading
2. Data Exploration
3. Data Cleaning
4. Exploratory Data Analysis
  Case trends
  Death rates
  Moving averages
5. Vaccination Analysis
6. Geographic Visualization
7. Key Insights Generation
8. Interactive Analysis (Optional)
Sample Visualizations
  Total cases over time (log scale)
  Daily new cases (7-day average)
  Case fatality rate by country
  Vaccination progress comparison
  Interactive world map of cases
Customization
Edit these variables to analyze different countries or metrics:

python
selected_countries = ['United States', 'India', 'Brazil', 'Germany', 'Kenya', 'South Africa']
analysis_metrics = ['total_cases', 'total_deaths', 'people_vaccinated', 'new_cases']
Outputs
  Console output with key statistics
  Visualizations displayed inline
  Formatted insights in Markdown
  Optional interactive widgets
License
This project uses publicly available data under the Creative Commons BY license. The analysis code is free to use with attribution.
References
  Our World in Data COVID-19
  Johns Hopkins University Dashboard
  Python Data Science Handbook

