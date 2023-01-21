# IssueTrac Project

Welcome to the Issue Trac project. 

Issue Trac a simple GIS based issue reporting and work management system. The general premise for the applications is to 
provide a web based map which allows a visitor to _"click"_ a location and report an issue or problem. These spatially 
enable locations offers an ability to present the reporting person(s) geo-specific, nomenclature work types and 
categories. All reported issue are associated with a maintaining agency at the state, county and 
city levels. 


## Project Components 

The project is organized into different repositories with each encompassing a specific area of the applications' 
development. Brief descriptions and links to those project repositories are found below:

- [nasumilu/issue-trac-databasse (a.k.a IssueTrac Database)](https://github.com/nasumilu/issue-trac-databsase) project 
  contains all things database which is associated with the application. This includes entity relationship diagrams 
  (ERD), set-up sql and scripts, and any initial application data.

- [nasumilu/feature-server](https://github.com/nasumilu/feature-server) is an application which provides discrete 
  feature information is a standard way. The application will adhere to the minimum standards outlined by the 
  Open Geospatial Consortium (OGC) [Feature - OGC API standard](https://docs.opengeospatial.org/is/17-069r4/17-069r4.html).

- [nasumilu/issue-trac (a.k.a IssueTrac API)](https://github.com/nasumilu/issue-trac-api) is the actual issue 
  tracking/work management applications that will provide the necessary application protocol interface (API) to create, 
  read, and update issues by providing an interface between application, database(s), and other **backend** web services.

- [nasumilu/issue-trac-web (a.k.a IssueTrac Web)](https://github.com/nasumilu/issue-trac-web) is a single page 
  application (SPA) which gives a face to the IssueTrac API. 

![IssueTrac Component Diagram](./dist/images/component.png)