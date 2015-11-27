# Novicell Simple Map

### A simple module to load a google map with a marker on it.

**Requires:** It requires something to get the LAT, LNG and ZOOMLEVEL, of the marker, and append it to the `map-canvas` element, as data-attibutes.

For Umbraco 7, use something like: https://our.umbraco.org/projects/backoffice-extensions/angulargooglemaps
For Drupal 7/8, use something like: https://www.drupal.org/project/gmap or https://www.drupal.org/project/simple_gmap
For Wordpress, use something like: http://www.advancedcustomfields.com/resources/google-map/

### Usage
Include the `novicell.map.js` in you project and add the following HTML and JS:

```html
<div id="map-canvas" data-lat="56.109574" data-lng="10.155361" data-zoom="15"></div>
```
**Remember to set a height for the map-canvas element!**

```javascript
$(document).ready(function(){
    novicell.map.init('map-canvas');
});
```
Where `map-canvas` is the id of the element, which should load the map.

# License
The Novicell Simple Map is licensed under the MIT Open Source license.
