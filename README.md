# NB Fire Map

An interactive web map for monitoring current and recent wildfire activity in New Brunswick, Canada.  
The map integrates multiple authoritative open data sources — including wildfire perimeters, active fire points, smoke forecasts, and environmental conditions — to provide situational awareness.

**Map:** [NBFireMap](https://www.nbfiremap.ca)

---

## Features

- **Active Fire Locations**: Displays new, active, under control, being monitored, and extinguished fire points from Government of New Brunswick (GeoNB) data services.
- **Wildfire Perimeters**: Current wildfire boundaries across Canada via [CWFIS](https://cwfis.cfs.nrcan.gc.ca/maps/fires).
- **Satellite Hotspots**: MODIS and VIIRS fire detections from [NASA FIRMS](https://firms.modaps.eosdis.nasa.gov/).
- **Smoke Forecasts**: NOAA surface smoke concentration forecasts with a timeline animation ([NOAA Smoke](https://www.weather.gov/sti/smoke)).
- **Fire Danger / Risk (FDR)**: Daily fire danger rating maps from [CWFIS](https://cwfis.cfs.nrcan.gc.ca/maps/fdr).
- **Fire Weather Index (FWI)**: Canadian Fire Weather Index components ([summary](https://cwfis.cfs.nrcan.gc.ca/background/summary/fwi)).
- **Fire Behaviour Prediction (FBP)**: Modelled fire behaviour metrics ([summary](https://cwfis.cfs.nrcan.gc.ca/background/summary/fbp)).
- **Burn Restrictions**: Links to official NB burn restrictions and fire watch updates.
- **Environmental Layers**: Weather stations, lightning density, fire danger ratings, radar, and Air Quality Health Index (AQHI).
- **Sentinel-2 Imagery**: Recent high-resolution satellite imagery (via [Esri Living Atlas](https://www.esri.com/arcgis-blog/products/arcgis-living-atlas/imagery/sentinel-2-landsat/)).
- **Aircraft Tracking**: ADS-B flight positions from the [OpenSky Network](https://opensky-network.org/) (sometimes including water bombers and support aircraft).
- **Community Context**: City and town markers with proximity tools to nearby fires (“Near Fires” list with distances).

---

## Data Sources and Ownership

This project depends on official open data services. All data remains the property of its respective owners:

- **Government of New Brunswick (GeoNB / ERD)**  
  - [Active Fire Data & Fire Watch](https://www.gnb.ca/en/topic/laws-safety/emergency-preparedness-alerts/fire-watch.html)  
  - [NB Crown Land](https://geonb.snb.ca/)  
  Ownership: © Province of New Brunswick.

- **Natural Resources Canada (CFS / CWFIS)**  
  - [Canadian Wildland Fire Information System](https://cwfis.cfs.nrcan.gc.ca/home)  
  - [Fire Danger Rating](https://cwfis.cfs.nrcan.gc.ca/maps/fdr)  
  - [Fire Weather Index System](https://cwfis.cfs.nrcan.gc.ca/background/summary/fwi)  
  - [Fire Behaviour Prediction System](https://cwfis.cfs.nrcan.gc.ca/background/summary/fbp)  
  Ownership: © Government of Canada.

- **Environment and Climate Change Canada (ECCC)**  
  - [Weather and Lightning](https://weather.gc.ca/)  
  - [Air Quality Health Index (AQHI)](https://www.canada.ca/en/environment-climate-change/services/air-quality-health-index.html)  
  Ownership: © Government of Canada.

- **NOAA National Weather Service**  
  - [Smoke Forecasts (Surface Concentration)](https://www.weather.gov/sti/smoke)  
  Ownership: © United States Government (public domain).

- **NASA / ESA / Esri**  
  - [MODIS / VIIRS Hotspots via FIRMS](https://firms.modaps.eosdis.nasa.gov/)  
  - [Sentinel-2 Imagery via Esri Living Atlas](https://sentinel.esa.int/)  
  Ownership: © NASA / ESA. Licensed for research and public awareness.

- **OpenSky Network**  
  - [Aircraft Positions API](https://opensky-network.org/)  
  Ownership: © OpenSky Network contributors (non-commercial use).

All layers are presented “as is” for visualization and public awareness. This repository does not modify, republish, or redistribute the underlying datasets.

---

## Acknowledgements

**Firefighters, emergency response teams, and support staff** — for their tireless work protecting lives, communities, and ecosystems.  

**Open data providers and agencies** — in New Brunswick, Canada, the United States, and internationally — for making critical environmental and geospatial data openly accessible.  

**Developers and maintainers** — of Leaflet, Esri Leaflet, and the OpenSky Network, whose open tools make geospatial visualization possible.  

We are deeply grateful for these efforts and recognize that this project would not exist without them.

---

## Disclaimer

This is an unofficial tool created for situational awareness and visualization.  
For official wildfire information, alerts, and restrictions, always consult:  
[Government of New Brunswick Fire Watch](https://www.gnb.ca/en/topic/laws-safety/emergency-preparedness-alerts/fire-watch.html)  

---
