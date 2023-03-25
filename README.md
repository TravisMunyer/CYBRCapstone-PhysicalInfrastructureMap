# CYBRCapstone-PhysicalInfrastructureMap
This project consists of a [QGIS](https://www.qgis.org/en/site/) project that represents the physical infrastructure of the internet. Currently, the mapping focuses on the state of michigan, but was designed in a way to allow extension to other regions.

## Feature Attribute Descriptions
Each layer has a list of metadata called attributes. The attributes store the interesting information related to each physical line or data center, such as phone number or address. 

### Data Center Layers - Seperated by city
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

### Physical Line Layers - Seperated by company ownership 
id - Unique ID of the feature  
CableType - The material or type of the cable (e.g., fiber)  
Company - The company that owns the cable 

## Usage
1) First, install QGIS from [here](https://www.qgis.org/en/site/)
2) Next, pull down this github respository to a local folder
3) Open the .QGZ file (the project) in QGIS 
