Introduction
Through the Google Data Analytics Professional Certificate course offered by Coursera, I have been learning about the six stages of the data analysis process (ask, prepare, process, analyze, share, & act), and how to use tools such as SQL, Tableau, and R to gather insights from data. With what I have learned throughout the course, I will be completing an analysis on the Cyclistic Case Study showing the process step by step.

Background
For this case study, I will be assuming the role of ‘Jr. Data Analyst’ at Cyclistic, a bike-share company based in Chicago that offers over 6,000 bikes at 800+ docking stations spread across Chicago. They currently offer classic bikes and electric bikes for use and have two customer segments: Casuals and Members. Casuals are customers who either buy a single-trip pass or a day pass, and Members are customers who buy annual memberships. My goal is to design marketing strategies aimed at converting casual riders into annual members. 

I will do this by focusing on how annual members and casual riders use Cyclistic bikes differently.

Ask
Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. The director of marketing and my manager, Moreno believes that maximizing the number of annual members will be key to future growth. Moreno wants to convert the casual riders into members rather than target all-new customers. To help them complete this goal, I have been asked to find “How do annual members and casual riders use Cyclistic bikes differently?”.

Prepare
To approach this question, I will be analyzing the historical Cyclistic bike trip data for all 12 months of 2022. The data is bias-free, reliable, and collected by Cyclistic and stored on the company’s database separated by each month and year in a CSV format. For this analysis, I have saved the 12 CSV files for each month of 2022 on my local drive.
The Cyclistic dataset can be found [here](https://divvy-tripdata.s3.amazonaws.com/index.html).

Process
To start, I utilize R through Posit Cloud to merge, clean, and manipulate the data, preparing it for analysis. This process entails several essential steps, including:

Uploading the Cyclistic data from January 2022, February 2022, and March 2022 into Posit Cloud and  merging them into a single dataframe. I then verify that all observations are transferred to the new dataframe properly. I also add the ride_length_secs, date, month, day, year, day_of_week columns so that I can use these for my analysis. I then use the str() function for my dataframe to check if the data types of the columns are correct. I then change the ride_lengh_secs to a numeric data type so that I can run calculations on the data later on. I then clean the data by removing NA values, duplicate rows, columns that will not be used for the analysis, and values less than 0 for the ride_length_secs column.

Analysis


