# Electricity-Demand-and-Price-Forcasting
This repository develops a model for predicting electricity demand and price using machine learning algorithms like LSTM, Random Forest, Gradient Boosting, and Linear Regression. It combines energy and weather data, with preprocessing, hyperparameter tuning, and evaluation to ensure accurate forecasts.

### Repository Description:

This repository focuses on developing a comprehensive electricity demand and price forecasting model, designed to accurately predict both energy demand and market prices. The model leverages multiple machine learning algorithms, including Long Short-Term Memory (LSTM) networks, Random Forest (RF), Gradient Boosting (GB), and Linear Regression (LR), to capture complex relationships between historical data and forecasted outcomes. Each algorithm is evaluated for performance, scalability, and prediction accuracy to ensure optimal results across various time frames and conditions.

The forecasting model is built using two key datasets: 
- **Energy Dataset**: Contains data such as energy price, load generation (from both fossil fuels and renewable energy sources), and energy demand over time.
- **Weather Dataset**: Includes meteorological variables such as temperature, humidity, pressure, rain, and snow, which are critical factors influencing energy consumption and generation.

Data preprocessing plays a crucial role in ensuring the reliability of the model. The weather data is aggregated using techniques like mean, mode, and groupby operations to align it with the energy dataset. Standard preprocessing steps such as handling missing values, outlier detection and treatment, feature scaling, and feature engineering are employed to enhance the model's input data quality.

To address the complexity of forecasting energy demand and prices, this repository explores advanced techniques, including:
- **LSTM Networks**: Capture temporal dependencies in the data, making them highly effective for time series forecasting.
- **Random Forest and Gradient Boosting**: Ensemble methods that handle complex non-linear relationships, providing robust predictions.
- **Linear Regression**: A simpler approach for baseline comparisons and understanding general trends in the data.

Hyperparameter tuning is implemented for each model to optimize performance. The repository also includes evaluation metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared to assess model accuracy.

This project is crucial for energy providers, policymakers, and stakeholders in optimizing energy production, maintaining grid stability, and implementing dynamic pricing strategies based on reliable demand and price predictions.
