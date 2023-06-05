# Water woes in the Bronx
For this project, I analysed water problems facing New Yorkers. Here is the [final published story](https://rentwirenyc.substack.com/p/water-woes-in-the-bronx)


# Getting the Data

* [Water-related complaints](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/data)
* [Drinking Water Quality Distribution Monitoring Data](https://data.cityofnewyork.us/Environment/Drinking-Water-Quality-Distribution-Monitoring-Dat/bkwf-xfky)
* [Total Population by community district](https://furmancenter.org/neighborhoods/)
* [Borough Boundaries](https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm)
* [Income levels by community district](https://furmancenter.org/neighborhoods/)
* [Demographic data by community district](https://furmancenter.org/neighborhoods/)


# How I analysed rates of water complaints by community district
I collected number of complaints by community district for a period of 12 months and joined it to population data from the Furman Center. <br>
I then normalised the data against population. <br/>
I then mapped the rates of complaints on a chloropleth map

# How I analysed coliform rates in the water
NYC data on water tank inspections is on USGS Eastern State Plane coordinates.<br/>
I converted this to latitude and longitude using CRS 4326 <br/>
Then I mapped the results. 

# How I analysed rates of water-related complaints in poorer community districts
I joined data on income levels by community district to the data on water problem complaints <br/>
I made the decision to consider the portion of the population in the lowest income level, less than 20000USD, as a measure of poverty levels. However, given NYC's cost of living, perhaps a higher cutoff could also be appropriate. <br/>
I then visualised the resulting distribution to show the disparities I found. <br/>

# How I analysed rates of water-related complaints in majority white community districts
I joined data on the portion of the population that is white by community district to the data on water problem complaints <br/>
I then visualised the resulting distribution to show the disparities I found in terms of water problem complaints <br/>


# Tech:
#Python, #MicrosoftExcel, #Datawrapper, #Mapping

You can read is the final published story [here](https://rentwirenyc.substack.com/p/water-woes-in-the-bronx)
