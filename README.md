# Tableau-challenge
**Background**
Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

**Deployment**
The results of the analysis in Tableau public worksheets:
https://public.tableau.com/app/profile/tina.dehghan/viz/challenge_17095850303290/Story1?publish=yes


**Instructions**
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.
1.Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.
2.Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.
3.Create one of the following visualizations for city officials:
  Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.
  Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.
  The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.
4.Create your final presentation:
  Create a Tableau story that brings together the visualizations, requested maps, and dashboards.
  Ensure your presentation is professional, logical, and visually appealing.

**Project Summary**
Firstly, we downloaded the structured data and conducted data cleaning procedures in Jupyter Notebook, labeled as " **"data 2018-2020"**". 
Subsequently, we exported the cleaned data to a CSV file named **"merged_df_years"**
Next, we imported the data into Tableau.

I analyzed total trips in two categories: user analysis, which is described by time and gender, and station analysis, which is described by geographic map and time. In each analysis, you can filter data by age, month, year, and trip duration.

The homepage displays the total goals of this analysis, which are divided into different categories, along with a summary of each dashboard.
![0](https://github.com/TinaDhn/Tableau-challenge/assets/147674963/c8a0f38f-8075-4c41-94c7-5c2b4393a362)

This dashboard analysis illustrates the number of trips taken by users, categorizing them based on user types across various years, months, and days.
![1](https://github.com/TinaDhn/Tableau-challenge/assets/147674963/54b8ddb9-3ab5-48c7-a721-a6de80baa883)
The analysis reveals a decline in trip numbers from 2018 to 2020. Notably, weekend trips, especially on Sundays when individuals usually have more leisure time, exhibit lower trips compared to weekdays. August consistently registers higher trip volumes than other months. Moreover, there's a noticeable downtrend in subscriber numbers over the years.


This dashboard presents gender analysis across various locations, months, and age groups.
![2](https://github.com/TinaDhn/Tableau-challenge/assets/147674963/9d991cf7-4e4f-482c-bdc9-f6134449784d)
Women exhibit higher participation rates in Citibike usage compared to men, with women also demonstrating longer trip durations on average. But among the top 10 stations, where many people go, more men choose to ride than women.

This dashboard displays the top 10 start and end station names along with their geographical maps, filtered by month, year, and trip duration.
![3](https://github.com/TinaDhn/Tableau-challenge/assets/147674963/f7b1bcb6-deb4-416d-bae5-9ea506eb0930)
We noticed that the top station for both start and end points remained consistent over the three years. Additionally, these stations tend to have longer trip durations compared to others.

This dashboard focuses on start station names, filtered by trip duration across different month, years, hours, and weekdays.
![4](https://github.com/TinaDhn/Tableau-challenge/assets/147674963/38bea045-a870-4fb9-a89d-f0a1c75106c2)
This analysis reveals the peak hours at various locations on different days.



