# Multitemporal-analysis-of-RS-data-via-the-ggridges-package: Internship proposals


#### PROPOSAL 1: Plant Phenology Analysis ####

Scope: Use ridgeplots to display the variation of important vegetation parameters (vegetation indices) related to phenology on annual and multi-year scales.

Data: From Copernicus, 1 image for each month of 2 different years (2014 and 2017) representing NDVI

A) Annual Scale: Draw distributions of NDVVI values for each month of a single year. 

B) Multi-year Scale: x = NDVI, y = month, fill = year


#### PROPOSAL 2: Analysis on Emilia-Romagna Forest Maps ####

Scope: Use ridgeplots to draw the distribution of values of different vegetation indices in relation to the forest type.

Possible application: Test the use of ridgeplots as a tool for visualization and preliminary analysis for remote forest type classifications.

Data:
Emilia-Romagna orthophoto (Google Earth)
Forest maps of the Emilia-Romagna region

Ridgeplot Model: (x = pixel value (radiance); y = forest types; fill = spectral bands)

Procedure:
1) Crop the region's orthophoto using forest maps
2) Extract pixel values from the orthophoto and save belonging forest areas in one dataframe
3) Calculate vegetation indices
4) Ridgeplot: x = VI, y = forest types, fill = spectral bands


#### PROPOSAL 3: Monitoring Copernicus Variables ####

Examples: Land Surface Temperature
Change in the distribution of the Land Surface Temperature variable from 2010 to 2020, categorizing by country/geographic gradient (e.g., latitude). Useful to visualize if and how climate changes in the last 10 years (temporal gradient) have unevenly or uniformly modified surface temperatures based on country or latitude (geographic gradient).

Other potential applications: Land Use in Natura 2000 Sites
Change in land use in Natura 2000 sites through multi-temporal analysis of Copernicus N2K products. Three orthomosaics collected every 6 years are available: 2006, 2012, 2018.
