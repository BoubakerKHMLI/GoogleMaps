# A comprehensive guide on adding markers to Google Maps using JavaScript and PHP for beginners

### At the end of this guide, you'll learn how to create custom maps with ease and display location-based information on your website.

Google Maps is a powerful tool that allows developers to create interactive maps for their websites. One of the most useful features of Google Maps is the ability to add markers to the map, which can be used to display location-based information.

In order to add markers to a Google Map, you can use both JavaScript, PHP and a Database. The JavaScript code is used to create the map and add the markers, while the PHP code is used to retrieve location data from a database.

Follow the steps below to add Google Maps to your project and place custom markers into it :

## 1. Get a Google Maps API Key [OPTIONAL].
If you are going to work in a local environment (i.e. localhost), you can skip this step. Elsewhere, you need to get a Google Maps API key. You can create one from Google Cloud Console: https://console.cloud.google.com/. This step is further explained here : https://developers.google.com/maps/documentation/javascript/get-api-key .
## 2. Create a raw HTML file (or PHP as you wish).
To begin coding, let's create a nearly empty HTML file, and Since this file will contain only HTML and JavaScript code, you can also create it as a PHP file :

```html
<html>
<header></header>
<body></body>
</html>
```

## 2. Add the Google Maps API to our file.
The first thing we need to do is to add the Google Maps API to our project. For this, we have to place this line of code between header and /header.
```html
<html>
<header>
<script src="https://maps.googleapis.com/maps/api/js?callback=initMap&v=weekly" defer></script>  
</header>
<body></body>
</html>
```
## 3. Create a Google Maps Instance.
## 4. Retrieve markers positions from database using XMLhttpRequest and PHP
## 5. Place markers on the map.
## 6. Create a click event on each marker to show any eventual position information.
