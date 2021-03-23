# SpaceX: React JS based Starlink Trajectory Visualization 
**Deployed at: https://dev8751.d3qik0o8mb1cdd.amplifyapp.com/**

SpaceX is a React JS based starlink searching tool and satellites trajacetory visualization dashboard based on geo-location. Users can find nearby satellites by inputs such as longitude, latitude, altitude, and radius. This app also allows users to view selected starlinks' trajacetory on a D3-based world map. 

![Gif of SpaceX app](./src/assets/gif/spacexapp.gif)

## How to use
To start off, put some data into the input box to specify the geo-location of the satellites you are looking for. And then click on the `Find Nearby Satellites` button, and you will see a list of starlinks below. Select the some of the starlink boxes and click on the `Track on the map` button to get an animated view on the real-time satellites trajactories.

## Techniques Used
* React JS
* D3 (for rendering graphic information in world map)

## APIs and libraries used
* N2YO: https://www.n2yo.com/api/#above 
* Ant Design: https://3x.ant.design/docs/spec/introduce 
* Axios: https://github.com/axios/axios 

## Modules used to generate the word map
* topojson:  https://github.com/topojson/topojson-client 
* d3-geo: https://github.com/d3/d3-geo 
* d3-geo-projection: https://github.com/d3/d3-geo-projection 
* d3-selection: https://github.com/d3/d3-selection 
* d3-time-format https://github.com/d3/d3-time-format
* d3-scale https://github.com/d3/d3-scale 
* d3-scale-chromatic https://github.com/d3/d3-scale-chromatic 
