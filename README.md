# Module 15 Challenge - Leaflet Challenge

## Background
* The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change.
* Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.
* The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data.
* They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it.
* In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Instructions
### Create the Earthquake Visualization
* Your first task is to visualize an earthquake dataset.
* Complete the following steps:
* Get your dataset. To do so, follow these steps: The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and choose a dataset to visualize.
* When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization.
* Import and visualize the data by doing the following:
* Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
* Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color.
* Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
* Include popups that provide additional information about the earthquake when its associated marker is clicked.
* Create a legend that will provide context for your map data.

## Requirements

### Map (60 points)
* TileLayer loads without error (20 points)
* Connects to geojson API using D3 without error (20 points)
* Markers with size corresponding to earthquake magnitude (10 points)
* A legend showing the depth and their corresponding color (10 points)

### Data Points (40 points)
* Data points scale with magnitude level (10 points)
* Data points colors change with depth level (10 points)
* Each point has a tooltip with the Magnitude, the location and depth (10 points)
* All data points load in the correct locations (10 points)

## Grading

### This assignment will be evaluated against the requirements and assigned a grade according to the following table:

Grade Points

A (+/-)	90+

B (+/-)	80–89

C (+/-)	70–79

D (+/-)	60–69

F (+/-)	< 60

## References
* Dataset created by the United States Geological Survey.
