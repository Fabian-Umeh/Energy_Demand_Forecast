
# EnAppSys Energy Demand Forecasting

## Overview
This repository contains two Jupyter Notebooks that focus on the energy demand forecasting for France. The notebooks take into consideration various factors such as weather conditions, time, and other features to make hourly forecasts up to 48 hours in advance.

### Table of Contents
1. [EnAppSys_EDA.ipynb](#enappsys_eda.ipynb)
2. [EnAppSys_Demand_ML.ipynb](#enappsys_demand_ml.ipynb)
3. [Data](#data)
4. [Installation](#installation)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

---

## [EnAppSys_EDA.ipynb](./EnAppSys_EDA.ipynb)
### Summary
This notebook provides an exploratory data analysis (EDA) of energy demand in France. It aims to understand the pattern and dependencies of energy demand in the context of the European electricity market.

#### Highlights
- **General Description**: Investigates the electricity demand of France and its influence on European electricity prices.
- **Forecasting**: Provides a framework for forecasting demand on an hourly level up to 48 hours ahead.
- **Extra Analysis**: Offers insights into how temperature changes affect the average electricity demand during weekdays and weekends, on a monthly basis.

#### Data Sources
- `dataset.csv`: Contains the actual demand data and several other features.
- `dataset_coords.csv`: Contains weather data on a coordinate level.

---

## [EnAppSys_Demand_ML.ipynb](./EnAppSys_Demand_ML.ipynb)
### Summary
This notebook delves into machine learning models for predicting energy demand in France. Various models are explored to understand their efficacy in forecasting.

#### Highlights
- **Modeling**: Employs several machine learning models, such as Random Forest and K-Nearest Neighbors, for demand forecasting.
- **Feature Importance**: Analyzes the significance of various features like solar forecast, wind actual, etc.
- **Performance Metrics**: Evaluates the models using metrics like R2 score and Mean Absolute Percentage Error (MAPE).

#### Data Sources
- Same as the EDA notebook, with additional feature engineering.

---

## Data
The data files used in these notebooks are presumed to be in CSV format. They contain both the demand data and various features that could influence demand, such as weather conditions.

---

## Installation
1. Clone this repository.
2. Make sure you have Jupyter Notebook installed, or install it via pip:
   ```
   pip install notebook
   ```
3. Run Jupyter Notebook and navigate to the cloned repository.

---

## Contributing
Feel free to fork this repository and contribute. Pull requests are welcome.

---

## License
This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.

---

## Contact
For any queries, feel free to reach out.
