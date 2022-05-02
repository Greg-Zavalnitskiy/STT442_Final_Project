# STT442_Final_Project
We loaded up the dplyr package 
Then uploaded the data file title "data.csv" with Header = True while not allowing strings as factors
Our data includes 41710 obs. of 24 variables 
To rid our data of any outliers, we removed players whose seasons were split into two because of a trade or release. We did this by only accepting players in our data set which had a stint (Year played with team) of 1. Also we only worked with batters who have played more than 100 games in a season, we did this because there is just not enough data to make that player worth including
We found batting average by dividing the number of H by the number of AB by each player. 
We created two different dataframes for the National league and the American league for our research question
We calculated the mean and standard deviations for out parameter batting average 
We then calculated the z test for the national leagues batting average 
We then caluclated the upper and lower intervals
