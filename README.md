# PyBer_Analysis

## Overview of the analysis: 
The purpose of this analysis was to provide business recommendations to PyBer's CEO. To do this I broke down PyBer's data into each type of city (Urban, Suburban, Rural), and looked into driver counts, fares, and rides to gather useful numbers such as average fare per ride and driver. A deeper analysis into fares spread out weekly from Janurary through April, by complete seven-day weeks, was also performed in order to look at differences overtime and see what recommendations that might lead to.

## Results: 
Based on the analysis, the number of rides decrease as city type decreases Urban to Rural, which logically lines up as more people live in Urban areas then Suburban or Rural, and more people in Suburban than Rural. This also corresponds to total fares; more rides would mean more fares. However, the cost of those fares increases as the city type decreases, perhaps because trips are shorter in Urban and Suburban areas than Rural. More analysis would have to be done on ride time in order to be completely sure as to the reason of cheaper fares in Urban vs Suburban and Suburban vs Rural. There is also a higher average fare per driver in rural areas than urban or suburban, likely correlated to their being fewer drivers and higher fares per ride. 

image--pyber summary

The analysis based on a snip of time from Jan to April shows that while each city has some fluctuation the data are not spiking wildly in any direction and appears somewhat stable i.e., the data points aren’t dropping or spiking into other lines data. There are some similarities across the data, for example it appears that across all city types fares increase the third week of February and then decrease going into March and then begin to increase again in the first week of March. Rural cities appear to fluctuate the least overtime. Urban cities appear to decrease and increase in larger spikes compared to the other city types, though they do not fall below the January low. With only looking at four months it hard to asses more patterns, as this just a small snip of time and limited to one variable ‘total fares.’

image--pyber summary plot

## Summary:
Three business recommendations I can make from this analysis:
- Urban cities have the highest total fares, and ride counts followed by a Suburban city, so if looking to expand operations it would be the safest bet to select an Urban or Suburban city. Rural cities would likely have the highest risk for expansion, due to fewer riders and drivers, even though the average fares are higher.
- Mid-to-late February appears to be a time when all fares increase regardless of city type, and that means more rides, so this timing might be a good to beta-test in a new city.
- Lastly, based on this data February might be a good time in all locations to increase the number of drivers available. Theoretically with more fares, and knowing that total fares increase with total rides it appears safe to assume in Feb, March and April more people are looking for rides so perhaps more drivers might increase business. Added bonus is that early February is bit slower allowing for time to train newer drivers via doing drive-alongs to learn the areas they will be woring in, thus preparing them for mid-late Feburary when bisuness will pick up when they would need to be driving seperately. 

### Limitations:
None of those business recommendations come without risk as they are based on limited data. Assessment of a year-long timeline for each city type including how many rides not just total fares would tell us more. This would allow for more or clearer patterns and connections to be found such as: perhaps there is a correlation on holidays, or perhaps summer sees a decrease in rides while winter sees an increase due to weather and walk-ability in Urban and Suburban cities while Rural remains steady due to the distance between locations. With the analysis above being restricted to only a few months and only looking at the total fares week by week, it is difficult to truly say hire drivers to grow here, expand there, or expand now, etc. 

Given more time, looking into ride time and seeing how it corelated to ride fare would also be helpful in being able to say 'in rural areas rides are longer and therefore fares are higher, and with few drivers doing longer commutes with fewer rides that is why their per ride fare is higher'. Without that is it an educated guess but more data is needed. 
