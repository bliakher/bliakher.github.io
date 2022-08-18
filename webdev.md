---
layout: page
title: Web Deveplopment
permalink: /webdev/
---

#### Public administration bulletin boards

<img width="250px" src="{{ site.baseurl }}/assets/uredni_mapa.jpg" /><img width="250px" src="{{ site.baseurl }}/assets/uredni_seznam.jpg" />
*\* App is in Czech*


**Web app for searching in public administration bulletin boards** [GitHub](https://github.com/bliakher/uredni_desky)

Web application made as part of my Bachelor thesis. It uses data form public administration bulletin boards published as open data in Czech [Open Data Catalogue](https://data.gov.cz/english/) to create user friendly visualization.

App enables to filter bulletin boards based on name and category and visualizes information from selected bulletin board. It also validates the data.

Application connects multiple sources of open data to visualize on the map and show statistics.


- Technology: TypeScript, React, SPARQL, Mapbox GL

- Deployed on GitHub Pages [here](https://bliakher.github.io/uredni_desky)
*\* Load of the app currently takes about 35s due to one of the main data sources being under construction and hence very limited performance.*


---

#### Web crawler

<img width="350px" src="{{ site.baseurl }}/assets/../../assets/webcrawler.png"><img width="200px" src="{{ site.baseurl }}/assets/../../assets/graph-data.png">


**Web crawler with a graph visualization and GraphQL API** [Github](https://github.com/bliakher/webcrawler)

Web crawler that lets user set up URLs to crawl with boundary RegEx. Server crawls URLs periodicaly. Crawled data can be displayed as a graph visualization in the web application or acquired from a GraphQL API. Application is deployed using Docker.

Team project for a university course. I was in charge of the frontend but also took part in the backend.

- Technology:
  - Frontend: TypeScript, React
  - Backend: TypeScript, Node.js, Express, Postgres
  - Docker

---

#### Election results map

<img width="350px" src="{{ site.baseurl }}/assets/../../assets/volebni_mapa.png">

**Utility to include a map with election results to articles** [GitHub](https://github.com/DataRozhlas/volby21-mapa/blob/mapa/js/script.js) [Used here](https://www.irozhlas.cz/volby/parlamentni-volby-2021-mapa-volili-sousede-sousedi-okrsky-volby_2110091850_pek)

Semester project made for Český Rozhlas (Czech national radio). It is a JavaScript utility that alows to embed an interactive map, that shows parliamentary election results, into articles.

- Technology: JavaScript, Mapbox GL

- Article with the map: https://www.irozhlas.cz/volby/parlamentni-volby-2021-mapa-volili-sousede-sousedi-okrsky-volby_2110091850_pek