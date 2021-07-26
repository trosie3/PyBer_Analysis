# PyBer Analysis

## Overview of the analysis:
The purpose of this analysis was to provide business recommendations to PyBer's CEO. To do this I broke down PyBer's data into each type of city (Urban, Suburban, Rural), and looked into driver counts, fares, and rides to gather data such as average fare per ride and driver. A deeper analysis into fares spread out by complete seven-days weeks from January through April was also performed, in order to look at differences overtime and see how weekly fares varied, in order to find patterns for recommendations. 

## Results:

Based on the analysis, the results followed some logical patterns, in Urban areas there were the greatest number of drivers and rides, and highest total fares, followed by Suburban and then Rural areas. This was fairly predictable as Urban cities have higher populations than Suburban which have higher populations than Rural areas.  Higher population unsurprisingly led to more rides, and more rides leads to a higher total fare amount. However, the average cost of those individual ride fares increases as the city type decreases in population, perhaps because trips are shorter in Urban and Suburban areas than Rural. More analysis would have to be done on ride time in order to be completely sure as to the reason of cheaper fares in Urban vs Suburban and Suburban vs Rural areas. There is also a higher average fare per driver in Rural areas than Urban or Suburban, likely correlated to there being fewer drivers and higher fares per ride.

![image](https://github.com/trosie3/PyBer_Analysis/blob/main/analysis/pyber_summary.png)

The weekly analysis based on a snip of time from Jan to April shows that while each city has some fluctuation the data appears somewhat stable i.e., the data points aren’t dropping or spiking wildly into other lines data. There are some similarities across the data, for example it appears that across all city types total fares increase the third week of February, then decrease going into March, and then begin to increase again in the first week of March. Rural cities appear to fluctuate the least overtime. Urban cities appear to decrease and increase in larger spikes compared to the other city types, though the decreases do not fall below the January low. With only looking at four months it hard to asses more patterns, as this just a small snip of time and limited to one variable ‘total fares.’

![image](https://github.com/trosie3/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary:

Three business recommendations I can make from this analysis:
- Urban cities have the highest total fares, and ride counts followed by a Suburban city, so if looking to expand operations it would be the safest bet to select an Urban or Suburban city. Rural cities would likely have the highest risk for expansion, due to fewer riders and drivers, even though the average fares are higher.
- Mid-to-late February appears to be a time when all total fares increase regardless of city type, and that means more rides, so this timing might be a good to beta-test in a new city.
- Lastly, based on this data February might be a good time in all locations to increase the number of drivers available. Theoretically with higher total fares, knowing that total fares increase with total rides, it appears safe to assume in Feb, March and April more people are looking for rides so perhaps more drivers might increase business. Added bonus, early February appears a bit slower allowing for time to train newer drivers via doing drive-a-longs to learn the areas they will be working in, thus preparing them for mid-late February when business picks up and when they would need to be driving separately not training.

### Limitations:

None of those business recommendations come without risk as they are based on limited data. Given more time, an assessment of a year-long timeline for each city type including how many rides not just total fares would tell us more. Looking into ride time and seeing how it corelated to ride fare would also be helpful, as without it one cannot be sure as to why fares are higher in Rural areas. This extra analysis would allow for clearer patterns and connections to be found. For example: perhaps there is a correlation on holidays, or perhaps summer sees a decrease in rides while winter sees an increase due to weather in Urban and Suburban cities while Rural rides remain steady due to the distance between locations. With the analysis above being restricted to only a few months and only looking at the ‘total fares’, it is difficult to truly say hire drivers now, expand there, or expand during this time of year, etc. with a high level of confidence. 
