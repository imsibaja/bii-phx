# Change in Biodiversity Intactness in Phoenix
![Image](https://www.azcentral.com/gcdn/-mm-/10cc64f0b869f41892a33aedf84732975161d6ab/c=0-178-3504-2158/local/-/media/2016/03/31/Phoenix/Phoenix/635950469596703234-sprawl.jpg?width=1320&height=746&fit=crop&format=pjpg&auto=webp) _Gibert, Arizona_ from [AZ Central](https://www.azcentral.com/story/opinion/op-ed/2016/04/03/phoenix-sustainability/82393246/)

## About
This repository contains notebooks `bii-phx.ipynb` whose goal is to analyze the effects of urban sprawl on biodiversity and ecosystem health in the Phoenix metropolitan area.

## Repository organization

```
 thomas-fire-analysis
│   README.md
|   bii-phx.ipynb
|   .gitignore
│
└───data
    |   tl_2020_04_cousub.cpg
    |   tl_2020_04_cousub.dbf
    |   tl_2020_04_cousub.prj
    |   tl_2020_04_cousub.shp
    |   tl_2020_04_cousub.shp.ea.iso.xml
    |   tl_2020_04_cousub.shp.iso.xml
    |   tl_2020_04_cousub.shx
```
## About the Data:

All data is housed within the repository and will run with the proper packages installed. To access the data, run the notebook cell by cell. For more information on the data, refer to the citations below.

### Arizona Shapefiles
The U.S. Census Bureau's TIGER/Line Arizona Shapefile is a set of shapefiles that outline boundaries within the state of Arizona. These files are publicly available and widely used for mapping, spatial analysis, and geographic information system (GIS) applications. Information such as counties, cities, census tracts and districts, roads, rivers, and lakes is included. 

### Biodiversity Intactness Index (BII)
This dataset consists of maps of global biodiversity intactness. This Microsoft Planetary Computer STAC Collection builds models of biodiversity and human relationships. The BII is modeled from abundance and compositional similarity. This dataset will help us visualize and analyze the change in biodiversity intactness through the years.

## References
United States Census Bureau [2020 TIGER/Line Shapefiles](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=County+Subdivisions)

Microsoft Planetary Computer STAC catalog [Biodiversity Intactness Index (BII)](https://planetarycomputer.microsoft.com/dataset/io-biodiversity)

- Z. Levitt and J. Eng, “Where America’s developed areas are growing: ‘Way off into the horizon’,” The Washington Post, Aug. 2021, Available: https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/. [Accessed: Nov. 22, 2024]
- F. Gassert, J. Mazzarello, and S. Hyde, “Global 100m Projections of Biodiversity Intactness for the years 2017-2020 [Technical Whitepaper].” Aug. 2022. Available: https://ai4edatasetspublicassets.blob.core.windows.net/assets/pdfs/io-biodiversity/Biodiversity_Intactness_whitepaper.pdf

Galaz García, Carmen. Final Project – EDS 220 - Working with Environmental Datasets. (n.d.). https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/final-project
