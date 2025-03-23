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

## Results
The following table summarizes the performance of the evaluated models:

| **Model Type**         | **Model**               | **MAE**  | **MSE**  | **R² Score** | **Training Duration (s)** | **Bias Correction** |
|-------------------------|-------------------------|----------|----------|--------------|---------------------------|---------------------|
| **Traditional Models**  | Linear Regression       | 3.1      | 21.58    | -1.07        | 0.003493070602            | 3                   |
|                         | SVR                     | 4.04     | 29.09    | -1.79        | 0.00091171                | 30                  |
|                         | ARIMA                   | 2.1999   | 6.63     | 0.363        | 0.1151                    | 4                   |
| **Tree-Based Models**   | Gradient Boosting       | 3.7375   | 16.28    | -0.5638      | 0.0414                    | 10                  |
|                         | LightGBM                | 2.1224   | 10.42    | 0            | 0.00523                   | 32                  |
|                         | Random Forest Regressor | 2.1016   | 10.44    | 0            | 0.074                     | 13                  |
|                         | XGBoost                 | 2.6      | 11.31    | -0.09        | 0.0443                    | 11.5                |
| **Neural Network-Based Models** | ANN             | 2.25     | 7.84     | 0.25         | 43.16                     | 5.5                 |
|                         | LSTM                    | 3.64     | 18.34    | -0.76        | 41.332346                 | 1                   |
|                         | CNN                     | 1.89     | 5.45     | 0.48         | 30.056533                 | 6                   |
|                         | RNN                     | 4.83     | 31.89    | -3.11        | 27.4278                   | -2                  |
|                         | GRU                     | 2.35     | 8.16     | 0.22         | 29.86                     | 5.5                 |
| **Hybrid Models**       | LSTM + ARIMA            | 0.73     | 0.74     | 0.61         | 37.86                     | 11                  |
|                         | ANN + ARIMA             | 2.07     | 5.02     | 0.52         | 30.7533736                | 7.5                 |
|                         | CNN + ARIMA             | 1.84     | 4.70     | 0.55         | 29.354654                 | 6.5                 |
|                         | GRU + ARIMA             | 1.97     | 5.26     | 0.49         | 34.06546                  | 6                   |

### Key Findings:
- **Hybrid Models Outperform**: Hybrid models (e.g., LSTM + ARIMA, ANN + ARIMA) consistently achieve the lowest MAE and MSE, along with the highest R² scores.
- **Best Performing Model**: The **LSTM + ARIMA** hybrid model achieves the best performance with an MAE of **0.73**, MSE of **0.74**, and R² Score of **0.61**.
- **Policy Implications**: The study highlights the importance of data-driven strategies and hybrid modeling techniques in achieving Sustainable Development Goals (SDGs).

## Installation
To replicate or extend this research, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/TanzinAbdul/Forecasting-Literacy-Development-in-Bangladesh-A-Study-of-Machine-Learning-and-Hybrid-Approaches.git
   cd Forecasting-Literacy-Development-in-Bangladesh-A-Study-of-Machine-Learning-and-Hybrid-Approaches

   
