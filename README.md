# COMP647 - Special Topic of Machine Learning and Applications

## Rainfall Forecasting Using Time Series Weather Data

This project focuses on building a machine learning model to predict whether it will rain in the next 24 hours based on historical weather data. Weather forecasting is very important in daily life, such as for transportation and planning outdoor events. Accurate rainfall predictions can help drivers prepare for dangerous road conditions and allow people to better plan their activities.

Recently, I have been using weather apps to check forecasts, but I often find they are not very accurate. This made me curious about how weather forecasting works and why it sometimes fails. I want to learn how machine learning models can use past weather data to make better and more reliable predictions. By building my own rainfall prediction model, I hope to understand the factors that affect weather changes and how to improve forecasting accuracy for practical use.

I chose this weather dataset because it provides detailed hourly measurements of important features like temperature, humidity, wind speed, pressure, and visibility. These features influence rainfall and make the dataset suitable for practicing time series analysis and classification tasks, which are key skills in data science and machine learning. Through this project, I aim to learn how to preprocess time-dependent data, extract useful features, and apply machine learning models to a real-world problem.

The dataset contains hourly weather data recorded over several months. It includes key columns such as Temperature, Dew Point Temperature, Relative Humidity, Wind Speed, Visibility, Pressure, and Weather Conditions. The Weather Condition column categorizes observations like Clear, Rain, Snow, Fog, etc. One important aspect is that this data is time series, meaning each record is linked to a specific time and recorded in order. This lets us analyze how weather changes hour by hour and how past weather affects future conditions. Overall, this dataset offers rich information to study short-term weather patterns and build predictive models.

The goal of this project is to predict whether it will rain within the next 24 hours at a given location. This is a binary classification problem, where the target shows if it will rain or not.

## Dataset

**Source:** [Weather Dataset on Kaggle](https://www.kaggle.com/datasets/rohitgrewal/weather-data/data)