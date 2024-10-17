#### Report


#### Presentation


#### Links
- https://en.wikipedia.org/wiki/Evapotranspiration
- https://en.wikipedia.org/wiki/Baseflow


#### Instructions:
This data deals with baseflowLinks to an external site.. Each row corresponds to one data point (a river segment during one month). The columns are:

- Date – number of days since 01/01/0000
Segment id – an identifier of the segment of river; it can be treated as a categorical variable
x/y – the spatial location of the gaging station at which observations are obtained
- EvapotranspirationLinks to an external site. – the evapotranspiration amount of an area adjacent to the river segment in the given month
- Precipitation - the precipitation amount of an area adjacent to the river segment in the given month
- Irrigation pumping - the amount of groundwater pumped out for irrigation in an area adjacent to the river segment in the given month
- Observed – observed baseflow

The target variable is Observed. We want to use linear regression to predict what the baseflow will be.

Date has some idiosyncrasies. Take make it easier to work with, subtract 693963 from the value. The new value is the number of days since Jan 1, 1900.

Your task is to experiment with linear regression on this dataset. This is a difficult dataset to interpret, and most of your time will be looking at scatterplots, looking at the data over time, looking at positional data, looking at individual segments, and doing background research. Just running regression and looking at the p values for different attributes is most definitely not enough.