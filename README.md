# Wind Turbine Power Prediction

## Aim of the Study

The goal is to predict wind turbine power production based on features like wind speed, wind direction, month of the year, and hour of the day.

## Technologies Used

- **Python Libraries:** NumPy, Pandas, Matplotlib, Seaborn, PySpark
- **Machine Learning:** Gradient Boosted Trees (GBT) Regressor

## Project Overview

The project begins with importing necessary libraries and configuring Spark for data analysis. A wind turbine dataset is loaded, and exploratory data analysis (EDA) is conducted to understand the relationships between variables. Notable findings include monthly and hourly variations in power production and the impact of wind speed on average power.

### Theoretical vs. Real Production

A comparison between the manufacturer's theoretical power production curve and real production reveals a good fit, showcasing the model's accuracy.

### Wind Speed Threshold

Identification of a wind speed threshold for zero theoretical power is explored. Anomalies are detected, and observations with zero power production are investigated, leading to the removal of outliers.

## Model Development

The dataset is prepared for machine learning algorithms, with features assembled into vectors. A Gradient Boosted Trees (GBT) Regressor is trained to predict power production. Model evaluation metrics, including R2 score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE), demonstrate the model's success.

## Model Comparison

The final section compares real, theoretical, and predicted power productions. The model shows a strong fit to real power production compared to the theoretical curve.

### Conclusion

The wind turbine power prediction model, built with PySpark and GBT Regressor, effectively captures patterns in the dataset. Further tuning can enhance performance, but the model demonstrates substantial predictive power.

For detailed implementation and analysis, refer to the Jupyter notebook provided.

*Note: This summary focuses on the key aspects of the project. For a comprehensive understanding, review the complete code and documentation.*
