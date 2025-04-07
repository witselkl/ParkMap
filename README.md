# Geog 777
Project 2

Problem Statement
A park has hired you to develop a mobile friendly application to improve the visitor experience. The park would like the application to be useful to visitors before they arrive to the park and provide information while the visitors are inside the park. The application should be centered on an interactive map that includes data related to park features. At a min, visitors should have the ability to explore park features through the app functionality. The park would like you to use user centered design to create the application around specific themes. For example, the application could be focused on themes like safety, accessibility, or recreation. The rest of the instructions will use these perspectives as an example. Finally, the park would like the visitors to be able to contribute to the database. 

Theme selected: Hiking and Weather
Park: Olympic National Park


Goal: Create a mobile friendly map application for park with a user center design.
•	Pick any park
•	Create a user persona and/or stories to frame the functionality of your application.
•	Pick a theme to drive the functionality – safety, access, recreation.
Requirements
1.	Min of 5 data layers (collected or made up) must be used in the application.
a.	A basemap can only count for 1 of the 5 data layers so long as it is a basemap you’ve created.
b.	One of the 5 data layers will be user submitted data
2.	All data must be stored in a database of your choosing
a.	You must create an ER diagram and logical schema
3.	A min of 4 functions must be included in the application
a.	One function should be user submitted (remember to include user validation in the application)
b.	These functions could be things such as
i.	search, 
ii.	query,
iii.	report, 
iv.	incorporate device
v.	create
c.	Note: the operator the primitives zoom, pan and retrieve do not count as functions.
Deliverable
1.	Mobile App
2.	Database
3.	ER Diagram
4.	Database schema
5.	5 min video demonstration
6.	Written report, 
a.	that includes information about the park you selected, 
b.	description of the user center design, 
c.	description of the back end of your app.


Using the national park data, I used ArcGIS REST service URL to an ArcGIS Maps SDK for JavaScript (formerly ArcGIS API for JavaScript) map to add feature layers to my site. Here are the data types and REST:

1) Park Boundaries: https://mapservices.nps.gov/arcgis/rest/services/Wilderness/Wilderness/MapServer

2) Buildings:  https://mapservices.nps.gov/arcgis/rest/services/NationalDatasets/NPS_Public_Buildings_Geographic/MapServer

3) Parking: https://mapservices.nps.gov/arcgis/rest/services/NationalDatasets/NPS_Public_ParkingLots_Geographic/MapServer

4) Trails: https://services2.arcgis.com/FiaPA4ga0iQKduv3/arcgis/rest/services/National_Park_Service_Trails/FeatureServer

5) EV: https://services9.arcgis.com/RHVPKKiFTONKtxq3/arcgis/rest/services/Alternate_Fuel/FeatureServer

6) Airports: https://services.arcgis.com/HRPe58bUyBqyyiCt/arcgis/rest/services/US_AirportsGeog576/FeatureServer

7) Hotspring: https://services.arcgis.com/HRPe58bUyBqyyiCt/arcgis/rest/services/Washington_State_Hot_Spring/FeatureServer

Ferries:

Weather: Open weather API

Campsites:


