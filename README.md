# PyBer Ride Share Analysis
Ride share analysis for early 2019.

## Overview 
This analysis looks at the weekly for ride share yields in rural, suburban, and urban drivers in early 2019.

## Results
**DataFrame Summary**
The PyBer Ride Share dataframe provides some obvious facts at first glance - urban areas have more rides and rack up more fares than rural areas, for example. 

The more interesting data lies in the "Average Fare per Driver" column and how it relates to "Average Fre per Ride". 
 * The average fare per ride makes sense - $24.53 in urban areas, $30.97 in suburban areas, and $34.62 in rural areas. There is a greater supply of drivers in the urban market, and a lot of demand. Rural areas have far fewer drivers and likely longer rides, causing higher fares per ride.
 * When it comes to the average fare per driver, the numbers are wildly different. The average fare per urban drivers is $16.57, up for suburban drivers to $39.50, and for rural drivers, the average earning goes up to a whopping $55.49.
 * The two above considered had me pondering the drivers per ride:
  * Urban - 1.48 drivers per ride
  * Suburban - 0.78 drivers per ride
  * Rural - 0.624 drivers per ride
 * This demonstrates a lower supply in regards to demand in rural areas, with a surplus of supply compared to demand in urban areas. 

Looking at this dataframe, I ponder how a rural driver could possibly make a living from driving. While the supply is low, the demand is relatively low, and the take home feels unsustainable.

![pyber table](https://github.com/TRACIE-F/PyBer_Analysis/blob/main/Resources/Pyber_Summary_DF.png)

**Fare Summary**
To put it plainly, this summary tells a clear and obvious story on first glance - with more drivers and more rides, urban drivers overall rake in the most money, followed by suburban drivers, and further below them, rural drivers.

Overall, the trend lines run in similar patterns, with some interesting nuances.

  * Urban
    * Urban drivers see several spikes at many times suburban and rural drivers are not - a sustained spike in April and spikes in early March.
  * Suburban
    * Suburban fares seem to lack the spike at the beginning of April happening in urban and rural fares. I am baffled at what might be causing this drop in demand. 
  * Rural
    * With an acknowledgement of bias, I see a potential trend in mid-March. Urban and suburban fare totals spiked during this time, but not rural fare totals. As an individual from a very, very rural area of America, my first question was - are rural drivers driving themselves home on St. Patrick's Day? Depending on the market, this could be an anomaly, but around St. Patrick's Day (March 17), there does appear to be a spike in rides in urban and suburban areas.
    * Overall, seeing the intake over time continues to raise suspicions that rural drivers cannot sustain a viable living as drivers.

![pyber line chart](https://github.com/TRACIE-F/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png)


## Summary

 * When addressing any disparities in the city pay, I would first consider another set of variables: time and distance. Urban drivers are much more likely to have more frequent, shorter rides. Consider possible mandatory minimums for drivers to accept a ride.

 * How active are the 2,405 urban drivers? There appear to be more drivers than the market demands, which is driving prices down. A potential limit on the number of drivers allowed to be active could be in order.

 * As it stands, drivers in rural areas cannot sustain driving as a reliable income source. I would run a marketing campaign for "sober rides home" during St. Patrick's Day, especially in markets where it is commonly celebrated, to shore up more ride opportunities.
