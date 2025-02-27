Real-Time Traffic Congestion Prediction Using Machine Learning

Overview

This project aims to predict real-time traffic congestion using machine learning techniques and urban traffic data. The dataset used is the Metro Interstate Traffic Volume dataset, which includes various weather conditions and time-based features affecting traffic volume.

Features Used

The dataset includes the following features:

date_time: Timestamp of the data collection.

holiday: Whether the day is a holiday.

temp: Temperature in Kelvin.

rain_1h: Amount of rain in the last hour (mm).

snow_1h: Amount of snow in the last hour (mm).

clouds_all: Cloud coverage percentage.

weather_main: Main weather condition.

weather_description: Detailed weather description.

hour: Extracted hour from the timestamp.

day_of_week: Extracted day of the week.

month: Extracted month.

is_weekend: Whether the day is a weekend or not.

traffic_volume: Target variable representing the number of vehicles passing a point in an hour.

Model Used

The project utilizes a Random Forest Regressor for predicting traffic volume based on historical data. The dataset is preprocessed using:

Label Encoding for categorical variables.

Feature extraction from timestamp data.

Train-test splitting (80-20 split).
Evaluation Metrics

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R2 Score

Future Improvements

Implement deep learning models for better accuracy.

Integrate live traffic data for real-time predictions.

Deploy the model as an API.

Contributors

Ishika Singhal - GitHub Profile

License

This project is licensed under the MIT License.

