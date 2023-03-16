# 🚦 Finding Heavy Traffic Indicators on I-94 🚦

## ℹ️ Project Description
This project is part of the Data Analyst and Data Scientist path on Dataquest. The goal of this project is to determine a few indicators of heavy traffic on I-94. These indicators can be weather type, time of the day, time of the week, etc. For instance, we may find out that the traffic is usually heavier in the summer or when it snows.

## 🗄️ Data Description
The dataset documentation mentions that a station located approximately midway between Minneapolis and Saint Paul recorded the traffic data. Also, the station only records westbound traffic (cars moving from east to west). This means that the results of our analysis will be about the westbound traffic in the proximity of that station. In other words, we should avoid generalizing our results for the entire I-94 highway.
The dataset used in this project contains the hourly Westbound traffic volume for the station located approximately midway between Minneapolis and Saint Paul on I-94 highway. The dataset has a total of 48204 observations and 9 columns including date and time, holiday, weather conditions, and traffic volume.



## 🔍 Analysis Steps
- Data cleaning and preparation
- Exploratory data analysis
- Identifying heavy traffic indicators

## 📈 Results
After analyzing the dataset, we found that the following factors have a significant impact on the heavy traffic on I-94:

- Time of Day: Traffic volume peaks during rush hours (7-8 AM and 4-5 PM) and stays low during night hours.
- Day of Week: Traffic volume is higher during weekdays (Monday-Friday) as compared to weekends.
- Weather Conditions: Rain and snow have a significant impact on the traffic volume, and heavy precipitation leads to lower traffic volume.

## 📚 Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

