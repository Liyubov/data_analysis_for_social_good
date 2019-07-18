# Data analysis methods 

Here we apply some standard data analysis methods to analyze and visualize the data for social good. 
The methods we are using are mostly based on:

1. network theory 
https://github.com/Liyubov/networks_beauty

2. stochastic processes 
https://github.com/Liyubov/networks_random_walking

Repository for analysis of mobility data and trajectories analysis https://github.com/Liyubov/mobility_analysis


Projects, which inspired creation of this repository:

1. Unicef school mapping project 
https://www.unicef.org/innovation/school-mapping

2. Lecturers without borders project, hosted at CRI 
www.scied.network 

3. Open global mobility data 
from https://bluehub.jrc.ec.europa.eu/migration/app/index.html?state=5cc845a97758cd17cdecd1fb 


# Data visualisation 

First of all, we start with visualisation of the data. 
We are working with data from csv files structured as:
   |institution name | institution type| institution location| institution contact| institution properties|
The notebooks here are dedicated to data visualisation and data analysis
Example of open data files can be found here https://data.cityofnewyork.us/Education/School-Point-Locations/jfju-ynrr

### Sources for interactive maps

Links from Hugo on blocks:
- bl.ocks.org : the main community platform for D3js devs and their nominative porfolio.
-- https://bl.ocks.org/mbostock - Mike Bostock is the creator of D3js
--- https://bost.ocks.org/mike/ - Mike Bostock  tutorials. More links there.
---- Command-Line Cartography
---- Towards Reusable Charts
---- Thinking with Joins
-- https://bl.ocks.org/jasondavies -- Best budy of mbostock for maps
-- https://bl.ocks.org/hugolpz/c89a76096c070a5a7d23 - Hugo Lopez, was a leading D3js cartographer back in 2014. Very rusty fingers now (2019). Globe tour
--- Stackoverflow answer for focus on something !

Codes browsers :
- Blocksplorer : http://bl.ocksplorer.org , tap in bl.ocks.org. Really 2014.
- Observable : https://observablehq.com/search?query=d3.geo -- by mbostock, more 2018

Toolkits:
- https://jsoneditoronline.org -- for topojson data

# Code

### data_on_map_visualisation.ipynb 

We visualise datafiles from two example files 
1. the csv file with data on randomized anonymized educational institutions data
2. the dbf with open data from https://toolbox.google.com/datasetsearch/search?query=schools%20around%20the%20globe&docid=2T2%2BDeqbWNzcqeorAAAAAA%3D%3D 
The example of data are randomized data from educational centres around the world. 
Due to the data privacy reasons we are visualising only in the average characteristics of the data, such as average number of data points and average parameters of datapoints (such as number of resources needed in datapoints etc.).

### mobilitydata analyzer.ipynb 

We analyze the mobility data from open GLOBAL mobility data. (work in progress)
More information on it is here https://github.com/Liyubov/mobility_analysis


###  	analysis_mobility_trajectories_oh_data.ipynb 
We analyze LOCAL mobility data 
(work in progress for analysis of individual trajectories)
