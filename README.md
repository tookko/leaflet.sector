# Sector
A circle sector overlay with a certain radius in meters, theta angle and rotation angle for Leaflet.

Extends [Circle](http://leafletjs.com/reference.html#circle). Use [Map#addLayer](http://leafletjs.com/reference.html#map-addlayer) to add it to the map.

    L.sector([50.5, 30.5], 200, 30, 45).addTo(map);

## Creation

| Factory                                                                                                                                                                                                     | Description                                                                                                                          |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| L.circle( <[LatLng](http://leafletjs.com/reference.html#latlng)> LatLng, <Number> radius, <Number> theta, <Number> azimuth, <[Path options](http://leafletjs.com/reference.html#path-options)> options? ) | Instantiates a sector object given a geographical point, a radius in meters, theta angle, azimuth, and optionally an options object. |

