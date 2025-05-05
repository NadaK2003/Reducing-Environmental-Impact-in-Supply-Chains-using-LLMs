Reducing Environmental Impact in Supply Chains using LLMs

An AI-powered system designed to analyze, forecast, and reduce carbon emissions in logistics and supply chains using real-world data and Large Language Models.

---

## Overview

As carbon emissions from supply chains continue to rise, industries are seeking AI-based solutions to monitor, predict, and reduce their environmental impact.  
This project introduces a hybrid system that combines time series forecasting with Large Language Models (LLMs) to:

- Predict future CO₂ emissions
- Analyze fuel efficiency in maritime transport
- Extract optimization tips from sustainability reports

---

## System Components

1. Data Analysis & Forecasting  
   Predict CO₂ emissions using historical and sectoral data via models like Prophet or ARIMA.

2. Fuel Efficiency Evaluation  
   Analyze fuel usage patterns in ships and their emission contribution.

3. LLM-based Insight Extraction  
   Extract actionable advice from unstructured reports using models like GPT.

---

## Datasets

| File Name                            | Description |
|-------------------------------------|-------------|
| CO2_emission_cleaned.csv          | Carbon emissions across sectors |
| ship_fuel_efficiency_cleaned.csv  | Maritime transport fuel efficiency |
| MER_T12_06_cleaned.csv            | Energy-related metrics and emissions |

---

## How to Run

1. Load the notebook Graduation_pro.ipynb or run copy_by_reema_,last_update.py
2. Ensure all CSV files are in the same directory
3. Run the cells to:
   - Clean and explore the datasets
   - Analyze trends using graphs
   - Forecast emissions
4. (Optional) Run LLM script to extract insights from uploaded reports

---

## Sample Visuals

_Add screenshots or chart outputs here (e.g. emissions forecast, fuel trends)_

| Emission Forecast | Fuel Efficiency |
|-------------------|-----------------|
| ![emission](images/forecast.png) | ![fuel](images/fuel_eff.png) |

---

## Technologies Used

- Python  
- Pandas, Numpy  
- Matplotlib, Seaborn  
- Prophet, ARIMA (or other ML models)  
- OpenAI API (GPT / LLMs)

---

## Future Enhancements

- Deploy Streamlit dashboard for decision-makers
- Real-time monitoring via API-connected logistics data
- Visualize emissions over geographic maps
- Integrate sustainability checklists via LLM

---

## Target Users

- Sustainability Analysts
- Supply Chain Managers
- Policy Makers & Environmental Agencies
- Logistics and Maritime Companies
