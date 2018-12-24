# Flight Delay Characteristics for US Flights in 2005
## by Anthony Andersland


## Dataset

The data constisted of approximately 7 million US flights. Arrival and departure delays in minutes as well as the delay causes were used from this dataset. Approximately 148,000 records were removed from this data set for having null values for arrival/departure delays.

Dataset - [here](http://stat-computing.org/dataexpo/2009/the-data.html)
Definitions - [here](https://www.transtats.bts.gov/Fields.asp?Table_ID=236)


## Summary of Findings

In the exploration I found that there is a yearly pattern to delays in flights. These typically follow the heavy travel periods such as summer months and around holidays. While some specific delay reasons follow this pattern such as National Airspace System (NAS) and late aircraft delays. There are also some that follow no specific pattern such as weather and security delays. While carrier delays are frequent throughtout the year, the larger impact to the system are weather delays with a higher average delay.


## Key Insights for Presentation

For the presentation I focus on the arrival and departure delays along with the specific delay reasons. I start with the overall volume of flights followed by the overall departure and arrival delays using a heatmap. The heatmap was very useful in showing an entire year with the categorical variables of weekdays and months. I then show the total flight delays for the year followed by visuals for each specific delay reason.


## Resources
* https://www.transtats.bts.gov/Fields.asp?Table_ID=236
* https://docs.python.org/3/library/bz2.html
* https://stackoverflow.com/questions/27333671/how-to-solve-the-10054-error
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.append.html
* https://scentellegher.github.io/programming/2017/07/15/pandas-groupby-multiple-columns-plot.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.sort_values.html
* https://www.weather.gov/mob/events
* https://pandas.pydata.org/pandas-docs/stable/categorical.html
* https://stackoverflow.com/questions/35414431/how-to-define-user-defined-function-in-pandas
* https://aspmhelp.faa.gov/index.php/Types_of_Delay
* https://seaborn.pydata.org/generated/seaborn.countplot.html
* https://seaborn.pydata.org/generated/seaborn.heatmap.html
* https://seaborn.pydata.org/tutorial/color_palettes.html
* https://stackoverflow.com/questions/32542957/control-tick-labels-in-python-seaborn-package
* https://stackoverflow.com/questions/26540035/rotate-label-text-in-seaborn-factorplot
* https://en.wikipedia.org/wiki/North_American_blizzard_of_2005