# AEP_power_consumption_time_series_analysis

How to do data visualization and machine learning on AEP hourly power consumption dataset?

1. Download the dataset from Kaggle, https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption

2. Sort the dataframe datetime in ascending order.

3. Plot power consumption versus datetime to visualize the general trend.

4. Add in time-based features to the dataframe. They are, Hour, DayOfWeek, Month, DayOfMonth, and Weekend.

5. Plot box, grouped average, and heat map plots.

6. With Long Short-Term Memory model, do input single feature (power consumption) to forecast the next 30 days power consumption. The input length is 720 hours, and output length is 720 hours.

7. With Long Short-Term Memory model, do input multi features (power consumption, Hour, DayOfWeek, Month, DayOfMonth, and Weekend) to forecast the next 30 days power consumption. The input length is 720 hours, and output length is 720 hours.
