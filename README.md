# PyBer_Analysis
Analysis on the rides the app had from january to may 2019 across multiple city types (Rural, urban and Suburban)

## Overview of the analysis
### What is the purpose?
This new analysis was made in order to obtain filtered and ordered data in order to make easier the decision making around Pyber. It has the objective to show in a more appealing and digestable way all the information about the service that the company offers. This data will be given in the form of a data frame and a graph, with the most important information at glance.

## Results
### Data Frame (summary of data)
For us to be able to get this information we had to merge both files and from there obtain a diferent data frame or series of each object of interest so we then could perform operations to get another Data frame or series and finally gather them all togetehr into one single Data Frame with digested information ready to be presented. ***For this part we used all the information no only some months.*** 

![Data_frame_1](https://user-images.githubusercontent.com/110573146/213847421-7ddc6638-603b-46b4-8fb0-0022303bc802.png)

![Data_frame_2](https://user-images.githubusercontent.com/110573146/213847427-ab0453c1-b189-4ff0-b0e4-5ced5ee702fa.png)

![Data_frame_3](https://user-images.githubusercontent.com/110573146/213847433-2b597a2d-5fb5-4459-88ef-206d62a0a05f.png)

As it is clearly visible in the last Data frame (summarised) the main difference is the same across all the columns except "Average Fare per Driver" and "Average Fare per Ride" and that is: 
* In ascending order it is always  Rural, Suburban and Urban: meaning that there are less rides, drivers and total fare in Rural cities and Urban has the most in every single category.

* This in turn makes sense for the other two columns to be the opposite, as there are less rides and less drivers the total fare is distributed in bigger parts per rides and drivers.   

### Line Plot (weekly total of fares)
For this plot it was necessary to get a new data frame that summarised and ordered by week (from january to the end of april) the total sum of fare by city type. 

Once the required data was obtained it was time to plot in three different lines the fares by week. And it is evident that at all times the Urban type is always at the top and the Rural is at the bottom. So it confirms what we saw in the summarised data frame with the whole information, so the total fare is not only higher from january to april, but in all the time the files holds. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/110573146/213848259-e5fdec92-bdda-42d2-8a88-e0b4912d58ee.png)

## Summary
### Recommendations
1. Our first recommendation is to push more attention to both or either Suburban and Rural cities as the plot and data frame showed that the total fare are lower than Urban. 
2. The second recomendation has to do with the size of the type, as a Urban is obviously bigger than the other two, so the rides are longer and the fare is more expensive so a solution could be to lower price in fares in suburban and rural so more people are willing to use the service, as we see in the data frame that the quantity of dirvers is not the issue (since there are more rides than drivers but not by a lot so they are more likely not overwhelmed).
3. The other reccomendation is to push more the marketing and publicity the suburban and rural areas as maybe there is not enough exposure or confidence in using this type of service. So maybe study a little more the population and understand what they want, maybe more security meassures or cheaper rides or maybe there is actually a shortage of drives.  
