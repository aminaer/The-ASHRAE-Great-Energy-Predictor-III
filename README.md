# The-ASHRAE-Great-Energy-Predictor-III
In this competition, you’ll develop accurate models of metered building energy usage in the following areas: chilled water, electric, hot water, and steam meters. The data comes from over 1,000 buildings over a three-year timeframe. With better estimates of these energy-saving investments, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies.


## Notebooks:
The Notebooks represent the different steps of our solution to the Ashrae III competition:

- EDA:
It contains the Exploratory Data Analysis step in which we perform performing initial investigations on data so as to discover patterns, to spot anomalies and missing values as well as data vizualisation.

- Pre-processing:
This step involve feature engineering in which we extract the 28 features, such as raw data (e.g., meter, building metadata and weather parameters), categorical interactions between building metadata and meters, various features of the weather data, and diﬀerent target encoding features. And in the output we retrieve the 'Train', 'Validation' and 'Test' datasets.

- ANN: Using the deep learning models : Artificial neural networks to predict meter building reading for the period of two years.
- LGBM: Making use of Light GBM a fast, distributed, high-performance gradient boosting framework based on decision tree algorithm for the prediction
- LGBM with gridseach: Using LightGBM accompanied with GridSearchCV for hyperparameter tuning.
- LSTM: apply Long Short Term memory model which is an artificial recurrent neural network (RNN) architecture used in the field for deep learning.
