# Leaflet

This project is about visualizing an earthquake data set with data from the USGS.
The USGS provides earthquake data in a number of different formats, updated every 5 minutes. 
After visiting the USGS GeoJSON Feed page and picking a data set to visualize, I had to use the URL of this JSON to pull in the data for the visualization.

 So the first step I followed is to get the data, import it and then visualize using html and javascript. Then I created a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude. The expected outcome here is to have data markers that reflect the magnitude of the earthquake by their size and and depth of the earth quake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color. Also, popups that provide additional information about the earthquake when a marker is clicked are included as well as a legend that will provide context for the map data.
The visualization should look something like the map below

![image](https://user-images.githubusercontent.com/75787486/124520431-7f0ac580-ddba-11eb-8a55-34ef44d44c6f.png)

The second step on this project is about plotting a second data set on the map and add a number of base maps to choose from as well as separate out both data sets into overlays  with layer controls) that can be turned on and off independently. The goal is to illustrate the relationship between tectonic plates and seismic activity. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.
The illustration should look something like the map below

![image](https://user-images.githubusercontent.com/75787486/124520651-0bb58380-ddbb-11eb-9c0a-65fdad40101d.png)
