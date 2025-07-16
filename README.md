Geospatial Analysis of Snow Crab Dataset
This project is a geospatial data analysis of snow crab populations collected through marine trawls. It was designed to demonstrate proficiency in geospatial data processing, interactive data visualization, and spatial trend discovery. The project supports my application to Zoox by showcasing my ability to analyze large datasets involving geolocation, temporal patterns, and environmental variables.

Objective
To explore spatial and temporal trends in snow crab populations using geospatial techniques. The analysis focuses on uncovering patterns in distribution, sex, catch rates, and environmental conditions such as bottom temperature and depth.

Dataset Overview
The dataset includes records of snow crab collections across multiple years and locations. Each row represents a unique haul (trawl event), including both geospatial and environmental attributes.

Key columns used:

latitude, longitude: Start location of the haul in decimal degrees

year: Year of the collection

sex: Gender of the crab

cpue: Catch per unit effort (number/square nautical mile)

bottom_depth: Weighted average depth at which trawl occurred (in meters)

bottom_temperature: Temperature at the bottom of the trawl (in tenths of degrees Celsius)

surface_temperature: Surface temperature at the haul location

haul: Unique identifier for each trawl

name: Common name of species

Tools & Libraries Used
Python

GeoPandas and Shapely for geospatial operations

Matplotlib and Seaborn for static plots

Folium and Plotly for interactive maps and charts

Pandas and NumPy for data wrangling and computation

scikit-learn for clustering geospatial locations

Contextily for basemaps in spatial visualization

Key Analyses
Exploratory Spatial Analysis:
Visualized haul locations, catch density, and sex distribution over years. Identified regions with high CPUE and consistent activity.

Temperature and Depth Analysis:
Analyzed bottom/surface temperature trends and their relationship with crab distribution. Investigated correlations between environmental factors and CPUE.

Interactive Visualization:
Created dynamic maps (Folium, Plotly) to explore how crab catch, depth, and temperature vary spatially and temporally.

Spatial Clustering:
Applied K-Means clustering to geospatial coordinates to identify distinct crab distribution zones.

Outcomes
Identified spatial patterns and environmental factors associated with high crab density.

Demonstrated the ability to build a reproducible geospatial data pipeline.

Built interactive tools to explore relationships between species distribution and climate metrics.
