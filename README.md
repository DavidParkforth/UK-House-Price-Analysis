# UK House Price Analysis & Prediction (2015–2024)

## Project Overview
This project explores the drivers of UK residential property prices using a dataset of ~90,000 transactions. It combines data engineering, geospatial intelligence, and time-series forecasting to assist housing associations in strategic decision-making.

## Research Questions
1. Which UK regions have the highest/lowest average prices?
2. Is the UK housing market stable or volatile post-2020?
3. What are the 3-year price trends for the North West?
4. How have property prices evolved over a 9-year timeline?
5. Is the North-South divide statistically significant?

## Technical Toolkit
* **Data Cleansing:** Fuzzy matching for county standardization and Regex for postcode validation.
* **Geospatial:** `PyDeck` for 3D spatial spikes and `Plotly` for animated choropleth maps.
* **Predictive Modeling:** `SARIMA` (Seasonal ARIMA) to forecast the North West market.
* **Statistics:** Independent Samples T-Test to validate regional price disparities.

## Key Visualizations
* **3D Spatial Intelligence:** Visualizing price density by postcode.
* **Temporal Animation:** 9-year time-lapse of regional price shifts.

## 🚀 How to Run This Project
1. **Data Source:** Download the raw CSV from [Kaggle](https://www.kaggle.com/datasets/swarupsudulaganti/uk-house-price-prediction-dataset-2015-to-2024).
2. **Setup:** Place the Kaggle CSV and the provided `county_mapping.csv` / `Regions.geojson` into the `/data` folder.
3. **Run:** Open `UK-House-Price-Analysis.ipynb` in Jupyter or VS Code.
