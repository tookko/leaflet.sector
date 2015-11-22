# Sector
A circle sector overlay (with a certain radius in meters, theta angle and azimuth) for Leaflet.

Extends [Circle](http://leafletjs.com/reference.html#circle). Use [Map#addLayer](http://leafletjs.com/reference.html#map-addlayer) to add it to the map.

## Installation

    bower install leaflet.sector

## Preparing your page

Include the single JavaScript file on your page somewhere after Leaflet:

```html
<script src="bower_components/leaflet.sector/leaflet.sector.js"></script>
```

## Usage

```javascript
L.sector([50.5, 30.5], 200, 30, 45).addTo(map);
```

## Creation

| Factory                                                                                                                                                                                                     | Description                                                                                                                          |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| L.sector( <[LatLng](http://leafletjs.com/reference.html#latlng)> LatLng, <Number> radius, <Number> theta, <Number> azimuth, <[Path options](http://leafletjs.com/reference.html#path-options)> options? ) | Instantiates a sector object given a geographical point, a radius in meters, theta angle, azimuth, and optionally an options object. |

