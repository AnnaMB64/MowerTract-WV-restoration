
# Mower Tract Mined Land Restoration, WV

Ecological restoration of reclaimed mined lands on Cheat Mountain, in Randolph and Pocahontas Counties, West Virginia. The Mower Tract mined lands are part of the Monongahela National Forest.

*Across the README.md file, please answer the who, what, when, where, why, and how of the map making process*

## Project Contents

*If you wanted to include a table of contents to sections, and then links to each section.*

- [Data Source](#data-source)
- [Project Background](#project-background)
- [Purpose](#purpose)
- [Mapmaking Process](#mapmaking-process)
    - [Mapbox Starter Style](#mapbox-starter-style)
    - [Upload Data to QGIS](#upload-data-to-qgis)
    - [Merge Layers and Organize Attribute Table](#merge-layers-and-organize-attribute-table)
    -[Add Layers to Mapbox, Customize styles, and Add Labels](Add-Layers-to-Mapbox,-Customize-styles,-and-Add-Labels) 
   
- [Map summary](#map-summary)

***

### Data Source

[Link to data source](https://...)

* Initial Data projection in ArPro: NAD 1983 UTM Zone 17N / Transverse Mercator / 26917
* QGIS projection: NAD83 / UTM zone 17N EPSG:26917
* Final Mapbox map projection: 

Mapbox Style: Classic Mapbox Satellite

The data used to create the map, shapefiles of the restoration areas, trails, dispersed campsites, and wetlands, have been created over the years primarily by U.S. Forest Service Monongahela National Forest partners, and sometimes Green Forests Work partners. These data are not available online.

In QGIS, Google Satellite XYZ tiles were used as a background for my process graphics.

### Project Background

*If you are interested in [other Markdown formatting options](https://www.markdownguide.org/basic-syntax/)*

Starting in 2010, the U.S. Forest Service Monongahela National Forest (MNF) began a partnership with Green Forests Work (GFW), a nonprofit housed in The University of Kentucky's Forestry Department, and a host of partners to conduct a suite of restoration activities, including non-native species removal, soil decompaction, organic matter loading, mined land reforestation, and wetland creation. In the short term, the goal is to create an early successional habitat, with the ultimate goal being to establish a red spruce dominant forest. Ancillary benefits include improved water quality, enhanced wildlife habitat, and improved ecosystem services, such as carbon sequestration. To date, nearly 900,000 seedling have been planted on almost 1,500 acres at the Mower Tract on Cheat Mountain in the MNF.

### Purpose
*Please write about the map purpose using complete sentences.*

This map was created to showcase the mined land restoration work completed from 2010 through the end of 2024, and to layout some of the plans for future work.

### Mapmaking Process

*Example of in process map ![in process image](filepath)*

*You can describe the mapmaking process in this section, including images where it helps to describe the process.*

*You can also use some lists, and here's some formatting ideas.*

1. **Example bold**
2. *Example italics*
3. 
4. 

#### Mapbox Style

Classic Mapbox Satellite with some customizations, such as __________

I customized this style to change road colors in the main frame, and as as you zoom out other names and boundaries appear, such as county names, state abbreviations, ocean names, and country names.

#### Upload Data to QGIS

I knew that I needed to do some manipulation of my data before adding it to my Mapbox style, so I added the shapefiles to QGIS. The 14 layers represent 14 mined land restoration areas "completed" over 14 years. I say "completed" because we are always going back into these restoration areas to do enhancement work.

![Add shapefiles](graphics/2_UploadDataToQGIS.png)
*Adding shapefiles to QGIS.*

I also added data to QGIS for restoration area name points, dispersed campsites, trails, and wetlands.

#### Merge Layers and Organize Attribute Table

I merged vector data from 14 layers into one layer and cleaned up the attribute table. To do this, I navigated to the Merge Vector Layer tool by selecting Vector > Data Management Tools from the top menu bar. A temporary file was created, which I exported to a GeoJSON file and named. Because the attribute tables of the 14 layers were created over many years and some contained fields unique to just one layer, leaving a large number of null cells, combined attribute table columns needed to be cleaned up manually and organized.

![Merge vector layers](graphics/3_MergeVectorLayers.png)
*Merging vector layers.*

I also merged data for the dispersed campsites, trails, and wetlands, but I did not need to clean up their attribute tables.

#### Add Layers to Mapbox, Customize Styles, and Add Labels

One by one, I added the merged and cleaned up resoration areas, dispersed campsites, trails, wetlands, and restoration area names point data to Mapbox. I manipulated the colors, sizes, and opacities, and changed these at various zoom levels. I changed the restoration area names points type to a symbol and added the names. I duplicated the trails layer and made it a symbol text and added labels to the various trails, which I also changed the colors of. I added the dispersed campsite numbers. 

#### 

Restoration areas

I did these same steps for adding the names of the trails and the assigned numbers for each dispersed campsite.





### Map summary

What are the key findings to take from your map and the overall mapmaking process?

## Final Project Link

Here you are linking from the README.md to the index.html.

Please view the [final map online](www.github...)
