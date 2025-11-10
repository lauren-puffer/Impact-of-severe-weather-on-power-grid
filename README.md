# Impact of severe weather on power grid

## Data sources

All of the data housed in this repository is open-access and free to use. We extracted data from the following sources.

**Open Street Map:** <https://planet.openstreetmap.org/>

**U.S. Census:** U.S. Census Bureau. (2020). *American Community Survey 5‑Year Estimates, 2019, Census Tracts, Texas (ACS_2019_5YR_TRACT_48_TEXAS).* Geodatabase, layer: “ACS_2019_5YR_TRACT_48_TEXAS”. U.S. Department of Commerce.

Website: <https://www.census.gov/data/datasets.html>

**Blackout data:** VIIRS Land SIPS. (2019). *VIIRS/NPP Daily Gridded Day Night Band 500 m Linear Lat Lon Grid Night (VNP46A1) [Data set].* NASA/GSFC/SED/ESD/HBSL/BISB/LAADS. <https://doi.org/10.5067/VIIRS/VNP46A1.001>

**EJ Screen data:** EJ SCREENEPA, 2024, "Environmental Justice Mapping and Screening Tool (EJScreen)", <https://doi.org/10.7910/DVN/RLR5AX>, Harvard Dataverse, V4, UNF:6:Ew64oHBMGoTrNkLoYBJcUw== [fileUNF]

## Repository layout

```{r}
Impact-of-severe-weather-on-power-grid
└───README.md
└───Rmd/Proj files    
└─── texas_blackout.qmd 
└───.gitignore
    └───data
        └───gis_osm_buildings_a_free_1.gpkg
        └───gis_osm_roads_free_1.gpkg
        └───ACS_2019_5YR_TRACT_48_TEXAS.gdb
            └───census tract gdb files
        └───VNP46A1
            └───VIIRS data files
```

## Authors

Owner of repository: Lauren Puffer

## Acknowledgments

I would like to acknowledge the two poeople who taught me these data manipulation and visualization skills, Annie Adams and Alessandra Vidal Meza. I would also like to thank my classmate Garrett Craig, for trouble shooting this assignment with me and discussing the workflow.
