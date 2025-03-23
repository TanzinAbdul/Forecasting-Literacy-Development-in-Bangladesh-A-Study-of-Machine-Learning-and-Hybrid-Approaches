# Forecasting Literacy Development in Bangladesh: A Comparative Study of Machine Learning and Hybrid Approaches

## Overview
Bangladesh has made significant progress in improving literacy rates over the past few decades, but achieving universal literacy remains a challenging goal. This research explores the potential of **machine learning** and **hybrid modeling approaches** to forecast literacy development in Bangladesh, with a particular focus on projecting literacy rates by 2030. By leveraging socio-economic and demographic factors such as GDP, population, unemployment rate, and life expectancy, this study evaluates the performance of various predictive models to provide actionable insights for policy-driven decision-making.

## Key Features
- **Comprehensive Dataset**: Utilizes a dataset comprising socio-economic and demographic factors to forecast literacy rates.
- **Diverse Model Evaluation**: Compares the performance of machine learning models (Linear Regression, SVR, Gradient Boosting, Random Forest, XGBoost), neural network-based models (ANN, LSTM, CNN, RNN, GRU), and hybrid models (LSTM + ARIMA, ANN + ARIMA, CNN + ARIMA, GRU + ARIMA).
- **Hybrid Model Superiority**: Demonstrates that hybrid models consistently outperform other approaches in terms of **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R² Score**, capturing complex temporal and non-linear patterns effectively.
- **Policy-Ready Projections**: Projects that Bangladesh is on track to achieve a **90% literacy rate by 2030**, aligning with Sustainable Development Goals (SDGs).

## Dataset
The dataset used in this study is available on Kaggle:
- **Kaggle Dataset Link**: [Socio-Economic Dataset of Bangladesh (1970-2023)](https://www.kaggle.com/datasets/tanzinabdul/socio-economic-dataset-of-bangladesh-1970-2023)

The dataset includes the following key features:
- `year`: Year of the data point.
- `gdp`: Gross Domestic Product (GDP) of Bangladesh.
- `population`: Total population.
- `unemployment_rate`: Unemployment rate.
- `life_expectancy`: Average life expectancy.
- `literacy_rate`: Literacy rate (target variable).

## Installation
To replicate or extend this research, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/TanzinAbdul/Forecasting-Literacy-Development-in-Bangladesh-A-Study-of-Machine-Learning-and-Hybrid-Approaches.git
   cd Forecasting-Literacy-Development-in-Bangladesh-A-Study-of-Machine-Learning-and-Hybrid-Approaches

   
