## Indian Village Boundaries
Indian Village boundaries sourced from different government websites which are freely available to all the Indians. Here we have digitized them, cleaned them, added appropriate attributes so it can be used by all the researchers, students etc

The boundaries are organized by state using state ISO code. All the village boundaries are available in geojson (WGS84, EPSG4326) format. The below table gives you the status of the data as we clean and upload. Data is not perfect there as many errors both in data and boundaries. You can contribute by sending the pull requests. Please use the census names when correcting the attributes and geojson for shapes.


### Structure
Each state has a folder with a short name, for example state of Gujarat will have GJ folder. It will contain a single geojson file gj.json and then a gj.md file containg the list of all supporting files.


### Attributes
Each boundary will have the following attributes

* NAME : Name of the Village/Town as per census
* TYPE: Village or Town
* SUB_DISTRICT: Sub District name as per census
* DISTRICT : District name as per census
* STATE: State or UT name as per census
* CENSUS_CODE_2001: Code as per 2001 census, its a concatination of State Code, District Code, Sub-District Code, Village Code 2001.
* CENSUS_CODE_2011: Code as per 2011 census


### License
All our work will be under [Open Data Commons Open Database License (ODbL)](http://opendatacommons.org/licenses/odbl/). This data is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  If you find issues we are more than happy to accept corrections.


### Information
- [Census of India, List of Villages/Towns, 2011](http://censusindia.gov.in/2011census/Listofvillagesandtowns.aspx) 

### Status


State | Short Code | Status 
------------ | ------------- 
Gujarat | GJ | Complete 

### Tools
- QGIS
- MapShaper
- GeoJSON.io
