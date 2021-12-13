 # Future land use of Seattle for 2035

## Project description
For my GEOG 495 final project I built a webGIS application that shows users the future land use plans of Seattle that are planned for 2035 visualized as polygons with different colors for different governmental zoning designations. Some areas are colored incorrectly on the fill layer because some areas have multiple designations, so it is best to rely on the layer with colored borders for zones in determining a zoning designation of an area. The zoning designations for respective areas can be determined by looking at the color key on the left side of the screen.
Project goal
The goal of my project is to show people how Seattle is changing over the next few years and to help them visualize those change more clearly. But I also wanted to allow people to see for themselves what might be happening to locations they are fond of/familiar with. For example, some parks are being removed or reduced in size to make space for more housing. I also thought it would be interesting to show people to see how Seattle is divided up in terms of governmental land designations. For me, it was interesting and surprising to see how much land in Seattle is dedicated for neighborhood residential areas and other types of housing.
Functionality
There are a few ways to determine an area’s zoning designation. One way is to hover your mouse cursor over areas of interest and check the box in the top left for an answer in a textbox. Another is to click on a zone and look for the textbox that pops up above where your cursor just clicked. To remove this textbox either click the ‘X’ in the top right or click on an area of the map where there is no data (i.e., no colored polygon). There are also a couple methods for identifying designation by color. One way is to look at an area’s color and match that to the color key on the left. However, this is not a sure-fire way to do this because colors are plotted with a degree of opacity and don’t match the color key’s colors. Although It’s close to the actual color and most people should be able to determine single designation zones through the fill color matching method relatively easily.  The bigger issue is when areas have multiple designations. With these zones the fill color becomes a blended wrong color because in these instances there are multiple different colored layers with opacity stacked on top of each other. To deal with this there is also a layer that shows colored and dashed borders for each area and the colors are the same as the color key’s colors for each respective zoning designation. This is useful for seeing the main zoning designation of areas and the sub designations for these areas. To see what zoning designation a location of interest falls under simply search the address in the search bar in the top right corner and click on one of the that search results comes up under search bar. Selecting an address like this will drop a pin of this location on the top layer of the map and move your screen view to that location. To remove this pin simply click the ‘X’ on the far-right side of the search bar in the top left. One note is that you can only drop pins on locations in Seattle and the search bar will only give results for addresses in Seattle.
## Picturess of my Project
### Overview
![image](img/overview.PNG)
### Normal zone bordering example
![image](img/normal_bordering.PNG)
### Multiple zone designation example
![image](img/multiple_designations.PNG)
### Search bar
![image](img/search_bar.PNG)
### Example of clicking
![image](img/clicking.PNG)
### Example of searching up a location
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
