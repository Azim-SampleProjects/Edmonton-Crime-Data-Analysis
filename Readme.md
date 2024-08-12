# Statistical Analysis.

## 2009-2019.

* Analyzing Crime Index for Alberta and its two major cities, Edmonton and Calgary.
* Analyzing Violent Crime Severity Index for Alberta, Edmonton and Calgary.
* Analysis of the above two led us to our Problem Statement.
* As per Stats Canada, Violent Crime consists of Assault, Sexual Assaults, Robbery and Homicide.
* Analyzing Edmonton Crime data between 2009 and 2019.

## 2016.

* Analyzing Edmonton Neighborhood Crime data filtered t0 2016 to incorporate 2016 Demographic Census data which includes, Education Level, Income Level and Employement Status.
* Cleaned data to remove Industrial Area/neighborhoods that are not included in 2016 Residential Census.
* For this Analysis, we included Property Crimes (Break and Enter, Theft from Vehicle, Theft Of Vehicle, Theft over $5000) with Severe Violent Crimes (Assault, Homicide, Sexual Assaults and Robbery).
* Merged data with Neighborhood Property Assessment Values filtered to 2016.
* Performed Correlation Analysis.
* Performed Kmeans Clustering.
* Analyzed the results by cluster.
* Statistical Tests on Clusters (non parametric test for discrete variables, since all the columns are counts.)
* Quick analysis of Calgary Crime and Disorder Statistics without Census Data: filtered to 2016.
* KMeans Clustering of Calgary 2016 data.
* Comparison of Edmonton HOT Crime Cluster with Calgary HOT Crime Cluster.

## Testing Redistribution of 'Income_No Response' and 'Employment_No Response' columns.

Tested to see if we could redistribute the columns, Income_N Response and Employemnt_No Response by redistributing their values to their other columns within their category to see if it made a siginificant difference to the other respective columns within their groups.

## Summary & Conclusion

In 2016, crimes were reported in all neighborhoods in the City of Edmonton. However, certain neighborhoods such as Downtown, Central McDougall, Boyle Street, Oliver, and Alberta Avenue consistently had the highest number of Violent and Property Crimes. Although we do not have precise information on the exact locations within these neighborhoods where the crimes occurred, a comparison with the City of Calgary showed a similar pattern, with the concentration of crimes occurring within the city center, specifically in Downtown Calgary Commercial Core and the Calgary Beltline. Our KMeans cluster analysis confirmed this for both cities.

However, we must note that 2016 was not the most representative year for our analysis, as there was a sharp decrease in violent crimes for both cities between 2015 and 2016. Additionally, in May 2016, a wildfire began southwest of Fort McMurray, Alberta, which forced upwards of 88,000 people from their homes, making it the largest wildfire evacuation in Alberta's history. On a more positive note, the Rogers Place, a multi-use indoor arena in Edmonton and the new home of the Edmonton Oilers hockey team, was officially opened on September 8, 2016.

Despite the decrease in crime rates, Edmonton still had the highest Crime Severity Index. However, due to time constraints, we were unable to perform a more in-depth analysis of the data. Given additional time, some of the areas we would have liked to explore include the ratio of crimes committed by neighborhood to the total population of that neighborhood, the precise locations and times of crimes, and the role of the municipal government in combating crime. We are particularly interested in examining the impact of different types of municipal government, given that Edmonton has had a more liberal municipal government for decades, while Calgary has historically had a more conservative municipal government up until Mayor Nanshi, who was a centrist. This would allow us to answer the question of whether conservative municipal governments are more effective than liberal ones in fighting crime.

Hence, in addition, given the patterns observed in Edmonton and Calgary, we would have liked to extend our analysis to other Canadian cities to determine if similar trends exist. Specifically, we would have explored the concentration of crimes in the downtown cores of other major Canadian cities, such as Toronto, Vancouver and Montreal, and compared their crime rates to those of Edmonton and Calgary. However, due to time constraints, we were unable to pursue this line of inquiry.
