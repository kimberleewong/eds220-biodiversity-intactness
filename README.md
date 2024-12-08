# Biodiversity Intactness Index

Kimberlee Wong - December 7, 2024

## About

This repository includes one notebook and one data folder. This notebook shows the process of using both a shapefile and a collection from the Microsoft Planetary Computer STAC catalog to visualize differences in the Biodiversity Intactness Index in Phoenix, Arizona from 2017 to 2020. Percentages were calculated and then visualized. The data folder includes the shapefile that has all the counties of Arizona.

![image](https://www.nhm.ac.uk/content/dam/nhmwww/our-science/Data/biodiversity-indicators/global-map-bii-two-column.jpg.thumb.1920.1920.jpg)

## Repository Structure
```
eds220-biodiversity-intactness
│
├── README.md                     
├── hwk4-task2-false-color-wong.ipynb
├── hwk2-task3-aqi-wong.ipynb                       
├── .gitignore
├── thomas-fire-blog.ipynb                  
│
├── data/                      
│   ├── tl_2020_04_cousub/
│       ├──tl_2020_04_cousub.dbf
│       ├──tl_2020_04_cousub.prj
│       ├──tl_2020_04_cousub.shp
│       ├──tl_2020_04_cousub.shx
│       ├──tl_2020_04_cousub.shp.ea.iso.xml
│       ├──tl_2020_04_cousub.shp.iso.xml
│       ├──tl_2020_04_cousub.cpg
```

## Data

The biodiversity intactness data comes from Microsoft Planetary Computer Data Catalogue.

The Arizona shapefile, that was filtered to Phoenix in this notebook, comes from the United States Census Bureau. 

## References

Microsoft Planetary Computer Data Catalogue, Biodiversity Intactness. Available from: https://planetarycomputer.microsoft.com/dataset/io-biodiversity Access date: December 7, 2024.

United States Census Bureau. 2020 version. Available from: https://www.census.gov/cgi-bin/geo/shapefiles/index.php Access date: December 7, 2024

Biodiversity intactness index. Natural History Museum. (n.d.). https://www.nhm.ac.uk/our-science/services/data/biodiversity-intactness-index.html 
