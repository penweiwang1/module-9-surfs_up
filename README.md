# module-9-surfs_up


# Overview of the statistical analysis:
The purpose of the analysis is to parse through Oahu's weather dataset using SQLite to help determine if running a surf shop business is sustainable all year round. Using the dataset, two queries will be run, one for the month of June and one for the month of December. The extracted data will be converted to a dataframe in which we can then easily calculate the summary statistics can compare data.

# Results:
After extracting the Hawaii weather data and filtering only for the months of June and December, the resulting summary statistics for the two months were calculated :

<img width="195" alt="Screen Shot 2023-03-05 at 8 47 17 PM" src="https://user-images.githubusercontent.com/115126898/223581792-a7ba6ec8-7e80-42e9-945b-c66a88cda108.png">
<img width="195" alt="Screen Shot 2023-03-05 at 8 47 32 PM" src="https://user-images.githubusercontent.com/115126898/223581796-250c7796-a76b-41a6-87bf-058d46b77156.png">

Based on the above summary statistics, it can be seen that the average temperature in June is slightly higher at 75 degrees compared to that of December at 71 degrees. 

Decemeber also had a lower minimum temperature than that of June.

Although the temperatures for December were slightly lower, about 95% of the daily avg temperatures for both months ranged from approx. 70 degrees to approx 80 degrees.

# Summary:
Based on the data, it can be assumed that the business is sustainable all year round. Average temperatures for both months are in the 70s which is suitable for surfing.

Additional queries that could be beneficial is to gather summary statistics for the precipitation and see how often/how much it rained, which can affect the sales of the store. In addition, the weather in each station could be analyzed to see the optimal vicinity in which the shop should be located.
