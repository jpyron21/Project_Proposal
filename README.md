## Project Proposal
#### Jaimee Pyron

#### Objectives
1. Connect Google Earth Engine and R
2. Read spatial data in R
3. Use ggplot2 to create basic analysis/graphs for Synthetic Aperture Radar, or SAR, data
4. Streamline output and utilize proper project management
5. Examine regional flood potential

#### Data Sources
Open access Sentinel-1 SAR data from https://scihub.copernicus.eu/dhus/#/home
This can be accessed directly by Google Earth Engine

#### Languages Used
1. R
2. JavaScript

#### Implementation
The initial spatial pre-processing will be done in Earth Engine. This involves image interpretation
of the Processed Level-1 data at different polarizations. Then earthEngineGrab can be used to connect
GEE with RStudio. Meaningful analysis can then be done in RStudio using ggplot2 to evaluate flood
potential throughout a region.

#### Expected Products
I intend to make two graphs of varying regional flood potential by region, each with the same month of two different
years. Additionally, I would like to produce a visual from the SAR data that supplements the data displayed
in the graphs.

#### Questions for the Instructor
None
