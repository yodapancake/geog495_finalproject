# Future Seattle Zoning Plans 2035

## Project Description 
For my **Geog495** final project I built a webgis application that shows you the future land use plans for the city of Seattle that are to be implemented by 2035, and the different colors represent different zoning designations. I also included a search bar at the top for people to look up different locations and drop a pin on that location. The goal of my project is to show people how Seattle might be changing over the next few years and to help people see what might be happening to locations they are familiar with. For example, some parks are being removed or reduced in order to make space for more housing. One issue with the data is that sometimes cities designate zones with multiple designations, and this causes the polygons to overlap in the data which causes certain areas to become weird colors not in the defined color key because I color the polygons with an amount of opacity. To compensate for this, I also included borders for each zone so that people can easily distsniguish area from one anaother. In addition, if you click on any zone a box with information on the zone will pop up on the map and tell you what the area is designated for.  

## Picturess of my Project
# Example of clicking
![image](img/clicking.PNG)
# Example of searching up a location
![image](img/geocoding_and_click.PNG)

## Link to my Application
[Future Seattle Zoning Plans 2035](https://yodapancake.github.io/geog495_finalproject/)

## Data Source
[Seattle GeoData](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::future-land-use-2035/about)

## Applied Libraries
* [MapBox](https://www.mapbox.com/)
* [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/api/)
* [Mapbox GL JS Geocoder](https://api.mapbox.com/mapbox-gl-js/plugins/mapbox-gl-geocoder/v4.7.2/mapbox-gl-geocoder.min.js)
* The project is also published on [Github](https://github.com/)
