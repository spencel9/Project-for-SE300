
<h2>Safe Housing </h2>

**Welcome!**
**This project allows the user to search for housing and see the sexual offenders within the area.**

With an interactive map, users may search through Volusia County to view housing, housing prices, and the sexual offenders in the 
surrounding area. 
This map allows users to either type in a known address or click an area to see what housing is available.
A pin or marker on the map will indicate their last known location. When the user further inspects the pin, they will be propted with 
their last known address, status, crime, and name. 



<h3>Getting Started</h3>
Downloads needed: 
Python 3 (any Python 3 version)

Python Libraries needed: 

import folium

from geopy.geocoders import Nominatim

from geopy.distance import geodesic

from folium.plugins import Geocoder

from geopy.distance import great_circle

import os

import fnmatch

import pandas as pd

<h3>Using the Map!</h3>
To search for a known address use the search bar located in the upper right corner of the screen.  If you arent sure of the full address, 
we will help you find what you are looking for through our autocomplete function.  
If you don't have an address, you can pan and zoom around the map to find a desired area.  Go ahead and click on this desired area and we 
will show you living options in the area.  

**Video of map usage will be here**
<h3>Pins/Map Markers</h3>
Pins will indicate a location on the map and will be color coded for sexual offender and their offenses.   
Users can view more information about the sexual offender by clicking on the pin.  

<h3>Databases</h3>
While APIs were originally going to be used for data, we found that csv files were more affordable. 
Therefore, csv files were made for this program and are maintained by the programers.  
The sexual offender csv file was made using information found at <em>Volusia County Sexual Offender Registry</em>.   
The <em>Zillow.com</em> and <em>Apartments.com</em> csv files were used to make a comprised data of available housing (address,price, and additional data).  
When changes are made to any csv files, the "date of last updated" is also changed.  















