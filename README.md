# COVID-19 Data Analysis & Visualization with Plotly Express 📊

## Overview  
This project performs an exploratory analysis of COVID-19 datasets and visualizes insights using **Plotly Express**, along with supporting libraries like **Pandas**, **NumPy**, and **Matplotlib**.  
It includes bar charts, line graphs, bubble charts, choropleth maps, and word clouds to help understand the spread, recovery, and causes of deaths from COVID-19 globally.

## Features & Highlights  
- Clean, preprocess, and aggregate multiple COVID-19 datasets  
- Generate interactive visualizations (bar charts, scatter / bubble plots)  
- Animate maps (choropleth) to show temporal spread of infections & deaths  
- Country-specific visualizations (e.g. USA)  
- Word cloud generation to analyze causes of death  
- Use of log scales, hover info, color scales, and animations  

## Tech Stack  
- Python  
- Pandas & NumPy  
- Matplotlib  
- Plotly Express  
- WordCloud  

## Dataset  
This project uses three primary datasets:  
1. **covid.csv** — global summary per country (cases, deaths, recoveries, tests, etc.)  
2. **covid_grouped.csv** — time series data per country (confirmed, active, etc.)  
3. **coviddeath.csv** — real-world records of COVID-19 deaths and causes  


## Getting Started

### Prerequisites  
- Python 3.x  
- pip (or conda)  
- Jupyter / Colab environment  

### Installation  
```bash
pip install pandas numpy matplotlib plotly wordcloud

