## Welcome 

This page provides some background into the work I was a part of during my casual contract at Statistic Canada's Statistical Geomatic Centre as a GIS Web Developer. 

My role was to support the front-end development of the Canadian Statistical Geospatial Explorer (CSGE) and it's API. I mainly focused on the [Geo-Explorer](https://github.com/SGC-CGS/geo-explorer), [Geo-Explorer API](https://github.com/SGC-CGS/geo-explorer-api), and [bundler](https://github.com/SGC-CGS/bundler). However, I was also involved in some of the other repositories for code reviews, peer-coding, and feedback. 


## Table of Contents
- Software / Tools
  - IIS Express
  - Visual Studio Code IDE
- Languages / APIs / Libraries
  - JavaScript / HTML / CSS
  - ArcGIS REST JS and API for JavaScript
  - D3JS
- Work Environment
  - Agile
- The Canadian Statistical Geospatial Explorer
  - Widgets
    - Select Data
    - Styler
    - Charts
    - Bookmarks
    - Export
    - Map and Chart Hover
    - Use of web storage 
- Documentation 

## Software
#### IIS Manager

Microsoft Window's Internet Information Services (IIS) enables server requested pages to reach your Windows system. In the case of the CSGE, ASP.NET server technology is required for building the full stack GIS web application with JavaScript / HTML / CSS. 

#### Visual Studio Code IDE

[Visual Studio Code](https://code.visualstudio.com/) is an integrated development environment (IDE) for developing software. IDEs are powerful because they offer complex developer tools (write code, compile code, and debug) in a single GUI. 

## Languages / APIs / Libraries

#### JavaScript / HTML / CSS

In web development, [HTML](https://html.com/) provides the structure for web pages, and is enhanced by [JavaScript](https://www.javascript.com/) and [CSS](https://en.wikipedia.org/wiki/CSS). JavaScript allows for more interactive web pages, and CSS helps with styling. 

#### ArcGIS REST JS and API for JavaScript

Developed by **[Esri](https://www.esri.com/en-us/home)**, the [ArcGIS JavaScript](https://developers.arcgis.com/javascript/latest/) and[ ArcGIS REST JS](https://developers.arcgis.com/arcgis-rest-js/) web APIs allow developers to build 2D and 3D browser-based mapping applications to provide users with an interactive experience. Additionally, the ArcGIS REST JS API utilizes [ArcGIS Enterprise](https://www.esri.com/en-us/arcgis/products/arcgis-enterprise/overview) for mapping, analytics, data hosting, and content management. In the case of the CSGE, geographic content and services are hosted within the government's infrastructure. 

#### D3JS

[D3JS](https://d3js.org/) is a JavaScript library for data visualization. In the CSGE, D3JS is used for developing interactive bar charts, pie charts, line charts, and scatter plots. 

## Work Environment 

#### Agile

[Agile](https://en.wikipedia.org/wiki/Agile_software_development) work environment's offer flexibility for employees and customers. As customer needs evolve, the development of the product also evolves in an iterative and incremental way. In this environment, the scrum framework is to organize teams to focus on certain features within a period of time (i.e., sprints). As part of scrum, there are daily scrum and occasional sprint planning meetings. Daily scrum meetings go over how things are progressing and if something needs addressing. The sprint planning meetings discuss tasks to take on for the period of the sprint and by the end of the sprint, the team goes into sprint review to provide feedback, ideas for improvement, and go over the work completed. 

## The Canadian Statistical Geospatial Explorer

The main goal of the [CSGE](https://github.com/SGC-CGS) is to allow subject matter experts to analyze and grab data from a map-based UI. The development of the CSGE is split into various parts: 
- [Geo-Explorer API](https://github.com/SGC-CGS/geo-explorer-api)
  - Provides the common code for geo-explorer sites
- [Geo-Explorer]((https://github.com/SGC-CGS/geo-explorer))
  -  The heaviest geo-explorer site rich with features, unlike the [Geo-Explorer Lite](https://github.com/SGC-CGS/geo-explorer-lite)
- [Geo-Explorer Proxy](https://github.com/SGC-CGS/geo-explorer-proxy)
- [Geo-Geocoder using Pelias](https://github.com/SGC-CGS/geo-geocoding)
  - Take a text description and return an address
- [Bundler built with Rollup](https://github.com/SGC-CGS/bundler)
  - Provide cross-browser compatibility for geo-explorer sites

#### Features

**Select Data**

**Styler**

**Charts**

**Bookmarks**

**Export**

**Map and Chart Hover**

**Use of Web Storage**

## Documentation

Word documents

JSDocs


#### Credits
- Statistics Canada
- SGC
- Bruno St-Aubin

