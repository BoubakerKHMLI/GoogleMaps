# Create a Google Maps Instance and place markers into it from database.

Google Maps is a powerful tool that allows developers to create interactive maps for their websites. One of the most useful features of Google Maps is the ability to add markers to the map, which can be used to display location-based information.

In order to add markers to a Google Map, you can use both JavaScript and PHP. The JavaScript code is used to create the map and add the markers, while the PHP code is used to retrieve location data from a database or other data source.

To begin, you must first create a Google Maps API key, which allows you to use the Google Maps API on your website. If you work offline, you can use Google Maps API without a key. In this case, your map will be rapped with a watermark ("For development purpose only") and a dark layer.

In this code, we will be doing the following :

1 - Add the Google Maps API to our file.
2 - Create a Google Maps Instance.
3 - Retrieve markers positions from database using XMLhttpRequest and PHP
4 - Place markers on the map.
5 - Create a click event on each marker to show any eventual position information.
