# surfs_up

### Overview of the analysis
The purpose of this analysis was to analyze the temperatures on Oahu Island in the months of June and December in an effort to determine if a surf shop could be viable year-round. Using Python, Pandas functions, and SQLAlchemy, a SQLite database of weather on the island was queried to find an answer.

#### Results
![image](https://user-images.githubusercontent.com/107162310/184002261-4e1dc0fb-f68a-41b9-98b6-a53947d35c2d.png)

![image](https://user-images.githubusercontent.com/107162310/184002336-9a292433-7313-44e5-9c32-f924a05b0c34.png)

* There were far more temperature measurements taken in June than in December, to the tune of an 11% reduction in sample size, so it's possible that the data for December is less accurate. For instance, I could see there being a lower minimum than 56 degrees which simply wasn't measured.
* The mean temperature for December is just under 4 degrees cooler than in June. Setting aside my complete lack of surfing experience, that 71.04 degree average in December sounds like perfectly fine surfing weather to me.
* There's little difference between the warmest day in June than in December, however their coldest days have nearly a 10 degree difference.

#### Summary
The data provided for analysis allowed for a decent comparison of the expected temperatures between the months of June and December. Given the fairly similar mean, median, and max temperatures, a surf shop open year round on Oahu seems like a viable business plan. That said, this analysis only looked at two months of the year, albeit from polar opposite seasons. I'd suggest performing the same query, but this time for a month in spring and in autumn. After all, if the surf shop is to be open year round, it would make sense to get a look at weather data in all four seasons. This analysis is also lacking one more important consideration, namely precipitation. Surfers might partake in rain, but it seems unlikely that ice cream buyers would do the same. An additional query on the precipitation for June, December, and the spring and autumn months could help the business anticipate the chances of half of their business model washing away any given day.
