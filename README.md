# Seattle-Weather
This project is about comparing Seattle's weather to St. Louis' weather
We will use daily precipitation measured in Seattle and St. Louis from January 1, 2017 to December 31, 2022. 
The data sets were downloaded from the National Centers for Environmental Information NOAA Climate Data
Source of Seattle Weather Data: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND
Source of St. Louis Weather Data: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

To analyze and visualize the rainfall data for Seattle and St. Louis in Python, I first imported the necessary libraries, including pandas and matplotlib. Next, I loaded the data into separate Pandas DataFrames for each city, and explored the contents of the data set to gain an understanding of its structure and format. I then converted the date strings to datetime format, and selected relevant subsets of the data by renaming columns and grouping the data by year. To deal with any missing values, I identified and filled them with appropriate values or dropped them from the analysis. Finally, I created a tidy data frame with columns for city and precipitation, and used this to create graphs to answer my research question of which city gets the most rain. These graphs provided a visual representation of the differences in rainfall between the two cities over time, allowing me to draw insights and conclusions from the data.
