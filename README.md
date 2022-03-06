# SurfsUp_Challenge
Analysis regarding temperature trends before opening a surf shop. Specifically, temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Overview of the analysis: 

The purpose of this analysis was to provide an overview analysis of the temperatures of the months of June and December. This data is critical for the analysis of the potential ice cream and surfing startup. The analysis was produced from a query of sqlite flat data files containing weather data. The query was run to produce results containing the temperature in the months of June and December. This will allow the ownership team to evaluate how the temperature changes between the summer and winter months. Further, this evaluation will provide good insight on how ice sales may fare during these extreme periods.

## Results: 
The following is a bulleted list with three major points from the two analysis deliverables. The images below show the statistical output regarding the temperature queries for the months of June and December, respectively.

![June_Stats_Results](Resources\june_stats_results.PNG)

Figure 1: June Results

![December_Stats_Results](Resources\december_stats_results.PNG)

 Figure 2: December Results

 - The mean temperature between December and June are similar enough. The temperature mean is only off my 3 significant figures. Considering that the December temperatures are anticipated to be colder, given it's winter, it's surprising that the temperatures are on the warmer side. Given this fact, it would not out of the oridinary to have ice cream in such warmer temperatures. The same can be said for the max temperature. The maximum temperature is in the low eighty degrees in both June and December, which is perfect for ice cream.

 - For the month of June, the mean temperature and median temperature are about the same. This suggests that the data is quite uniform and predictable with respect to the temperature distribution. For the month of December, the mean temperature and median are also the close enough to suggest that the data is uniformly distributed. 

 - The standard deviation for both June and December is 3 degrees, not accounting for further siginificant digits. With respct to warmer weather, this would suggest that the fluctuation in weather is minimal. Within 2 standard deviations, the temperature continues to remain in the 70 degree weather. This type of weather is ideal for getting ice cream, and would be safe to assume that the start up would do well even in December.

## Summary: 

From the perspective of selling ice cream and surfing, the weather in Hawaii never ceases to fail. Both the summer and winter months, are warm enough to do one or the other, or both. The temperatures continue to be maintained within the seventy degree range, and even manage to get into the 80 degrees. 

An additional query to perform would be a chronological anaylsis of the temperature across the year. Essentially, all the data for each month would be aggregated to measure what the mean temperature every month. This would provide a bigger picture for how the temperature is over the year and not just the extreme months.

The last query to perform would be the precipitation data for the extreme months. Just because the temperature is warm, it does not mean it won't rain. In that case, there wouldn't be anyone buying ice cream which may hurt the business's bottom line. It would be important to know if all the days of December are warm, but 70% of the days are raining. This hypothetical scenario will provide valuable insight for the business.
