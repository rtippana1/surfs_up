# surfs_up

## Overview
The Purpose of this analysis is to provide W.Avy with stastical analytics on weather dataset for an island in hawaii to determing if the its the right place to set up a surf shack.
As part of this analysis we are using SQLite to store the weather data that W. Avy shared with us.
Performed some analysis on precipitation in Oahu.There needs to be enough rain to keep everything green, but not so much that you lose out on that ideal surfing and ice cream weather.We Perfored some  analysis on  precipitation levels to show Oahu as the perfect place to surf. We have last 12 months of precipitation data already loaded into your SQLite database to do the same.
To make it easy to understand the data we have created a plot of precipitation scores in chronological order. Rather than simply showing whether it rained on a given day, we have displayed how much it rained and if it was raining on the previous or subsequent days as well
Determining how active the stations are will tell us how much data has been collected from each station. In this case, active essentially means the number of recordings for each station. This will help us figure out how reliable our data is, which, in turn, will boost W. Avy's confidence in his investment.
W. Avy tells you that he's interested in the most active station; he believes it will provide the most data and help you determine the best location for the surf shop. 
To make the proposal more appealing plotting the results of the analysis can be shared as a visual presentation with the board if needed, and convince them to invest in your shop.
We have used Flask, which will let me display my results in a webpage. All that needs to be done is provide your board with the URL."
creating the appropriate routes so that W. Avy's board of directors will be able to easily access the analysis. We have  put together a route for each segment of  analysis: Precipitation, Stations, Monthly Temperature, and Statistics, as well as a welcome route that will orient W. Avy and his associates to the webpage.

### Results:
1)The statistics of Temperature retrieved for the month of june over the years indicate that June is a good month for surfing.

2)The statistics of Temperature retrieved for the month of December over the years indicate that December is also good month for surfing.

3)Based on the above temperates retrieved from the month of June and December indicate that  Oahu is a good lcoation for a year around of surfing ,which indicates that surf shack is a good investment .


#### Summary: