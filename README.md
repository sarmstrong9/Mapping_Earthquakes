# Mapping_Earthquakes

## Project Overview
This project uses the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake is visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake will have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.

## Basic Project Plan
- Purpose
    - The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

- Tasks
    - Use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes in the last seven days from the GeoJSON data. Use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.
    - Earthquake data is plotted in relation to the tectonic plates’ location on the earth, and a separate layer is created to show all the earthquakes with a magnitude greater than 4.5 on the map, 
    - A third, dark map layer is presented for additional views.

## Deliverables
- Deliverable 1: Add Tectonic Plate Data (35 points)
    - Using knowledge of JavaScript, Leaflet.js, and geoJSON data, add tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data. <p> 
- Deliverable 2: Add Major Earthquake Data (50 points)
    - Using knowledge of JavaScript, Leaflet.js, and geoJSON data, add major earthquake data to the map using d3.json(). Add color and set the radius of the circle markers based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().<p>
- Deliverable 3: Add an Additional Map (15 points)
    - Using knowledge of JavaScript and Leaflet.js add a third map style to the earthquake map.