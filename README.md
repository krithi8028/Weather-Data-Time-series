# Weather-Data-Time-series

## Project Overview

This project focuses on time-series analysis of weather data using various machine learning models. The main objective is to predict future weather patterns based on historical data, applying different machine learning techniques and performing exploratory data analysis (EDA) for insights.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Installation](#installation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Machine Learning Models](#machine-learning-models)

## Data Collection

The weather data was scraped using **Beautiful Soup** from online sources. The dataset includes daily observations of temperature, humidity, wind speed, and precipitation.

- **Features include:**
  - Date
  - Temperature
  - Humidity
  - Wind Speed
  - Precipitation

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/weather-data-time-series.git
    cd weather-data-time-series
    ```

2. Install the necessary dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Required packages:
    - Python 3.8+
    - pandas
    - numpy
    - matplotlib
    - seaborn
    - scikit-learn
    - Beautiful Soup
    - statsmodels

## Exploratory Data Analysis (EDA)

EDA was performed to understand trends and relationships in the data. Some key visualizations include:

- Line plots to observe time-series trends
- Correlation heatmaps to understand feature relationships
- Histograms and box plots for statistical insights

## Machine Learning Models

Several machine learning models were implemented to forecast future weather conditions:

1. **Linear Regression:** 
   - Used to predict temperature based on historical values.

2. **Support Vector Machine (SVM):** 
   - Applied for classification of weather events (e.g., rain or no rain).

3. **Decision Tree:**
   - Created a decision tree model to capture non-linear patterns in the data.

4. **Long Short-Term Memory (LSTM):**
   - A neural network-based model that excels in time-series forecasting tasks.

5. **Random Forest:**
   - Employed for improved accuracy through ensemble learning techniques.

