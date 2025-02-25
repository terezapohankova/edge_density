# Edge Density (ED) and Shanon Diversity Index (SDI) for ArcGIS Pro

This repository contains a Python script for calculating Edge Density and Shanon Diversity Index based on the Fragstats metrics (https://fragstats.org/index.php/fragstats-metrics/patch-based-metrics/area-and-edge-metrics/l4-edge-density and https://fragstats.org/index.php/fragstats-metrics/patch-based-metrics/diversity-metrics/l4-shannons-diversity-index).


# Requirements
Originally created for **ArcGIS Pro v. 3.3.0.**

*	Python (tested on 3.9.9)
*	arcpy (tested on 2.9)

# Input Data

* Vector layers
	* Shapefile layer with (multi)polygons for which ED is detected
  * the (multi)polygons must be cut using a grid with a regular number of sides (e.g. square, octagon)
	* each (multi)polygon must be assigned a numeric ID
	* the (multi)polygons must be cut using a grid with a regular number of sides (e.g. square, octagon)
   
https://github.com/terezapohankova/edge_density/assets/60270092/82909cd1-7c7a-4c63-bf76-c980758776d2


# Output Data
* Output a layer with newly added columns regarding caluclation and results

# Video tutorial (adding script to ArcGIS Pro and launching)
https://github.com/terezapohankova/edge_density/assets/60270092/e3808940-7119-4d95-9a1b-3ff700203f9d

