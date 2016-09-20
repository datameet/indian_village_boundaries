## Indian Village Boundaries
Indian Village boundaries sourced from different government websites which are freely available to all the Indians. Here we have digitized them, cleaned them, added appropriate attributes so it can be used by all the researchers, students etc

The boundaries are organized by state using state ISO code. All the village boundaries are available in geojson (WGS84, EPSG4326) format. The below table gives you the status of the data as we clean and upload. Data is not perfect there as many errors both in data and boundaries. You can contribute by sending the pull requests. Please use the census names when correcting the attributes and geojson for shapes. Refer [CONTRIBUTING.md](CONTRIBUTING.md) for ways to contribute.


### Structure
Each state has a folder with a short name, for example state of Gujarat will have GJ folder. It will contain a single geojson file gj.json and then a gj.md file containg the list of all supporting files.


### Attributes
Each boundary will have the following attributes

* NAME : Name of the Village/Town as per census
* TYPE: Village or Town
* SUB_DIST: Sub District name as per census
* DISTRICT : District name as per census
* STATE: State or UT name as per census
* CEN_2001: Code as per 2001 census, its a concatination of State Code, District Code, Sub-District Code, Village Code 2001.
* CEN_2011: Code as per 2011 census, We are yet to populate this. 


### License
All our work will be under [Open Data Commons Open Database License (ODbL)](http://opendatacommons.org/licenses/odbl/). This data is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  If you find issues we are more than happy to accept corrections but please source them to an official source. Refer [CONTRIBUTING.md](CONTRIBUTING.md) for ways to contribute.


### Reference
This is the master list of all the references. These links are mostly goverment or under open license. Each state folder also has a note that can be reffered.

#### State Level
- [AP - Bhuvan - Andhra Pradesh State Village Boundaries](http://bhuvan.nrsc.gov.in/state/ap)
- [BR - Bihar Atlas -  iBHUGOAL-BiHar infrastrUcture mapping Geomatics Oriented Application modeL](http://gis.bih.nic.in/Map/BiharMap.aspx)
- [BR - Administrative Atlas-Bihar](http://www.censusindia.gov.in/2011census/maps/atlas/Bihar.html)
- [GJ - Gujarat Revenue Department Maps](https://revenuedepartment.gujarat.gov.in/village-map)
- [HR - Haryana Geo-portal](http://www.harsac.org/hsdi.htm)
- [KA - Bhuvan Panchayat - Digital Empowerment of Society for Panchayat level Planning and Governance](http://www.bhuvan-panchayat.nrsc.gov.in/#SISDP)
- [KA - Geographical Information System (GIS) based Road Information System (RIS) for PWP & IWTD Road Network](http://103.241.144.46:8888/webris/webris)
- [KA - Dharwad Village Boundaries](http://www.dharwad.nic.in/dwd_vill.htm)
- [KL - Delimitation Map 2010, Kerala, Maps of Villages and Towns](http://delimitation.lsgkerala.gov.in/map)
- [TS - Bhuvan - Telangana State Village Boundaries](http://bhuvan.nrsc.gov.in/state/ts)
- [MH - Maharashtra Remote Sensing Application Centre](http://www.mrsac.gov.in/en)


#### India Level
- [Maps by Census of India](http://www.censusindia.gov.in/2011-common/map.html)
- [Digital Library, Census of India](http://www.censusindia.gov.in/DigitalLibrary/MapsCategory.aspx)
- [Local Government Directory - List of all Local Goverments, Urban and Local, with codes and sometimes maps ](http://lgdirectory.gov.in/)
- [Bhuvan Panchayat - Digital Empowerment of Society for Panchayat level Planning and Governance](http://www.bhuvan-panchayat.nrsc.gov.in/#SISDP)
- [VILLAGE CENSUS CODE - 2001, ](http://pmgsy.nic.in/census-code.asp)
- [Census of India, List of Villages/Towns, 2011](http://censusindia.gov.in/2011census/Listofvillagesandtowns.aspx) 
- [GARV-GIS Mapping of UE Villages](https://ncog.gov.in/garvgis/admin/gisModule)
- [India WRIS](http://india-wris.nrsc.gov.in/GeoVisualization.html?UType=R2VuZXJhbA==?UName=)
- [India WRIS Web Map Services - Administrative - WMS](http://india-wris.nrsc.gov.in/arcgis/services/SubInfoSysLCC/Admin_subinfo_a/MapServer/WMSServer)
- [India WRIS Web Map Services - All](http://india-wris.nrsc.gov.in/WMSServicesApp.html?UType=R2VuZXJhbA==?UName=)
- [Layer: Villages Boundary (Census-2001) (ID: 1)](http://india-wris.nrsc.gov.in/ArcGIS/rest/services/SubInfoSysLCC/Rural/MapServer/1/query)
- [Village layer (Census 2001) WMS Service](http://india-wris.nrsc.gov.in/arcgis/services/SubInfoSysLCC/Rural/MapServer/WMSServer) provided by [WRIS India](http://india-wris.nrsc.gov.in/WMSServicesApp.html)
- [Administrative layer (Invluding Village) WMS Service](http://india-wris.nrsc.gov.in/arcgis/services/SubInfoSysLCC/Admin_subinfo_a/MapServer/WMSServer) provided by [WRIS India](http://india-wris.nrsc.gov.in/WMSServicesApp.html)
- [Mapping of Land Region Codes for Census 2011 and 2001 Data](https://egovstandards.gov.in/mapping_land_region_codification) 

### Status


State | Project Page | Status | Quick View 
------------ | ------------- | ------------- | ------------- 
[Gujarat](/gj) | GJ | Complete | [Quick View](https://github.com/datameet/indian_village_boundaries/blob/master/gj/gj.geojson)
[Kerala](/kl) | KL | Complete  | [Quick View](https://github.com/datameet/indian_village_boundaries/blob/master/kl/kl.geojson)
[Bihar](/br) | BR | Complete  | [Quick View](https://github.com/datameet/indian_village_boundaries/blob/master/br/br.geojson)
[Karnataka](/ka) | KA | Complete  | [Quick View](https://github.com/datameet/indian_village_boundaries/blob/master/ka/ka.geojson)

### Tools and Tutorials 
- [MapShaper](http://mapshaper.org/) is software for editing Shapefile, GeoJSON, TopoJSON and several other data formats, written in JavaScript.
- [geojson.io](http://geojson.io/) is a quick, simple tool for creating, viewing, and sharing maps. geojson.io is named after GeoJSON, an open source data format, and it supports GeoJSON in all ways - but also accepts KML, GPX, CSV, GTFS, TopoJSON, and other formats.
- [GeoJSONLint](http://geojsonlint.com/) is an app that validates your GeoJSON and shows your feature(s) on a map if everything checks out ok.
- [RawGit](https://rawgit.com/) - serves raw files directly from GitHub with proper Content-Type headers.
- [QGIS](http://www.qgis.org/en/site/) - A Free and Open Source Geographic Information System.
- [Mapping geoJSON files on GitHub](https://help.github.com/articles/mapping-geojson-files-on-github/) 
