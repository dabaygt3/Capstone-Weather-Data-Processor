# Capstone-Weather-Data-Analysis

Purpose: Take in monthly weather data in csv format for 6 years of data. Produce quarterly averages for wind speed and humid air density out of historical weather data collected at the Guelph Turfgrass Institute, stored by Environment Canada. These averages will assist in design of wind farm to meet the power demands of a theoretical hydrogen fuel cell bus fleet for Guelph Transit.  

This code requires the use of a lot of csv files but is simple in principle. The wind and density functions will take the csv files for a quarter for a particular year put them in a dataframe, clean it up and calculate the average wind speed or humid air density for the year. These will be displayed for the user, as well as the average across the 6 years. This process is repeated for each quarter. This displayed data could then be used in wind power potential calculations which would inform the linear programming optimization analysis. 

The python file is buried at the bottom of the Weather Data Analysis folder beneath the csv's. If you download the file be sure that the csv's remain in the same filepath as the python script.
