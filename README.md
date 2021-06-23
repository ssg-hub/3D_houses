# 3D_houses :houses: Project

**Project duration :** 2 weeks

**Project dates :** 14th - 21st June, 2021

### Team Spacy : _Arnaud D, Lyes R, Shilpa S_

### Project Objective :
---
The project **3D_houses** ojective is to generate a **3D** model of the building structure for a given address in the Flanders region of **Belgium**.  

***Input :*** _An address given by user or selected by user from a pre-determined list._  
Example : Rue de Geneve 12, Evere
Google map view :

***Output :*** _A **3D** image rendered for the building structure at the above address._  
Example :

### Learning Objectives :
***
:heavy_check_mark: **Consolidate the knowledge in Python :snake:, specifically in :**   
- NumPy    
- Pandas  
- Matplotlib 

:heavy_check_mark: **to be able to search and implement new libraries**  
_New libraries searched and explored_  
* geopandas
* osgeo , gdal
* rastario
* shapely

:heavy_check_mark: **to be able to read and use the shapefile format**  
Read and used shapefiles from .shp files within [public data](https://eservices.minfin.fgov.be/myminfin-web/pages/cadastral-plans) for Belgium coordinate system _L_72 i.e.Lambert 72_  

:heavy_check_mark: **to be able to read and use geoTIFFs**  
Read and used geoTIFFs from .tif files within the **DTM** and **DSM** public data.  

:heavy_check_mark: **to be able to render a _3D_ plot**  
(link to 3D plot)

:heavy_check_mark: **to be able to present a final product**     
(link to the jupyter notebook)

### The Client and mission behind the project
***
-Client: LIDAR PLANES, active in the Geospatial industry.  
-End use of data : To launch a new branch in the insurance business.  
-3D_houses project goal : To build a solution with the client data to model a house in 3D with only a home address.  

**Must-have features MVP** 
3D lookup of houses :heavy_check_mark: :heavy_check_mark: _Delivered_  

**Nice-to-have features**  
Optimize your solution to have the result as fast as possible.  
Features like the living area of the house in m², how many floors, if there is a pool, the vegetation in the neighborhood, etc...  
Better visualization.  :heavy_check_mark: :heavy_check_mark: _Delivered_  

### Data :
***
[DSM - Digital Surface Model](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dsm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DSM,%20raster,%201m) 
[DTM - Digital Terrain Model](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dtm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DTM,%20raster,%201m)  
Above links contain the required _.tif_ files for DSM and DTM respectively.

[Cadastral Data](https://eservices.minfin.fgov.be/myminfin-rest/cadastral-plan/cadastralPlan/2020/Belgium/72)  
Above link contains the required _.shp_ files for Belgium specific Lambert72 coordinates.

### Installation Guide


### How to use
[Click here to open the interface](link to jupyter nb)  

Enter an address.  

### Results  
***  
#### Data Visualization  
:belgium: Plot a 3D house from a given list of addresses in Flanders.    
(link to notebook)
Image


:belgium: Plot a 3D structure for a monument in Flanders, Belgium.  
(link to notebook)
Image

more images  

### Challenges  
***  
#### Understanding the data
Geodata was a new format of data that was interesting as well as challenging. The  essential parts of data needed in this context are the .tif and .shp files.

* The first step was to understand the data provided, which were the above mentioned DSM and DTM files. Here is a diagram to visually represent the same.  


* Next, to figure out how to use DSM and DTM and to establish the relation CHM for end plotting.
![DSM, DTM, CHM](https://user-images.githubusercontent.com/80852343/123079978-ba9dab00-d41c-11eb-9fcc-11c92c1bb7bf.png)


* Another dimension was the complexity of data present in the DSM, DTM (43 x 2) zip folders, which totalled to more than 20/40 GB of data. Multiple files exist in layered file tree. The .tif files from 




### **Contributions**







**Libraries Used:**

