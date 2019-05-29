# Google Health Searches Visualizations


In the data visualization class at the University of San Francisco’s Master’s in Data Science Program, I was tasked with choosing a dataset to present visualizations. Healthcare accounts for 17.9% of the US economy, and searching healthcare related data sets revealed   “Health Searches by US Metropolitan Area” on the Kaggle link at https://www.kaggle.com/GoogleNewsLab/health-searches-us-county. This dataset looks at Google Search data and measures the frequency of searches by the public of specific disease categories at the local level. These disease categories include common health issues in the United States, such as Cancer to Diabetes, and reflect the health care information gathering of millions of Americans. The health conditions were selected from the Community Health Status Indicators (CHSI) which provides key metrics for local communities in the United States, and overall trends across the country. 

All Python graphs can be found in `HealthSearchVisualizations.pdf` and supplemental code can be found in `graph_code.ipynb`. Tableau files are also posted for reference

A few of my favorite graphs are included below:

![Alt text](images/boxplot.png?raw=true "Title")

This boxplot allows us to see the amount variability in the search score (Google’s own metric) in health searches from 2004 to 2016. It is interesting there a wide range for both diabetes and depression. The variability can be explained for 1 or 2 regions: 1) variability in the number of searches in each county or 2) variability in the number of searches in each year. Cancer, however, appears to have the least amount of variability as this makes sense - it’s been a consistent topic of discussion whereas diabetes and depression/mental health have been more of a discussion in recent years.

![Alt text](images/scatter1.png?raw=true "Title")
![Alt text](images/scatter2.png?raw=true "Title")

It is known that obesity can lead to Type 2 diabetes, and it is interesting that the search results between diabetes and obesity is extremely correlated. To show that this isn’t just a result of all searches I displayed cardiovascular diseases to depression, which may or may not be linked in one form or another, however, the search results are not as closely correlated as searches between diabetes and obesity. 

![Alt text](images/bubblemap.png?raw=true "Title")

This graph shows the most prominent search in some of the major cities in the United States. The size of the bubble shows the relative amount of searches compared to other cities.

![Alt text](images/stacked_area.png?raw=true "Title")

This stacked area graph presents a dramatic illustration of how the public is increasingly obtaining health care information by searching online. Looking at the graph as a whole, searches since 2004 for the composite group of health conditions has doubled, and interest in all eight individual conditions have also expanded over this time interval. Interestingly, the frequency of searches does not necessarily correlate with the frequency of the condition in the general population, as searches for stroke information are more common than cardiovascular searches even though strokes are more infrequent than cardiovascular disease. 
