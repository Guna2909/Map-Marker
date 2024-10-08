Mapbox Interactive Map
This project demonstrates how to integrate an interactive map into a webpage using Mapbox GL JS. The map is centered at a specific location with a marker placed at that location. This implementation allows users to pan, zoom, and interact with the map.

Features
Interactive Map: A fully interactive map with zoom and pan functionalities.
Custom Marker: A marker is placed at a specific geographic location (latitude and longitude).
Mapbox Styles: The map uses the streets-v9 style from Mapbox, but this can be easily customized.
How It Works
Mapbox GL JS: The map is created using the Mapbox GL JS library, which is loaded via the Mapbox CDN.
Access Token: You must provide a valid Mapbox Access Token to use their mapping services. In the example, the token is set in the mapboxgl.accessToken variable.
Centering the Map:
The map is centered at [77.12, 11.02] (longitude, latitude).
Adding a Marker:
A marker is added at the same coordinates using the mapboxgl.Marker() method.
