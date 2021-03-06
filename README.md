# Identifying areas of opportunity in Bangkok for food delivery service platforms with Local Moran's I

_In partial fulfillment of IBM Data Science Capstone_

Local Moran's I (I=0.241, p=0.0048) of 83 Bangkok districts' venue value per capita identified one hot spot (4 districts),  one cold spot (2 districts) and one geospatial outlier for targeted prospecting and market research. Sensitivity analysis produces an area of interest of districts which self-cluster into the entire southwest region (17 districts). Recommendations to a hypothetical business were made, starting with immediate prospecting in 'doughnut' outliers, which have potential to provide high value like their neighbors.

![geospatial_reccs](https://user-images.githubusercontent.com/8182121/80268096-bf2ccf00-8672-11ea-8069-d049a6b7b7fb.png)

**statistics**: Global Moran's I, Local Moran's I

**competencies**: Geospatial hot spot analysis, multiple hypothesis testing, sensitivity analysis

**tools**: ArcGIS, GeoDa, Python (libpysal, esda, splot; geopandas, shapely, scipy, statsmodel, matplotlib)

## Notebook link
Global, Local Moran's I:
- [venue value per capita](https://nbviewer.jupyter.org/github/akbarry/Coursera_Capstone/blob/master/GIS-Bangkok-venue-value.ipynb)

Data Mining:
- [Bangkok venues](https://nbviewer.jupyter.org/github/akbarry/Coursera_Capstone/blob/master/Bangkok_venues.ipynb)
- [Bangkok venue likes](https://nbviewer.jupyter.org/github/akbarry/Coursera_Capstone/blob/master/Bangkok-venue-likes.ipynb)
- [Bangkok district population](https://nbviewer.jupyter.org/github/akbarry/Coursera_Capstone/blob/master/Bangkok_population.ipynb)
- [Bangkok district saturation](https://nbviewer.jupyter.org/github/akbarry/Coursera_Capstone/blob/master/Bangkok_district_saturation.ipynb)
- [Foursquare request helpers](https://github.com/akbarry/Coursera_Capstone/blob/master/foursquare.py) 

Other:
- [Global/Local Moran's I - venue density](https://nbviewer.jupyter.org/github/akbarry/Coursera_Capstone/blob/master/GIS-Bangkok-venue-density.ipynb) for visualizations

## Report
[Link](https://github.com/akbarry/Coursera_Capstone/blob/master/docs/Bangkok_Food_Venue_Hot_Spot_Analysis_Report.pdf)


## Video presentation
Audience: Online marketplace businesses with physical storefront locations
[Link](https://www.loom.com/share/9f37ce6a0e3348d1b997e3d4caa44cca)
