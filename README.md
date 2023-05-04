

# CYBRCapstone-PhysicalInfrastructureMap
This project consists of a [QGIS](https://www.qgis.org/en/site/) project that represents the physical infrastructure of the internet. Currently, the mapping focuses on the state of michigan, but was designed in a way to allow extension to other regions.

# Interactive Map of Datacenters

```geojson
{
"type": "FeatureCollection",
"name": "DataCenters",
"crs": { "type": "name", "properties": { "name": "urn:ogc:def:crs:OGC:1.3:CRS84" } },
"features": [
{ "type": "Feature", "properties": { "id": 2021, "Company": "Digital Crossroad", "Address": "103 Lake Michigan street, Hammond, IN 46320", "Website": "https://digitalcrossroad.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Digital Crossroad(Indiana NAP)", "Notes": null, "PhoneNum": "1-219-533-2111", "City": "Hammond", "Region": "Indiana" }, "geometry": { "type": "Point", "coordinates": [ -87.520899078022921, 41.707003982024659 ] } },
{ "type": "Feature", "properties": { "id": null, "Company": " ", "Address": "", "Website": "", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "", "Notes": null, "PhoneNum": null, "City": "", "Region": "" }, "geometry": { "type": "Point", "coordinates": [ -87.641280347377602, 41.862711465167955 ] } },
{ "type": "Feature", "properties": { "id": 2018, "Company": " CoreSite", "Address": "1432 S Clinton Street, Chicago, IL 60607", "Website": "https://www.coresite.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "CoreSite Chicago CH2", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.641280347377602, 41.862711465167955 ] } },
{ "type": "Feature", "properties": { "id": 2019, "Company": "Deft", "Address": "350 E. Cermak Road, Chicago, IL 60616", "Website": "https://deft.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "ServerCentral Chicago DRT-CH1", "Notes": null, "PhoneNum": "1-312-829-1111", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.618019910531714, 41.853566898804551 ] } },
{ "type": "Feature", "properties": { "id": 2020, "Company": "Equinix", "Address": "350 East Cermak Road, Chicago, IL 60616", "Website": "https://www.equinix.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Equinix Chicago CH1, CH2, & CH4", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.618314539345207, 41.853835541447538 ] } },
{ "type": "Feature", "properties": { "id": 2022, "Company": "Lumen Technologies", "Address": "600 West Chicago Avenue, Chicago, IL 60610", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Level3 Chicago (600 West Chicago)", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.643535702371182, 41.897037552507413 ] } },
{ "type": "Feature", "properties": { "id": 2023, "Company": "TierPoint", "Address": "601 West Polk Street, Chicago, IL 60607", "Website": "https://www.tierpoint.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": " TierPoint Chicago Polk", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.643149637029367, 41.871789709996847 ] } },
{ "type": "Feature", "properties": { "id": 2024, "Company": "ServerFarm Realty", "Address": " 840 South Canal, Chicago, IL", "Website": "https://www.serverfarmllc.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Server Farm Realty 840 South Canal", "Notes": null, "PhoneNum": "", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.640061114294653, 41.870912134053803 ] } },
{ "type": "Feature", "properties": { "id": 2025, "Company": "DataBank", "Address": "800 E Business Center Dr, Mt Prospect, IL 60056\n", "Website": "https://www.databank.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "DataBank ORD3 Mount Prospect", "Notes": null, "PhoneNum": "214-720-2266", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.640061114294653, 41.870912134053803 ] } },
{ "type": "Feature", "properties": { "id": 2026, "Company": "Lumen Technologies", "Address": " 111 North Canal Street, Chicago, IL 60606", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Level3 Chicago (111 North Canal)", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.639161988432761, 41.883851375514944 ] } },
{ "type": "Feature", "properties": { "id": 2027, "Company": "Lumen Technologies", "Address": "101 North Wacker Drive, Chicago, IL 60606", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Level3 (was GX) Chicago", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.636601765639483, 41.883507220313732 ] } },
{ "type": "Feature", "properties": { "id": 2028, "Company": "XO", "Address": "140 South Dearborn Street, 2nd floor, Chicago, IL 60603", "Website": "https://www.verizon.com/business/xo/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "XO: 140 S Dearborn", "Notes": null, "PhoneNum": "800-421-3872", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.630551715348261, 41.879638183189563 ] } },
{ "type": "Feature", "properties": { "id": 2029, "Company": "Cogent Communications", "Address": "216 W Jackson Blvd, Chicago, IL", "Website": "https://www.cogentco.com/en/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Cogent: 216 W Jackson", "Notes": null, "PhoneNum": "877-875-4432", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.634483486066415, 41.878325758639704 ] } },
{ "type": "Feature", "properties": { "id": 2030, "Company": "QuadraNet", "Address": "427 S LaSalle St, Chicago, IL 60605", "Website": "https://quadranet.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "QuadraNet Chicago", "Notes": null, "PhoneNum": "888-578-2372", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.631499099377834, 41.876037461170483 ] } },
{ "type": "Feature", "properties": { "id": 2031, "Company": "CoreSite", "Address": "427 South LaSalle Street, Chicago, IL 60605", "Website": "https://www.coresite.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "CoreSite Chicago CH1", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.631494019570709, 41.875897513046766 ] } },
{ "type": "Feature", "properties": { "id": 2032, "Company": " Digital Realty Trust", "Address": "600 South Federal Street, Chicago, IL 60605", "Website": "https://www.digitalrealty.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": " 600 S Federal - Digital Realty", "Notes": null, "PhoneNum": "877-378-3282", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.629896420228533, 41.87430510876078 ] } },
{ "type": "Feature", "properties": { "id": 2033, "Company": "Cogent Communications", "Address": "600 South Federal Street, Chicago, IL 60605", "Website": "https://www.cogentco.com/en/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Cogent: 600 S Federal", "Notes": null, "PhoneNum": "877-875-4432", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.629891340421409, 41.874240806566682 ] } },
{ "type": "Feature", "properties": { "id": 2034, "Company": "Netrality Properties", "Address": " 717 South Wells Street, Chicago, IL", "Website": "https://netrality.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": " Netrality Chicago: 717 S Wells", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.633269412162505, 41.872811011657149 ] } },
{ "type": "Feature", "properties": { "id": 2025, "Company": "1547 Critical Systems Realty (fifteenfortyseven)", "Address": "725 S Wells St Chicago, IL 60607", "Website": "https://1547realty.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "725 S Wells - 1547 Critical Systems", "Notes": null, "PhoneNum": "1-732-441-1547", "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.633246553030418, 41.872591622306331 ] } },
{ "type": "Feature", "properties": { "id": 2026, "Company": "SteadFast", "Address": "725 S Wells St Chicago, IL 60607", "Website": "https://www.steadfast.net/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Steadfast Chicago 725 Wells", "Notes": null, "PhoneNum": null, "City": "Chicago", "Region": "Illinois" }, "geometry": { "type": "Point", "coordinates": [ -87.633246553030418, 41.872648361003733 ] } },
{ "type": "Feature", "properties": { "id": 1000, "Company": "Liquid Web ", "Address": "4428 S. Creyts Rd 48917 ", "Website": "https://www.liquidweb.com/", "PowerSys": "13,500 kVA utility power feeds, ASCO closed transition bypass switches, Backup diesel and electrical generators, and multiple service entrance feeds.", "NetworkHw": "Redundant fiber lines expandables to 1,840 Gigs per second, Mulitpels etherent linking datacenter 1 and 2, and Redundant lines to each rack.", "Cooling": "Multiple Liebert 20, 22, 30 and 45 ton upflow and downflow AC unit, and stand alone HVAC systems that don't allow for large scale failure.", "PhysSec": "24/7/365 manned facilities, CCTV security cameras covering onside, outside and all entrances of data centers, electronic perimeter access card system, remotely monitored by 3rd party security, and entrances secured by mantraps with interlocking doors", "Name": "Liquid Web DC1 & DC2", "Notes": "N/A", "PhoneNum": "1-800-580-4985", "City": "Lansing", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -84.643038298686392, 42.688064580469323 ] } },
{ "type": "Feature", "properties": { "id": 1001, "Company": "Liquid Web", "Address": "4210 Creyts, 48917 Lansing, Michigan, USA", "Website": "https://www.liquidweb.com/", "PowerSys": "13,500 kVA Utility Power Feeds. ASCO Closed Transition Bypass Switches, Backup diesel and electircal generators. Multiples service entrance feeds. ", "NetworkHw": "Redundant fiber lines expandables to 1,840 Gigs per second. Mulitpels etherent linking datacenter 1-3. Redundant lines to each rack.  ", "Cooling": "Multiple Liebert 20, 22, 30 and 45 ton upflow and downflow AC unit. Stand alone HVAC systems that don't allow for large scale failure. ", "PhysSec": "24/7/365 Manned Facilities. CCTV security cameras covering inside, outside and all entrances. Electronic perimeter access card system. Sites remotely monited by 3rd party security company. Entrances secured by mantraps with interlocking doors.", "Name": "Liquid Web DC3", "Notes": "N/A", "PhoneNum": "1-800-580-4985", "City": "Lansing", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -84.642810374888242, 42.690016557026567 ] } },
{ "type": "Feature", "properties": { "id": 1002, "Company": "Global Dataplex", "Address": "4300 W. Saginaw, 48917 Lansing, Michigan, USA", "Website": "https://www.datacentermap.com/usa/michigan/lansing/global-dataplex.html", "PowerSys": "N/A", "NetworkHw": "Rack cabinets. Suites. Fiber optic services.", "Cooling": "Redundant HVAC systems. Individual airflow units per area.", "PhysSec": "24/7 surveilance. Card access controlled facility doors.", "Name": "Global Dataplex Lansing", "Notes": "N/A", "PhoneNum": "(517) 803-4281", "City": "Lansing", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -84.611454198599205, 42.741910289383902 ] } },
{ "type": "Feature", "properties": { "id": 1003, "Company": "Lumen Technologies", "Address": "1206 May Street, Lansing, MI 48906", "Website": "https://baxtel.com/data-center/lumen-lansing", "PowerSys": "Power densities up to 20kW per cabinet. Backed by a 100% power uptime SLA.", "NetworkHw": "NULLTier 1 ISP and international carrier offering multiprotocol label switching. Virtual private network (VPN). Ethernet virtual private line (EVPL). Ethernet private line (EPL) and private line services.", "Cooling": "Redundant HVAC system.", "PhysSec": "Multi-level physical/logical security and challenge points.", "Name": "Lumen Lansing", "Notes": "N/A", "PhoneNum": "N/A", "City": "Lansing", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -84.534412079273366, 42.741983092679703 ] } },
{ "type": "Feature", "properties": { "id": 1200, "Company": "Online Tech", "Address": "5225 Exchange Drive 48507 Flint Michigan", "Website": "https://www.datacentermap.com/usa/michigan/flint/onlinetech-exchange-drive.html", "PowerSys": "Dual utility power feeds into the data center from diverse routes.Dual synchronized 1,300 KVA Detroit Diesel generators. Pooled UPS system provides over 1,600 KVA of conditioned power to the data center floor. High availability power runs diverse power paths to each server.  ", "NetworkHw": "Multiple Internet Service Providers (ISPs) with diverse fiber feeds into the data center. Redundant Gigabit network provides capacity on-demand. Private Gigabit connection for data replication to Online Tech's Ann Arbor data center 53 miles away. High availability dual Cisco-powered network provides redundant network connections to the server.", "Cooling": "400 tons of cooling capacity with full N+1 redundancy.", "PhysSec": "All critical equipment is N+1 with full redundancy across core network and security systems. Dry pipe fire suppression system with state-of-the-art laser particle counting technology. Multiple levels of physical security with two-factor authentication to gain floor access. Digital video surveillance with 24x7 recording activity.", "Name": "Mid-Michigan Data Center", "Notes": "N/A", "PhoneNum": "N/A", "City": "Flint", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -83.77966633960385, 42.968692195681015 ] } },
{ "type": "Feature", "properties": { "id": 1400, "Company": "US Signal", "Address": "21648 Melrose Avenue, Southfield, MI, USA", "Website": "https://ussignal.com/data-centers/southfield-michigan", "PowerSys": "Full back-up power systems for each feed, including onsite diesel power generation and AC UPS. Backup diesel and electrical generators. Two 2-megawatt substation feeds.", "NetworkHw": "N/A", "Cooling": "N+1 cooling system design using free cooling technologies. Photoelectric photo sensors for environmental monitoring. 100 tons of cooling via Liebert DSE cooling systems. ", "PhysSec": "24/7/365 Manned Facilities .", "Name": "US Signal Southfield", "Notes": "N/A", "PhoneNum": "N/A", "City": "Detroit", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -83.256978935816093, 42.447321397347501 ] } },
{ "type": "Feature", "properties": { "id": 1401, "Company": "365 Data Centers", "Address": "24660 Lahser Road Southfield, MI 48033", "Website": "https://365datacenters.com/", "PowerSys": "Primary and Redundant Circuits. Single and 3-Phase AC.", "NetworkHw": "N/A", "Cooling": "120 and 208 Volt ACs.", "PhysSec": "24/7 Staffed Facility. Hybrid DVR camera systems. Biometric scanners and card reader at main entrances. Mantrap entries. Locking cages and cabinets.", "Name": "365 Data Centers", "Notes": "N/A", "PhoneNum": "866-365-6246", "City": "Detroit", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -83.262613118614013, 42.447721430996353 ] } },
{ "type": "Feature", "properties": { "id": 1402, "Company": "123NET", "Address": "24700 Northwestern Hwy.Southfield MI 48075 Michigan", "Website": "https://www.123.net/", "PowerSys": "AC/DC power options.", "NetworkHw": "N/A", "Cooling": "Hot aisle-cold aisle containment systems. Diesel generators.", "PhysSec": "Disaster Recovery. 24/7 Staffed Facility.", "Name": "123NET Data Center", "Notes": "N/A", "PhoneNum": "888-440-0123", "City": "Detroit", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -83.237949058199476, 42.471639176972765 ] } },
{ "type": "Feature", "properties": { "id": 1403, "Company": "Sungard", "Address": "37720 Amrhein Rd, Livonia, MI", "Website": "https://www.sungardas.com/en-us/", "PowerSys": "Full power redundancy. Dual UPS system.", "NetworkHw": "N/A", "Cooling": "Hot and cold aisle cabinet design.", "PhysSec": "24/7 staffed facility.Biometric scan. Multi-Level key card.", "Name": "SunGard Detriot", "Notes": "N/A", "PhoneNum": "1-800-441-1181", "City": "Detroit", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -83.415111533508878, 42.374959862215555 ] } },
{ "type": "Feature", "properties": { "id": 1600, "Company": "US Signal", "Address": "400 76th St. SW Byron Center, MI 49315", "Website": "https://baxtel.com/data-center/us-signal-grand-rapids-south", "PowerSys": "(2) 800a 480V 3 phase. (2) 500kW diesel generators with 24 run time at full load. 675kVa UPS with battery backup. DC power with battery backup available. Power Capacity and power quality monitored by US Singal TOC.  ", "NetworkHw": "N/A", "Cooling": "240 tons of cooling, via Liebert DX and DS units. Photoelectric fire sensors throughout facility. Temp and humidity monityed by US Signal TOC.", "PhysSec": "RFID access readers on all doors. Digital video surveillance (recordings kept at least 90 days). Steel mesh for security.", "Name": "US Signal Grand Rapids South", "Notes": "N/A", "PhoneNum": "N/A", "City": "Grand Rapids", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -85.672688742234826, 42.825451591904645 ] } },
{ "type": "Feature", "properties": { "id": 1601, "Company": "US Signal", "Address": "4765 Barden Ct. SE Kentwood, MI 49512", "Website": "https://baxtel.com/data-center/us-signal-grand-rapids-east", "PowerSys": "(1) 2000a 480V 3 phase, (1) 800a 480V 3 phase. (2) 2.5 MW Cummins diesel generators, (1) Cummins 450 kW diesel generator. (2) APC Symmetra MW 1400 kVa UPS w/ battery backup.  DC power with battery backup. Power capacity/quality monited by US Signal TOC. ", "NetworkHw": "N/A", "Cooling": "Ecaro 25 plus dry fire suppresion. Photelectri photo sensors. 24\" raised floor used for cooling plenum. Overhead mechanical hot air returns. Temp and humidity monitored by US Signal TOC.", "PhysSec": "Biometric access control on entry points. Video Surveillance (recordings kept for at least 90 days). Concrete building w/ steel reinforcement. Steel mesh in all walls.", "Name": "US Signal Grand Rapids East", "Notes": "N/A", "PhoneNum": "N/A", "City": "Grand Rapids", "Region": "Michigan" }, "geometry": { "type": "Point", "coordinates": [ -85.564447520800599, 42.876550616979003 ] } },
{ "type": "Feature", "properties": { "id": 2000, "Company": "Expedient Data Centers", "Address": "15166 Neo Parkway, Cleveland, OH 44128\n", "Website": "https://www.expedient.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Expedient Garfield Heights 1", "Notes": null, "PhoneNum": "877-570-7827", "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.573980967376926, 41.428172315202865 ] } },
{ "type": "Feature", "properties": { "id": 2001, "Company": "Expedient Data Centers", "Address": "15248 Neo Parkway, Cleveland, OH 44128", "Website": "https://www.expedient.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Expedient Garfield Heights 2", "Notes": null, "PhoneNum": "877-570-7827", "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.573888929071416, 41.429238112362938 ] } },
{ "type": "Feature", "properties": { "id": 2002, "Company": "Lumen Technologies", "Address": "15467 Neo Parkway, Garfield Heights, OH 44128\n", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": " Level3 Garfield Heights", "Notes": null, "PhoneNum": null, "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.573193528540969, 41.430495577160158 ] } },
{ "type": "Feature", "properties": { "id": 2003, "Company": "Lumen Technologies", "Address": " \n4000 Chester Avenue, Cleveland, OH 44145\n", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Lumen Cleveland (4000 Chester)", "Notes": null, "PhoneNum": null, "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.657812523971216, 41.505056450104085 ] } },
{ "type": "Feature", "properties": { "id": 2004, "Company": "Lumen Technologies", "Address": "1228 Euclid Avenue, Cleveland, OH 44115\n", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": " Level3 Cleveland (1228 Euclid)", "Notes": null, "PhoneNum": null, "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.683794330417086, 41.500293953630653 ] } },
{ "type": "Feature", "properties": { "id": 2005, "Company": "DataBank", "Address": "1255 Euclid Avenue, Cleveland, OH 44115 (Suite 200 on Second Floor)\n", "Website": "https://www.databank.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "DataBank Cleveland CLE1", "Notes": null, "PhoneNum": "800-840-7533", "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.683507989022189, 41.501082840732558 ] } },
{ "type": "Feature", "properties": { "id": 2006, "Company": "Lumen Technology", "Address": "1621 Euclid Avenue, Cleveland, OH 44115 (Suite 518)\n", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": " Level3 Cleveland (1621 Euclid)", "Notes": null, "PhoneNum": null, "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.680429819027083, 41.501657267041828 ] } },
{ "type": "Feature", "properties": { "id": 2007, "Company": "Fusion Connect", "Address": "1621 Euclid Ave, Cleveland, OH 44115 (Suite 730)\n", "Website": "https://www.fusionconnect.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Fusion Connect Cleveland", "Notes": null, "PhoneNum": "+1 844-833-9653", "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.680450271983872, 41.501576847665262 ] } },
{ "type": "Feature", "properties": { "id": 2008, "Company": "DataBank", "Address": "1525 Rockwell, Cleveland, OH (Suite 200)\n", "Website": "https://www.databank.com/data-centers/cleveland/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "DataBank Cleveland", "Notes": null, "PhoneNum": "800-840-7533", "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.684170153497902, 41.506026569708048 ] } },
{ "type": "Feature", "properties": { "id": 2009, "Company": "SecureData 365", "Address": "1525 Rockwell Ave, Cleveland, OH 44114\n", "Website": "https://www.clevelandohio.gov/node/5595", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "SecureData 365 Cleveland", "Notes": null, "PhoneNum": null, "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.683955397451712, 41.506168251186963 ] } },
{ "type": "Feature", "properties": { "id": 2010, "Company": "H5 Data Centers", "Address": "1625 Rockwell Street, Cleveland, OH, 44114\n", "Website": "https://h5datacenters.com/cleveland-data-center.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "H5 Cleveland Technology Center (CTC)", "Notes": null, "PhoneNum": " +1 (303) 714-7800", "City": "Cleveland", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -81.682922523134437, 41.506654560931864 ] } },
{ "type": "Feature", "properties": { "id": 2011, "Company": "Telesystem", "Address": "2700 Oregon Rd, Northwood, OH 43619\n", "Website": "https://www.telesystem.us/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Telesystem Toledo", "Notes": null, "PhoneNum": null, "City": "Toledo", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -83.540848663900405, 41.605844622497749 ] } },
{ "type": "Feature", "properties": { "id": 2012, "Company": "Lumen Technologies", "Address": "639 Oliver St, Toledo, OH 43609\n", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Level3 Toledo", "Notes": null, "PhoneNum": null, "City": "Toledo", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -83.547214646697654, 41.638789438022435 ] } },
{ "type": "Feature", "properties": { "id": 2013, "Company": "CISP", "Address": "3035 Moffat Rd, Toledo, OH 43615\n", "Website": "http://www.cisp.com/our-data-center/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "CISP Yocolo", "Notes": null, "PhoneNum": "419-724-5300", "City": "Toledo", "Region": "Ohio" }, "geometry": { "type": "Point", "coordinates": [ -83.690768837083908, 41.673653836619437 ] } },
{ "type": "Feature", "properties": { "id": 2014, "Company": "CyrusOne", "Address": "316 E. Monroe St South Bend, IN 46601\n", "Website": "https://cyrusone.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "CyrusOne Indiana - Monroe", "Notes": null, "PhoneNum": "+1 855-564-3198", "City": "South Bend", "Region": "Indiana" }, "geometry": { "type": "Point", "coordinates": [ -86.246802968458937, 41.671159783242018 ] } },
{ "type": "Feature", "properties": { "id": 2015, "Company": "US Signal", "Address": "506 W. South St. South Bend, IN 46601\n", "Website": "https://ussignal.com/data-centers/south-bend", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "US Signal South Bend", "Notes": null, "PhoneNum": null, "City": "South Bend", "Region": "Indiana" }, "geometry": { "type": "Point", "coordinates": [ -86.256042591683396, 41.669358886767107 ] } },
{ "type": "Feature", "properties": { "id": 2016, "Company": "Lumen Technologies", "Address": "1140 Franklin Street, South Bend, IN 46601\n", "Website": "https://www.lumen.com/en-us/home.html", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "Level3 South Bend", "Notes": null, "PhoneNum": null, "City": "South Bend", "Region": "Indiana" }, "geometry": { "type": "Point", "coordinates": [ -86.255183567498705, 41.662865310458649 ] } },
{ "type": "Feature", "properties": { "id": 2017, "Company": "CyrusOne", "Address": "3919 Crescent Circle South Bend, IN 46628\n", "Website": "https://cyrusone.com/", "PowerSys": null, "NetworkHw": null, "Cooling": null, "PhysSec": null, "Name": "CyrusOne Indiana - Blackthorn", "Notes": null, "PhoneNum": "+1 855-564-3198", "City": "South Bend", "Region": "Indiana" }, "geometry": { "type": "Point", "coordinates": [ -86.331695018078605, 41.72769608662842 ] } }
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
PhysSec - Physical security mechanisms employed by the data center  
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
