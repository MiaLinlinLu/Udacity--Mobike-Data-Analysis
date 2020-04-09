# Mobike Dataset Exploration
## by Linlin Lu


## Mobike Dataset

> There are 10241 items in this mobike dataset.

The features include: orderid, userid, bikeid, start and end location information(start_location_x, start_location_y, end_location_x, end_location_y), the riding track of the user in this order (track), the riding time information (start_time, end_time).


## Summary of Findings

> Peak Order Time: 7-9 am, 17-20 pm
> Peak positions : Latitude [121.48,121.55], Longitude [31.25,31.35]
> Greatest peak positions in peak time: latitude 121.5, longtiude 31.3, which is near Gongqing National Forest Park.


## Key Insights for Presentation

> First step, plot the order counts of every weekday and hour. Result: no big difference in each weekday, while 7-9am and 17-20pm peak order counts.
> second step, plot the order counts of locations.
> third step, plot the order counts of locations in peak hours. And find the peak locations, followed by careful examinations on those spots.
> fourth step, adding the track positions to the locations, to find out the most busy riding roads,in order to try to contain the different riding time into consideration, which was excluded in above analysis.
> Finally, according to the plots in the fourthe step, an OUTSTADING location was found in localtion [latitude 31.3 andlogitude 121.5], which was near 'GongQing National Forest Park' in Shanghai.