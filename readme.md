# Université de Lomé | Map | QGIS 

[x] Manipulate Togo Map and work on University of Lome polygone
[] Load the Map in android studio 
[] Import different informations
    - building
    - road
    - location
[]  Build Algorithm A* to leave point A to point B

### How to display QGIS map in android application..?
To show a custom generated map from QGIS in an android application you can do the following:

- Export your QGIS map as a kml file

- Use the Google Maps Android API to display the map in your application. Here's the url to the API: 
https://developers.google.com/maps/documentation/android-sdk

- You need to import the KML layer using the Google Maps KML Importing utility, which is still in beta. The instructions for importing kml data can be found in this url: https://developers.google.com/maps/documentation/android-sdk/utility/kml#maps_android_utils_kml_add_file-kotlin

Please note that I haven't done this myself in an Android app but I have done it on my website using the Google Maps JavaScript API. The functionality of the Android API is somewhat more limited but the link referenced here has a table of supported features.
https://developers.google.com/maps/documentation/android-sdk
https://developers.google.com/maps/documentation/android-sdk/utility/kml#maps_android_utils_kml_add_file-kotlin
https://developers.google.com/maps/documentation/android-sdk/utility/setup