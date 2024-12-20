# Metro Interstate Traffic Volume

This project focuses on analyzing traffic patterns on the westbound lanes of the I-94 Interstate highway. The aim is to identify key factors associated with heavy traffic, such as weather conditions, time of day, and day of the week, to better understand what influences congestion.

## Dataset Overview

The analysis is based on the I-94 Traffic Dataset, provided by John Hogue. The dataset is publicly available for download from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).

## Features

The dataset contains the following features:

- `holiday`: US National holidays plus regional holiday, Minnesota State Fair
- `temp`: Average temp in kelvin
- `rain_1h`: Amount in mm of rain that occurred in the hour
- `snow_1h`: Amount in mm of snow that occurred in the hour
- `clouds_all`: Percentage of cloud cover
- `weather_main`: Short textual description of the current weather
- `weather_description`: Longer textual description of the current weather
- `date_time`: Hour of the data collected in local CST time
- `traffic_volume`: Hourly I-94 ATR 301 reported westbound traffic volume

## Analysis

The analysis is divided into five sections:

1. **Monthly Patterns**: Analysis of traffic patterns by month. This analysis reveals distinct monthly patterns, with higher traffic volumes during summer months (June-August) and significantly lower volumes during winter months (December-February).
2. **Daily Patterns**: Analysis of traffic patterns by day of the week. This analysis reveals distinct daily patterns, with higher traffic volumes during weekdays and significantly lower volumes during weekends.
3. **Hourly Patterns**: Analysis of traffic patterns by hour of the day. This analysis reveals distinct hourly patterns, with peak congestion during typical rush hours (7-9 AM and 4-6 PM) and lowest volumes during early morning hours (2-4 AM).
4. **Traffic Distribution**: Analysis of the distribution of traffic volume throughout the day. This analysis reveals that traffic volume is normally distributed, with a mean of approximately 3259 vehicles per hour and a standard deviation of approximately 1987 vehicles per hour.
5. **Weather Patterns**: Analysis of traffic patterns by weather conditions. This analysis reveals that weather conditions have a significant impact on traffic volume, with higher volumes during clear or partly cloudy conditions and lower volumes during rainy or snowy conditions.

## Visualizations

The analysis is accompanied by a variety of visualizations, including:

- Line plots of monthly, daily, and hourly traffic patterns
- Histograms of traffic volume
- Scatter plots of traffic volume vs. weather conditions

## Conclusion

The traffic analysis reveals distinct temporal patterns across different time scales. Monthly patterns show higher traffic volumes during summer months (June-August), likely due to vacation travel and better weather conditions. Daily patterns indicate peak congestion during weekdays, particularly Tuesday through Thursday, with significantly lower volumes on weekends. The hourly pattern demonstrates classic rush hour peaks: a sharp morning peak between 7-9 AM as commuters head to work, and an even more pronounced evening peak between 4-6 PM as people return home. Traffic volumes are lowest during early morning hours (2-4 AM) when most people are asleep. These patterns suggest that the interstate traffic is heavily influenced by regular commuting patterns and workday schedules.

Additionally, the analysis reveals that weather conditions have a significant impact on traffic volume, with higher volumes during clear or partly cloudy conditions and lower volumes during rainy or snowy conditions. This understanding of traffic patterns can be valuable for transportation planning, especially during peak hours when the interstate experiences its heaviest use.
