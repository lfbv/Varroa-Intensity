# Varroa-Intensity
Code and data for "Spatiotemporal, environmental, and behavioral predictors of Varroa intensity in managed honey bee apiaries"

## Datasets: 

apiarydata_201819.csv : Data for years 2018 and 2019. Each row represents one apiary. Data are compiled from state of Illinois Inspection reports. Each apiary has associated latitude and longitude. These are used as the training data for model fitting.

apiarydata_202021.csv : Data for years 2020 and 2021. These are used as the testing data for model validation.

mitesvirus.csv: This data is used to show the relationship between number of mites and viral load, as shown in Supplementary material.

Enviromental Data - broaderHiveOutput3km.csv : Environmental indicators (floral and nesting quality, pesticide load) downloaded from BeeScape (https://beescape.psu.edu) in 2018


## Code

The code are in two R markdown files. 

modeling.Rmd fits all the models referenced in the manuscript and produces the tables in the Supplemenatry material

plots.Rmd creates all the plots used in the paper and Supplement
