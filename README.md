# TV Ratings Analysis & Forecasting

## Overview

This project analyzes morning TV audience data to identify key factors that influence ratings and support data-driven programming decisions. It combines exploratory data analysis and time series forecasting to understand audience behavior and predict performance.

---

## Business Problem

Television networks need to understand what drives audience engagement in order to optimize content, scheduling, and on-screen presence.
This project focuses on identifying patterns in TV ratings and evaluating how different factors (time slots, competitors, and on-screen personalities) impact audience performance.

---

## Dataset

* ~500,000 observations of TV ratings and screen-time data
* Time-based variables (date, weekday, time slot)
* On-screen presence of TV personalities
* Competitor channel ratings

*Note: Dataset has been simplified/anonymized for portfolio purposes.*

---

## Approach

### 1. Data Cleaning & Preparation

* Processed large-scale datasets using Python (pandas)
* Handled missing values and structured time series data

### 2. Exploratory Data Analysis (EDA)

* Analyzed rating trends over time
* Identified weekly patterns and seasonal effects
* Compared performance against competitor channels

### 3. Feature Analysis

* Evaluated impact of on-screen presence
* Analyzed influence of content type and scheduling
* Explored relationship between competitors and rating fluctuations

### 4. Forecasting Model

* Built time series models (ARIMAX)
* Evaluated model performance using error metrics
* Generated forecasts to support decision-making

---

## Key Insights

* TV ratings show strong weekly patterns and time-slot dependency
* On-screen presence of certain personalities is associated with rating changes
* Competitor performance has measurable influence on audience behavior
* Forecasting models can provide useful short-term predictions for programming decisions

---

## Business Impact

* Supports data-driven programming decisions
* Helps identify high-impact content and scheduling strategies
* Provides a framework for monitoring and predicting audience performance

---

## Tools & Technologies

* Python (pandas, numpy)
* Time Series Modeling (ARIMA / SARIMA)
* Data Visualization (matplotlib / seaborn)

---

## Project Structure

```
tv-ratings-analysis/
│
├── README.md
├── notebooks/
│   └── tv ratings analysis.ipynb
├── data/
└── visuals/
```

---

## Next Steps

* Build interactive dashboards (Power BI / Streamlit)
* Incorporate additional variables (content type, marketing campaigns)
* Improve forecasting models with external features

---

## Author

José Tomás Ahumada
Data Analyst | Python · SQL · Business Analytics
