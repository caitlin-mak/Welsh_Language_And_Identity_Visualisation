# Welsh Language and Identity - Interactive D3 Visualisation

## Overview

This project is an interactive data visualisation built with [D3.js](https://d3js.org/) and HTML. It uses two choropleth maps to explore Welsh language proficiency and national identity across Wales, based on data from the 2021 Census.

Users can interact with the visualisation in the following ways:
- **Hover over** local authorities to view detailed statistics, including Welsh language ability, identity, and population size.
- **Use the map controls** to toggle between:
    - **Welsh Language Map:** Shows the percentage of people who can or cannot speak Welsh.
    - **Welsh Identity Map:** Switch between percentages identifying as Welsh, Welsh-British, or British.


## Live Demo 

[**Click here to view the visualisation**](https://caitlin-mak.github.io/Welsh_Language_And_Identity_Visualisation/)

## Tools
- **HTML / CSS / JavaScript**
- **[D3.js](https://d3js.org/)** for data-driven visualisation
- **Git & GitHub** for version control and hosting

## Project Structure

```none
├── index.html              # Main HTML file containing D3 visualisation logic
├── stylesheet.css          # CSS styling
├── LAWelshLang.csv         # Dataset used in visualisation
├── walesLocalAuth.geojson  # geoJSON data to map Welsh local authorities
└── README.md               # Project documentation
```