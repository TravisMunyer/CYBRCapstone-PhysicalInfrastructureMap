

# CYBRCapstone-PhysicalInfrastructureMap
This project consists of a [QGIS](https://www.qgis.org/en/site/) project that represents the physical infrastructure of the internet. Currently, the mapping focuses on the state of michigan, but was designed in a way to allow extension to other regions.

# Interactive Map of Datacenters

```geojson
{
"type": "FeatureCollection",
"name": "DataCenters",
"crs": { "type": "name", "properties": { "name": "urn:ogc:def:crs:OGC:1.3:CRS84" } },
"features": [
{ "type": "Feature", "properties": { "id": 3, "Company": "Example Company", "Address": "Example Address", "Website": "Website Link", "PowerSys": "Power system used by the data center", "NetworkHw": "Networking Hardware used by the data center", "Cooling": "Cooling system employed by the data center", "PhysSec": "Physical security mechanism in place", "Name": "Name of data center", "Notes": "Notes", "PhoneNum": "123-456-7890", "City": "Detroit", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -83.081713988292762, 42.355686521672524 ] } },
{ "type": "Feature", "properties": { "id": 1, "Company": "Company Name", "Address": "Some Address", "Website": "Website link", "PowerSys": "Power System", "NetworkHw": "Network Hardware", "Cooling": "Cooling System", "PhysSec": "Physical Security", "Name": "Data Center Name", "Notes": "Some Notes", "PhoneNum": "123-456-7891", "City": "Grand Rapids", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -85.609998076504766, 42.941196805170449 ] } }
]
}
```

## Feature Attribute Descriptions
Each layer has a list of metadata called attributes. The attributes store the interesting information related to each physical line or data center, such as phone number or address. 

### Data Center Layer
id - Unique ID of the feature  
Company - Name of the company that owns the data center  
Address - The address of the data center  
Website - Link to the data centers website  
PowerSys - Description of the data centers power system  
NetworkHw - Descriptionn of the data centers networking hardware  
Cooling - Description of the data centers cooling system  
Name - The name of the data center  
Notes - Miscellaneous notes for the data center  
PhoneNum - The data centers phone number (at the time of feature creation)  
City - The city the data center is located in  
Region - The region or state in which the data center is located  

### Physical Lines Layer
id - Unique ID of the feature  
CableType - The material or type of the cable (e.g., fiber)  
Company - The company that owns the cable 

## Usage
1) First, install QGIS from [here](https://www.qgis.org/en/site/)
2) Next, pull down this github respository to a local folder
3) Open the .QGZ file (the project) in QGIS 
