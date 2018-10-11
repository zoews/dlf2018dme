The following data files should be contained in this folder:

# CSV
There are two csv files. Both of these files were created by Jose Cardona, student researcher at  UCLA, in consultation with Professor Genevieve Carpio (UCLA) and Andy Rutkowski (UCLA at the time of creation and now at USC) during the spring/summer of 2017. Addresses were hand coded into a Google spreadsheet, geocoded using a script (see below), and then verified using current Google Maps in order to make sure that locations were accurate.

* 39GreenBook.csv - Los Angeles locations from the 1939 Greenbook. 
* 47GreenBook.csv - Los Angeles locations from the 1939 Greenbook

# geojson
There are two geojson files. 

The HOLC_LosAngeles geojson contains boundary information that corresponds to the Homeowner's Loan Corporation maps from 1939. The file contains boundaries with associated data letting you know what the grade is for each boundary. The file was downloaded from the American Panorama Redlining Project which has processed this data. 

The la-county-neighborhoods-v6 geojson was created by the Los Angeles Times as part of the Neighborhood mapping project. It is the 6th iteration of the file and includes 318 unique neighborhood boundaries with names.

* HOLC_LosAngeles.geojson - downloaded originally from American Panorama project
* [American Panorama Redlining website](https://dsl.richmond.edu/panorama/redlining/)
* la-county-neighborhoods-v6.geojson
* [Mapping LA Boundaries LA Times API](http://boundaries.latimes.com/sets/)

# .GS 

This .gs file is a google script that lets you geocode addressed in Google Sheets. 

* geocodingmacroforgooglesheets.gs

The orginal script and instructions can be found here:

* [Geocoding Script](https://github.com/nuket/google-sheets-geocoding-macro)
