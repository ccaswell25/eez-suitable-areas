# Modeling Suitable Growth Areas for Marine Species on the West Coast of the United States
A repository for analyzing suitable areas for marine aquaculture in West Coast EEZ zones.


## Purpose

Marine aquaculture has the potential to play an important role in the global food supply as a more sustainable protein option than land-based meat production.1 Gentry et al. mapped the potential for marine aquaculture globally based on multiple constraints, including ship traffic, dissolved oxygen, bottom depth .2

This analysis will look at which Exclusive Economic Zones (EEZ) on the West Coast of the US are best suited to developing marine aquaculture. First analyzed for several species of oysters, and then includes a function to understand results for a chosen marine species.

## Structure

```         
eez-suitable-areas
│   README.md
│   Rmd/Proj files    
│   .gitignore
└───data
    │   wc_regions_clean.shp
    │   depth.tif
    │   average_annual_sst_2008.tif
    │   average_annual_sst_2009.tif        
    │   average_annual_sst_2010.tif        
    │   average_annual_sst_2011.tif
    │   average_annual_sst_2012.tif    
```

## Set-up

Data associated with this analysis is too large to be included in the repository. It was downloaded and stored locally and included in the .gitignore. You can find details on the data files included in the R markdown file.
