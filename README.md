# PyBer_Analysis

In this assignment we were tasked to perform a data analysis of 2019 Pyber Data to inspect trends and propose improvements of the service of the app. We created line graphs, box-and whisker plots and scatter plots divided by city to characterize the service by city-type. 
[! Fig 1. Pyber Ride-Sharing](https://github.com/anapereda/PyBer_Analysis/blob/master/Analysis/fig1.png)

Fig.1 suggests that a larger number of rides are completed in urban cities, in consequence we see a larger number of drivers and a larger percentage of % fare collected in it. On the other hand, rural city types,  have the lowest percentage of rides and drivers, but fares are widely distributed and having the greatest mean and median fare. Thus we see a negative correlation between price and total number of fares. 
[!Fig.8] (https://github.com/anapereda/PyBer_Analysis/blob/master/Analysis/Fig8.png)
By looking at Fig.8 in the Analysis folder, we see that there is no real correlation between time and fare; urban is always greater than suburban and rural fares. 

During this challenge we did not overcome any major challenge as the data was mainly clean and complete. However this issues are usually overcome by eliminating missing data point or assigning central tendency measures to minimize its effect on the data with the use of the appropriate code. Moreover there are different graphs that offer better pictures of the results and are easier to understand; thus it is important to make good decisions about which graph to use depending on the data. 


Based on the data there are great disparities between average cat per rider and driver between each city type. This can be easily fixed by adjusting supply and demand of drivers; give incentives in rural areas and limit capacity in urban areas. I think it would be interesting to dive into each city data and cross it with geography to explore trends in service use. Finally I would look more into the the driver_count and its correlation (scatter plot) with average and total fare. For this we would have to set up a new series or data frame where we aggregate on the city level. For the second project I would just to a scatter plot of the driver count vs. fare and distinct the color by city type. 
