# EU Energy Production Analysis & Forecasting Project

## Objective
The aim of this project is to create a model and conduct an analysis of the current energy make-up of 4 different European countries. The goal was to predict energy production for selected countries within the European Union. The model is built using free energy statistics data from the International Energy Agency (IEA), covering the period from 2010 through 2025. In addition to energy production data, weather data is incorporated to explore how weather influences energy production.

The final output of this project includes a predictive model accompanied by an interactive dashboard. The dashboard highlights key insights such as:
- Highest and lowest energy production months  
- Energy consumption split between industry and household use  
- Changes in the energy mix, with a focus on how renewable energy is expanding or contracting  

---

## How the Objective Was Achieved

### Data Collection and Preparation
- Energy statistics data was sourced from the International Energy Agency.
- Additional datasets, including weather, population, and geodata, were collected through external APIs.
- The data was uploaded to Google Sheets and BigQuery to support exploration and dashboard creation.
- Data cleaning was performed as needed to ensure consistency and usability.

### Modeling Approach
- Time series modeling techniques were explored using the **DARTS** package in Python.
- A predictive model was created to forecast future energy production based on historical trends and available variables.
- The model was designed to integrate with the dashboard to provide forward-looking insights.

### Dashboard Development
- An interactive dashboard was created to visualize energy production insights.
- The dashboard answers specific research questions and presents trends in production, consumption, and energy mix.
- Insights such as peak and low production months are clearly displayed.

### Collaboration
- All coding and analysis were conducted in **Google Colab**, allowing team members to share notebooks and coordinate work efficiently.

---

## Project Guideposts
- Read through and understand time series modeling projects using the DARTS Python package.
- Review and question the collected data after uploading it to Google Sheets and BigQuery.
- Clean the data as required for analysis and visualization.
- Create an interactive dashboard showing energy production insights.
- Develop and attach a predictive model to the dashboard.

---

## Schedule
- **Dec 25th – 28th**: Understand DARTS and complete code-along projects  
- **Dec 1st**: Develop questions based on the provided data  
- **Dec 2nd – 5th**: Create an interactive dashboard answering those questions  
- **Dec 8th – 10th**: Build a predictive model based on the given data  
- **Dec 11th**: Create and practice presentation  
- **Dec 12th**: Present findings  

---

## Research Questions
- What is the current energy mix, and how has it evolved over 5-year intervals?
- Have energy losses in transmission been reduced?
- How much energy has been imported?
- How much has energy consumption grown in the last 5 years?

---

## Countries Analyzed
- **Germany (MVP)**
- **Spain (MVP)**
- Norway
- Slovakia

---

## Tools and Resources Used

### Learning Resource
- YouTube: https://www.youtube.com/watch?v=sXNXI2mE8DU

### APIs and Documentation
- **API Ninja**
  - Geodata: https://api-ninjas.com/api/geocoding  
  - Population Data: https://api-ninjas.com/api/population  

- **Visual Crossing**
  - Weather Data API: https://www.visualcrossing.com/resources/documentation/weather-api/timeline-weather-api/

### Modeling Library
- **DARTS** (using a wide data format)
