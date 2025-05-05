# Reducing Environmental Impact in Supply Chains using LLMs

An AI-powered system designed to analyze, forecast, and reduce carbon emissions in logistics and supply chains using real-world data and intelligent modeling.

---

## Overview

As carbon emissions from supply chains continue to rise, industries are seeking AI-based solutions to monitor, predict, and reduce their environmental footprint.  
This project introduces a hybrid system that combines time series forecasting with Large Language Models (LLMs) to:

- Predict future CO₂ emissions  
- Measure fuel efficiency in maritime transport  
- Extract optimization tips from sustainability reports  

---

## System Components

1. Data Analysis & Forecasting  
> Predict CO₂ emissions using historical and sectoral data via models like Prophet or ARIMA.

2. Fuel Efficiency Evaluation  
> Analyze fuel usage patterns in ships and their emission contribution under different fuel types and weather conditions.

---

## Datasets Used

- CO₂ Emissions Dataset  
  Historical carbon emissions by country and year.

- Ship Fuel Efficiency Dataset  
  Contains distance, fuel consumption, CO₂ emissions, engine efficiency, and weather conditions.

- Cost of Living & Income Dataset  
  Used to explore economic factors that may correlate with emissions and fuel patterns.

---
## Exploratory Data Analysis (EDA)
### Boxplot of Carbon Emissions
Shows the spread and outliers in carbon emission values.  
![Boxplot of Carbon Emissions](images/boxplot_carbon_emissions.jpeg)

### CO₂ Emissions Over Time
Illustrates the historical trend of emissions from the 1970s to 2015.  
![CO2 Emissions Over Time](images/co2_emissions_over_time.jpeg)

### Distribution of Average Monthly Income
Explores the spread of income levels and its pattern across the dataset.  
![Average Monthly Income](images/income_distribution.jpeg)

### Fuel Consumption vs. CO₂ Emissions
Strong correlation shown between fuel use and CO₂ emissions, influenced by weather and fuel type.  
![Fuel vs CO2 Emissions](images/fuel_vs_emission_weather.jpeg)

---

## Models Used

- Prophet: For forecasting emissions trends  
- ARIMA: To validate and compare seasonal/time-based patterns  
- LLMs: To extract recommendations from unstructured sustainability reports  

---

## Project Goals

- Provide actionable AI insights for reducing carbon impact  
- Support logistics and maritime companies with predictive modeling  
- Promote sustainable practices through data-driven decisions  

---

## How to Run

1. Clone the repository  
2. Upload your data or use the sample datasets  
3. Run main_analysis.ipynb in Google Colab or Jupyter  
4. Explore the visual outputs and AI-driven insights  

