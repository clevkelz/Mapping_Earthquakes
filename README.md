# Mapping Earthquakes

## Applications and Sources Used

An individual account was created on Mapbox (https://www.mapbox.com/) to generate and API to render maps on the browser.  Leaflet, an open-source JavaScript library (https://leafletjs.com/), was used to create layers on the map such as streets and satelitte images.  Data for recent earthquakes, tectonic plates, and major earthquakes came from the following sources:
- USGS GeoJSON Data for All Earthquakes from the Past Seven Days:  https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
- Tectonic Plate Boundaries from a GitHub User:  https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
- Major Earthquake (Magnitude of 4.5 or More) Data from the Past Seven Days:
https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

## Results

### Earthquakes from the Past Seven Days with the Tectonic Plate Overlay

_Street View_

![image](https://user-images.githubusercontent.com/106293233/188282625-0adb6630-2bf3-4332-a017-78b3a2395e29.png)

_Pop-up Layer Selector_

![image](https://user-images.githubusercontent.com/106293233/188283731-945288b8-2a96-434f-85b9-31b4ee8f7646.png)

_Satelitte View_

![image](https://user-images.githubusercontent.com/106293233/188282761-90eba699-e697-49f5-8598-d51e370d0f65.png)

### Adding Major Earthquake Layer

_Street View Showing All Three Layers_

![image](https://user-images.githubusercontent.com/106293233/188283968-a52c1ae3-7679-4627-a750-998a2ce4416c.png)

![image](https://user-images.githubusercontent.com/106293233/188284075-b748bfc5-f408-4320-b65a-d7fa7b3c540e.png)

_Satelitte View Showing Only Major Earthquakes_

![image](https://user-images.githubusercontent.com/106293233/188284157-ea03e1bc-3b60-4157-91e0-093316a69489.png)

### Adding Third Map Style - Dark Tile Layer

![image](https://user-images.githubusercontent.com/106293233/188284639-a4cc9bcf-449d-4543-af04-48dd25efa2fb.png)




