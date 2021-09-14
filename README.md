# Visualizing Data with Leaflet
![Image](Images/1-Logo.png)
The United States Geological Survey (USGS) provides scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

# Instructions
### I. Basic Visualization
1. **Get your dataset** <br>
[USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) provides earthquake data in a number of different formats, updated every 5 minutes. <br>
Use the `JSON representation` of a dataset from ["All Earthquakes from the Past 7 Days"](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) to pull in the data for visualization.

2. **Import & Visualize the Data** <br>
Create a map using `Leaflet` that plots all of the earthquakes from the data set based on their longitude and latitude. <br>
Your `Markers` should reflect the magnitude of the earthquake by their size (higher the magnitudes the larger) and depth of the earthquake by color (greater the depth the darker). *Note the depth of the earth can be found as the third coordinate for each earthquake.
   * Include `popups` that provide additional information about the earthquake when a marker is clicked.
   * Create a `legend` that will provide context for your map data.
   * Your visualization should look something like the map above.   
![2-Data](Images/2-BasicMap.png)
- - -
### II. More Data Visualization
Plot a second data set from [World Tectonic Plates and Boundaries](https://github.com/fraxen/tectonicplates) to the map to illustrate the relationship between tectonic plates and seismic activity, and visualize it alongside your original set of data. 
   * Add a number of `baseMaps` to choose from as well as separate out two different data sets into `overlayMaps` that can be turned on and off independently.
   * Add `Layer Control` to the map.
![5-Advanced](Images/5-Advanced.png)
