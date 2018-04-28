# mapbox-view-bounds

<p>This demonstration uses map.unproject() to create a geojson quadrangle for the main map's view.  As you drag, zoom, pitch, and rotate the map, the polygon will update, and can be seen visualized on the inset map.</p>

View the demo live at [https://chriswhong.github.io/mapboxgl-view-bounds/](https://chriswhong.github.io/mapboxgl-view-bounds/)

<p>map.getBounds() does not produce the same quadrangle, rather it will return the largest "north-up" rectangle that fits within the current map view. </p>
<p>This approach is documented in <a href="https://github.com/mapbox/mapbox-gl-js/issues/2375">this github issue</a>.

