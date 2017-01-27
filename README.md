## Indian Village Boundaries
 
 Please visit our [projects website for details](http://projects.datameet.org/indian_village_boundaries/).
 
 the folder for each state also has a text file which essentially maps 2001 census village codes to 2011 census village codes. All 2011-2001 village code maps were from http://egovstandards.gov.in/content/mapping-land-region-codes . Unfortunately this page no longer seems active. To match this data to the codes in the associated geojsons, you will need to concatenate state,district,tehsil and village codes for 2001 and use that as the 'join' field, so to speak, to match the two datasets.
