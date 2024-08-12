# Energy-Production-Forecasting

## Overview

This project involves predicting energy production based on various features using a Random Forest Regressor model. The dataset includes timestamped records of energy production and temperature. The goal is to forecast future energy production values.

## Dataset

The dataset used in this project is `energy_production_data.csv`, which contains the following columns:

- `timestamp`: Date and time of the record
- `temperature`: Temperature at the given timestamp
- `energy_production`: Amount of energy produced (target variable)

## Features Engineered

The following features are extracted from the `timestamp` column:

- `hour`: Hour of the day
- `day`: Day of the month
- `month`: Month of the year
- `year`: Year

## Installation

To run this project, you need to have Python installed along with the following libraries:

- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these dependencies using pip:

```bash
pip install pandas scikit-learn matplotlib seaborn
