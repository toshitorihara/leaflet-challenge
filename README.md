# Visualizing Data with Leaflet
The USGS (United States Geological Survey) provides scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

# Instructions
### Basic Visualization
![2-Data](Images/2-BasicMap.png)

1. **Get your dataset** <br>
[USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) provides earthquake data in a number of different formats, updated every 5 minutes. Use the JSON representation of a dataset of ["All Earthquakes from the Past 7 Days"](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) to pull in the data for visualization.

2. **Import & Visualize the Data** <br>
Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.
   * Your data markers should reflect the magnitude of the earthquake by their size and and depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.
   * **HINT:** The depth of the earth can be found as the third coordinate for each earthquake.
   * Include popups that provide additional information about the earthquake when a marker is clicked.
   * Create a legend that will provide context for your map data.
   * Your visualization should look something like the map above.   
- - -
### More Data Visualization
![5-Advanced](Images/5-Advanced.png)

Plot a second data set from [**World tectonic plates and boundaries**](https://github.com/fraxen/tectonicplates) on your map to illustrate the relationship between tectonic plates and seismic activity, and visualize it alongside your original set of data.
* Plot a second data set on our map.
* Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.
* Add layer controls to our map.
