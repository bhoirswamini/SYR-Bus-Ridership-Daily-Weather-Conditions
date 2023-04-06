# SYR-Bus-Ridership-Daily-Weather-Conditions

Using SY30 Bus route dataset and daily weather conditions data performed a data analysis using Python on how bus route, weater conditions affect bus ridership activity.
Following task were performed to do thorough analysis on ridership:
1. For the year of 2019, determined the number of passengers that board the bus (PASSENGERS_ON) at a particular STOP_ID per day. Used this data to understand how the changes in weather affect the ridership at  selected Bus Stop. Selected a bus stop with a daily annual average of at least 5 passengers using it (This means that for any service day of the year, on average, at least 5 passengers boarded the bus from that bus stop).
2. Grouped the activity at the selected bus stop per month and compared against the average temperature for that month
3. Compare the activity between 2 or more bus stops over each month of the year
3. Determined the 5 bus stops that provide the highest average number of daily passengers during the year
4. For the years of 2019 and 2020, determined the number of passengers that board the bus (PASSENGERS_ON) at a particular STOP_ID per week. Selected a bus stop where one would expect a high number of users (i.e. Near a shopping mall, school, hospital, etc).
5. Compare the ridership activity between the two years and mentioned  hypothesis as to why changes could have taken place.
6. Broke down the miles travelled by the buses per month. Assuming an efficiency of 7 miles per gallon and a price of US$ 3.60 per gallon, computed how much it costs to run the buses per month if they use diesel fuel.
7. Determined if there are any anomalies (outliers) in the values of daily distance travelled by the bus.
8. For any of the years 2019 or 2020, studied the differences between the time of arrival (TIME_ACTUAL_ARRIVE) and the scheduled bus time (TIME_SCHEDULED) to determine the hours of the day, or the weeks of the year (or some other time period) where significant deviations between the arrival time and the scheduled time appear. Deviations of more than 10 minutes can be considered significant but you can change this limit if it makes sense for your analysis
9. (For 2019 ONLY) Investigated if there is any relationship between weather conditions (temperature, wind, snow) with the deviations between time of arrival and scheduled bus time.
10. Investigated if the VEHICLE_NUMBER or OPERATOR_ID have any influence in the deviations between time of arrival and scheduled bus time. Justify your analysis with graphs and documentation.

#Languages and Tools used: Python, Jupyter Notebook
#Libraries used: pandas, numpy, requests, matplotlib, seaborn

