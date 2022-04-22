# PyBer_Analysis
## Project overview
The purpose of this project was to perform an exploratory analysis and provide a visual comparison of PyBer's performance in three types of markets:  urban, suburban, and rural.  This information can be used to help determine where to spend marketing efforts to increase ridership and drive revenue.


## Resources
* Software:  Python 3.9.7, Anaconda 4.12.0, Jupyter Notebook 6.4.5
* Data sources:  
  * [city_data.csv](https://github.com/curt0230/PyBer_Analysis/blob/main/Resources/city_data.csv)
  * [ride_data.csv](https://github.com/curt0230/PyBer_Analysis/blob/main/Resources/ride_data.csv)


## Analysis
City and Ride data collected and stored in CSV format was used to perform this analysis.  This data was merged and aggregated to create metrics representing Total Drivers, Total Rides, Total Fares, Average Fare per Ride, and Average Fare per Driver.  Then, columns and indexing were adjusted and data was aggregated again to the Month level.  At this point a pivot table was generated and data was resampled to reorganize aggregate values by city type and day.

## Results
![pyber_summary.png](/analysis/pyber_summary.png)

The summary of rides per market for the first half of the year 2019 demonstrates that there is a higher demand for ridesharing services in urban markets compared to suburban and rural markets.  While average fares in rural cities average fares nearly 30% more and suburban fares around 20% more than fares in urban cities, approximately 68.4% of of all rides originated in urban areas, where suburban and rural rides made up only 26.3% and 5.3% of the shares respectively.  This translates to higher revenue potential.  However, it apepars our urban markets may be overly saturated with drivers at this time as our 2,405 urban drivers only delivered 1,625 rides during this six month term where suburban and rural drivers were busier.

Exploring trends over time we can see that fares and therefore ridership remain relatively steady through the first part of the year.  In spite of collecting higher fares in rural markets the majority of PyBer's revenue comes from urban markets.  The trend remains relatively consistent throughout the first part of the year, but suburban ridership experienced a sharp uptick in the second half of April.

![total_fare_by_city_type.png](/analysis/total_fare_by_city_type.png)

Urban areas have several characteristics that make them more unique:
* Higher population densities and therefore more potential riders and incidentally more potential drivers.  
* More people may choose not to own a car of their own because more destinations are accessible via other methods.  
* Destinations of interest are closer to where people live, meaning trips are much shorter.  

These factors mean the business model in urban areas is more competitive:  shorter trips mean more ride capacity for each driver, and higher population density means more potential riders to keep the cars occupied.  However it appears Pyber ridership is low compared to the number of drivers available and that only 68% of drivers collected fares during this term.  This could represent that the drivers are operating under capacity and potentially at a loss, and could result in a reduction in the number of drivers.

In rural markets homes and businesses are generally spread far apart, which means that most people have cars to support their lifestyle.  Also, incomes tend to be lower, so requesting a driver may seem like an extravagance to more people.  Ride sharing services in markets like this might typically be useful for trips to airports or train stations but wouldn't represent a primary mode of transportation.  The opportunity here is that longer trips can mean higher fares for drivers, and this market may be slightly underserved as rural drivers booked three times as many rides per driver as their urban counterparts.

Suburban markets sit somewhere in the middle, however they seem to share more characteristics with rural markets.  Here, people may be more inclined to use ride sharing services to travel into the city for special events such as sporting events or concerts, or for occasions like celebrations or transportation to and from the airport.  These riders may think of a ride sharing service more like a taxi service.  The uptick in ridership during the month of April might represent a seasonal increase as the spring event season kicks off, or it might represent a shift in thinking where ridesharing is becoming more commonplace in these markets.


## Summary
In summary, PyBer appears to have several opportunities for growing service:
* Increase rider marketing in urban markets to align ridership with driver capacity and improve driver retention.
* Obtain more data for trend analysis in suburban markets.  The April uptick in fares may represent an increase in ridership demand that hasn't been met by driver availability.
* Increase driver marketing in rural markets to align capacity with rider demand.
