# COVID-19 Cases and Rates in the United States (2020)

## Project Overview

This project presents two interactive thematic web maps visualizing COVID-19 data across U.S. counties for the year 2020.

The first map displays a choropleth of COVID-19 case rates (cases per 1,000 residents), while the second map uses proportional symbols to represent total COVID-19 case counts by county.

Both maps are built using Mapbox GL JS and are projected using the Albers Equal Area projection to better represent the country that is the United States.

---

## Live Maps

- **Choropleth Map (Case Rates):**  
  https://farcoolius.github.io/covidcases/map1.html

- **Proportional Symbol Map (Total Cases):**  
  https://farcoolius.github.io/covidcases/map2.html

---

## Map 1: Choropleth – COVID-19 Case Rates

This map visualizes COVID-19 case rates (cases per 1,000 residents) at the county level.

### Features:
- Albers Equal Area projection
- Sequential color ramp
- County boundary outlines
- Interactive popup showing:
  - County name
  - State
  - Total cases
  - Case rate
  - Population (2018 ACS)
- Custom legend with class breaks
- Title and subtitles 

---

## Map 2: Proportional Symbols – Total COVID Cases

This map visualizes total COVID-19 case counts using proportional circle symbols placed at county centroids.

### Features:
- Albers Equal Area projection
- Scaled circle sizes based on case counts
- Interactive popups
- Proportional symbol legend
- Title and subtitle covered

---

## Data Sources

- **COVID-19 cases and rates data:**  
  The New York Times COVID-19 Dataset (2020)

- **Population data:**  
  2018 American Community Survey (5-Year Estimates)

- **County boundary shapefiles:**  
  United States Census Bureau

All data were processed and converted to GeoJSON format via map shaper.  

---

## Libraries Used

- Mapbox GL JS v2.8.1
- JavaScript (ES6)
- HTML5 / CSS3

---

## Data Processing

- Shapefiles were converted to GeoJSON format via mapshaper.
- County case rates were calculated as
