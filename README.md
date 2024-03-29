# USGC Global Earthquake Data Visualization with Leaflet

## Overview

The United States Geological Survey (USGS) is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 

These tools collect a massive amount of data from all over the world each day, but they lacked a meaningful way of displaying it. I visualized their earthquake data using Leaflet allowing them to better educate the public and other government organizations on issues facing our planet.

## Technology Used:

| Technology   		| Description    							|
| :---         		|     :---:      							|
|  Github      		| HTML, CSS, Javascript, Github pages 							|
|  API's       		| Mapbox API, GeoJSON 							|
|  Leaflet    	| Map Library    		|
|  Website    	| [USGC Earthquake Data Visualization](https://amairanyg.github.io/USGS-Data-Vizualization-with-Leaftlet/)   		|

![5-Advanced](Images/5-Advanced.png)


### A) Data set

   * Utilized current earthquake data provided by the USGS, which is updated every 5 minutes and includes all earthquake data for the Past 7 Days. Live API data was obtained from [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page as a JSON representation. The URL of this JSON was used to pull in the data for the visualization.

   * Plot a second data set on the map to illustrate the relationship between tectonic plates and seismic activity. This second dataset was pull from <https://github.com/fraxen/tectonicplates> and was visualized along side the original dataset. 



### B) Import & Visualize Earthquake Data

   * Created a map using Leaflet that plots all of the earthquakes from dataset based on their longitude and latitude.

   * Data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color.

   * Included popups that provide additional information about the earthquake when a marker is clicked.

   * Created a legend that provides context for the map data.
   
   * A number of base maps were added to choose from as well as separate out the two different datasets into overlays that can be turned on and off independently.
   
   * Added layer controls to the map.
  

