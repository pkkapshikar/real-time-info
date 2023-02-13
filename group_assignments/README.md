# Project Proposal

### Introduction of research question
We will be exploring which bus line among the AC Transit 19, 20, and 51A would benefit most from real-time information displays at some of their bus stops. These bus routes run through Downtown Oakland, Alameda and South Oakland and include pockets that are heavily non-white, Asian and Black. 

### Why this topic matters
Real-time information displays inform transit riders about when the next bus is arriving at their stop. These displays provide convenience for all transit riders, but they are especially useful for those who lack smartphones or access to the Internet and are therefore unable to access bus arrival times by any other means, especially the elderly (Shrestha et al. 2017). Real-time information at bus stops provide the most benefit for stops serviced by routes that have more unreliable schedules and infrequent headways as riders at these stops likely have longer or more unpredictable wait times. Installing real-time information can also enhance ridership on a given route. A New York City study found that real-time information has also been associated with increases in ridership especially on long and heavily-used routes (Brakewood et al. 2015). At the same time, the installation of real-time information (RTI) also has the potential to improve operations by allowing transit agencies to assess the performance of bus routes in real time (Cats & Loutos 2016). Therefore, we believe this is an important topic as it has the potential to improve rider satisfaction, increase ridership and potentially improve bus operations. 

### Spatial scope (and why it matters)
For this project, we will be evaluating the AC Transit 19, 20, and 51A lines, which each run between the cities of Oakland and Alameda, California. These routes also serve multiple heavy rail (Bay Area Rapid Transit) stations, operate through Downtown Oakland and serve neighborhoods of differing profiles. These routes also operate at various frequencies with the 51A being the most frequent and the 19 being the least frequent, thereby making it a more representative sample of bus routes operated by AC Transit. We will be using demographic data from census tracts that each of these three bus lines pass through to aid our analysis of which bus line would benefit most from real-time information displays. Demographic data could point towards certain priority populations without access to smartphones (i.e. seniors) and those who are more heavily reliant on buses to get around (i.e. BIPOC and low-income populations). There is also an equity angle to this project as communities as marginalized commmunities who are more likely to rely on transit will likely benefit from greater convenience and comfort with the presence of real-time information. Other relevant spatial features could also include bus stop location relative to population density and frequent transit riders, delay information (buses more prone to delays might benefit from real-time information as passengers will know when buses are coming outside scheduled arrival times), or some combination of these factors and the aforesaid variables. These variable can be plotted using a variety of software including plotly, geopandas, contextily, etc. 

### Data sources (including links)
We have used AC Transit's bus route GIS shapefile and bus stop GIS data shapefile from AC Transit's Data API & Resource Center. We also used census data from the US Census Bureau. We have also directly sourced data from AC Transit surrounding boarding/alighting at each stop by bus line and compiled delay statistics for each line using 511 SF Bay information portal. 

AC Transit's Data API & Resource Center URL: https://www.actransit.org/data-api-resource-center

U.S. Census Data: https://data.census.gov/

SF Bay 511: https://511.org

### Intended analysis and visualizations
For each of the 19, 20, and 51A lines, we analyzed and compared demographic information from the census. We selected demographic characteristics that we believed would reveal which line served populations that were comparatively the most mobility-disadvantaged or had the greatest inaccessibility to technology and, therefore, would likely benefit the greatest from real-time information displays. We decided to analyze general demographic characteristics (e.g. age, income, and race), transportation characteristics (e.g. percent of workers commuting by car), and housing characteristics (e.g. median rent, number of residents in renter occupied units) of each tract that the lines run through. We have also worked to visualize delays across the three bus routes.  

### Hypotheses
We believe that the 51A line would benefit most from real-time information displays at some of their bus stops because it has the longest route out of all of the bus lines. Additionally, the population in the tracts that the 51A runs through are more likely to ride public transit than those in the tracts of the other two lines and it traverses heavily minority areas in Downtown Oakland, Alameda and South Oakland (near Fruitvale BART station) making real-time information more beneficial for existing riders as well as potentially attracting more riders from Alameda. 

### References

Brakewood, C., Macfarlane, G.S. & Watkins, K. (2015). The Impact of Real-time Information on Bus Ridership in New York City. *Transportation Research Part C: Emerging Technologies*, 53, 59-75. 

Cats, O. & Loutos, G. (2016). Real Time Bus Arrival Information System: An Empirical Evaluation. *Journal of Intelligent Transportation Systems*, 
20(2), 138-151. 

Shrestha, B.P., Millonig, A., Hounsell, N.B. & McDonald, M. (2017). Review of Public Transport Needs of Older People in European Context. *Journal of Population Ageing*, 10, 343-361.
