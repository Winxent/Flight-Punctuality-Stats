# 2018 Jan Flight Punctuality Stats
Punctuality statistics provide valuable insights into the reliability and performance of flights and airlines. Travelers can use this information to make informed decisions about their travel plans, and airlines can use it to improve their operations and enhance the passenger experience.

## Goal: To investigate 2018 Jan flight punctuality statistic and provide analysis, insights and visualisation.

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Introduction
Punctuality statistics of a flight provide valuable information about the on-time performance of a specific flight or an airline. Here are some key insights that can be derived from punctuality statistics:

1. On-Time Performance: Punctuality statistics indicate how often a flight or airline arrives at its destination on time, which is typically defined as being within a certain number of minutes of the scheduled arrival time (e.g., within 15 minutes of the scheduled arrival time). This information is crucial for passengers who want to plan their travel schedules efficiently.

2. Delays: Punctuality statistics reveal the frequency and duration of delays for a flight or airline. Delays can occur due to various reasons, such as weather conditions, air traffic congestion, mechanical issues, or operational challenges. Understanding the extent of delays helps passengers assess the reliability of a particular flight or airline.

3. Flight Cancellations: Punctuality statistics may also include information about flight cancellations. Cancellations can disrupt travel plans significantly, so knowing the cancellation rate of a flight or airline is essential for passengers.

4. Comparison Between Airlines: Passengers often use punctuality statistics to compare the performance of different airlines when selecting flights. Airlines with a strong track record of on-time arrivals may be more attractive to travelers.

These metrics are important for airlines and passengers to track as they provide insights into the operational reliability and performance of an airline, as well as potential disruptions to travelers' plans. Airlines aim to maximize the number of flights matched while minimizing the number of flights canceled and actual flights unmatched to provide a smooth and reliable travel experience for passengers.Travelers can use this information to make informed decisions about their travel plans, and airlines can use it to improve their operations and enhance the passenger experience.

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Datasets

There are 3207 rows, 25 columns. There are Column types of both categorical and numerical and they provide us the information about the flight details such as their run date, reporting period, reporting airport, origin destination country, origin destination, airline name, schedule or charter, number flights matched, actual flights unmatched, number flights canceled, flights punctuality percentages, average delay mins, and their previous record

Raw Datasets:https://docs.google.com/spreadsheets/d/147Hz6pcdtQfGJNu-KXCz8nn5TgncoVyS/edit?usp=sharing&ouid=107402225492318840480&rtpof=true&sd=true

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Data Cleaning
The below checklist is done for data cleaning using (google sheet):
##### A – Remove duplicate rows
	Ans: There are no duplicate rows
##### B – Handle missing values
	Ans: There are no missing values
##### C – Correct data formats
	Ans: Change run_date to date time data type, others no issue
##### D – Drop irrelevant columns
	Ans: No irrelevant column
##### E – Fix inconsistent data entry
	Ans: No inconsistent data entry
##### F – Trim whitespaces

  <img width="306" alt="image5" src="https://github.com/Winxent/Flight-Punctuality-Stats/assets/146320825/2a7e12e8-3d2e-4d21-9f81-39c4243f55e1">

	Ans: Trimming some white spaces using google clean-up suggestion
##### G – Correct spelling errors
	Ans: no wrong spelling
##### H – Correct numerical errors
	Ans: no numerical errors

Cleaned Datasets:https://docs.google.com/spreadsheets/d/1OHK0vSzopM_YVklA4jY7IJBB2aoWP2rZ5SEGahc22Pk/edit?usp=sharing

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Data Analysis
Different data analysis strategies are used to analyse the dataset provided: 

#### 1. Data Aggregation:
Helps describe the data, and generate insight from the characteristic of the data.
A customer might want to look into the performance in terms of punctuality based on different flight lines, punctuality and data should aggregate based on flight lines.

<img width="535" alt="Screenshot 2023-10-02 at 10 21 09 PM" src="https://github.com/Winxent/Flight-Punctuality-Stats/assets/146320825/85f95852-7eb0-43dc-aed1-1f85d6985d3c">

From the above shape and size table of the dataset we can see general max and min of the data base on different categories. 

<img width="549" alt="Screenshot 2023-10-02 at 10 26 49 PM" src="https://github.com/Winxent/Flight-Punctuality-Stats/assets/146320825/1bfcd36a-6256-4b50-afc0-703a5f85e36d">
<img width="546" alt="Screenshot 2023-10-02 at 10 29 01 PM" src="https://github.com/Winxent/Flight-Punctuality-Stats/assets/146320825/51f088fa-e474-43d9-93b1-30cadacc0f6e">

From the above two bar charts we can see the frequency of airports and airlines for 2018 Jan

#### 2. Summary Statistic:
Summarized the large datasets into insightful numbers and gist of information about the data,
We can understand the general situation, make decisions and monitor the changes.

1. Measures of location:
	Mean (Average of a data set), Median (middle value of the data set), Mode (most repeated number),
2. Measures of spread:
	To understand the spread and distribution of data. and to find outliers.
3. Graphics and charts:
	Dash board 

![rainbow](https://github.com/Winxent/portfolio/assets/146320825/5dc438d2-e138-4db0-97a0-e5ae8c3473e8)

# Insights generated
