### Leaflet_challenge

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. I visited the USGS GeoJSON Feed page [here](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) and chose a dataset to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization. I created a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude. The data markers should reflect the magnitude of the earthquake by their size and and depth of the earth quake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color. I plotted a second data set on my map to illustrate the relationship between tectonic plates and seismic activity. A second set of data was pulled and visualized along side the original set of data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.
![Image1](Images/US_Geological_Image1.png)
