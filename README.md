# World Energy Consumption Analysis

This repository contains a data analysis project based on the **World Energy Consumption** dataset from Kaggle, derived from the *Energy* dataset maintained by Our World in Data.

## Project Overview

The goal of this project is to explore country trends in energy consumption, energy mix, and related indicators over time.  
Using the dataset, the project examines how total energy use and the share of different energy sources (fossil fuels vs. renewables) have evolved across countries.

This repository serves as the final project for the AWDP course.

## Dataset

The project uses the **Energy** dataset maintained by Our World in Data, made available on Kaggle under the name:

> World Energy Consumption – Energy Consumption and Mix dataset by Our World in Data

Kaggle page (data source):

- https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption

Key characteristics:

- Global, regional, and country-level yearly data.
- Metrics on primary energy consumption, per‑capita consumption, energy mix, electricity mix, and fossil fuel production.
- Main data file `owid-energy-data.csv` describing 130+ columns.

## Research Questions

This project focuses on questions such as:

- How has global primary energy consumption changed over time, and which energy sources have driven this change?
- How does the energy mix (renewables vs. fossil fuels) differ between selected countries?
- Which countries have increased the share of renewable energy in their energy mix, and how quickly has this transition happened?
- How does energy consumption per capita differ between high‑income and low‑income countries?
- What is the relationship between energy consumption and economic development (e.g. GDP per capita)?

## Methods and Tools

The analysis follows a typical data science workflow:

- **Data acquisition** – Downloading the Kaggle dataset and loading it into the analysis environment.
- **Data cleaning & preprocessing** – Handling missing values, selecting relevant variables, and filtering to the time range and countries of interest.
- **Exploratory data analysis** – Descriptive statistics, time-series plots, and comparisons by country.
- **Visualization** – Charts that illustrate long‑term trends and differences in energy mix (e.g., line plots, stacked area charts, bar charts).

Technologies used (adjust to match your setup):

- Python (pandas, NumPy, Matplotlib, Seaborn / Plotly)
- Jupyter Notebook
- Git and GitHub for version control and documentation