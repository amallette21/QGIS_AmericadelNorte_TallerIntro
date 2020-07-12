# Conferencia Virtual de QGIS en America del Norte: Taller Intro
http://qgis.us/qgis-na-2020  

La Conferencia Virtual de QGIS en America del Norte es un evento en línea que está programado para las siguientes fechas, todos los días viernes: 17 de julio, 24 de julio, y 31 de julio. Cada día comienza con un taller de 2 a 4 horas, dichos talleres se llevaran a cabo en la plataforma Zoom, y la otra mitad del día habrá presentaciones hechas via streaming de YouTube. Las sesiones se presentarán en ingles, pero el primer día habrá un taller en español. Los siguientes talleres que se ofrecen son los siguientes:  
17 de julio: Introducción de QGIS (opciones en íngles y español) 
24 de julio: Visualización 2D de geología con QGIS 
31 de julio: Recolección de datos con "Input" y QGIS  

El registro es gratuito, pero es un requisito para recibir la liga de Zoom.  

* * *

Este taller cubrirá los conceptos básicos de los sistemas de información geográfica, los cuales incluyen los cinco componentes principales: el hardware, el software, los datos, los procesos y metodologias, y las personas involucradas. Habrá una presentación de un resumen del hardware y los software más comunes. La sesión utilizará datos públicos como fuentes de información y explicará los procesos comunes para la recolección de datos, incluyendo recolección móvil de datos y hojas de trabajo de campo. Habrá modulos para poner los conceptos en practica y crecer sus capacidades en los siguientes temas: 

- Visualización de datos 
- Propiedades de la capa 
- Herramientas básicas 
- Tablas de atributos 
- Selecciones espaciales y no espaciales 
- Herramientas de geoprocesos y la caja de herramientas de procesamiento 
- Los plugins 
- Diseño geográfico y "layout manager"  

La sesión terminará con un diálogo sobre la movilización de sus redes individuales e institucionales para crecer un programa eficiente y productivo de sistemas de información geográfica, utilizando ejemplos de Mexico, Ucrania, y Nueva York.

* * *
# Introduction of QGIS

## Introduction: Coordinate reference systems
Prior to opening any geographic information system (GIS), one should be familiar with coordinate reference systems as you will encounter several different systems in your career as a GIS user. Fundamentally, coordinate reference systems, or spatial reference systems, use coordinates to locate geographical entities, which are mapped using a unique map projection. Map projections differ by type (i.e. pseudocylindrical/cylindrical, pseudoconical/conic, and azimuthal, among others) and whether or not the projection distorts areas or shapes (i.e. equidistant, conformal, and equal-area, among others). All beginner QGIS users should know that EPSG codes are used to identify the coordinate reference system. EPSG stands for the European Petroleum Survey Group – who created the registry of coordinate reference systems codes, which are described at epsg.io Coordinate Systems Worldwide: https://epsg.io/. 

Different organizations, institutions, and individuals may identify a standard coordinate reference system for homogeneity throughout mapping initiatives and projects. For this training, we will be using the World Geodetic System WGS84 ellipsoid and the Universal Transverse Mercator (UTM) coordinate system. Most of New York State is in the 18th zone of the northern hemisphere, which would be EPSG: 32618.
 
Figure 1. Contiguous US UTM Zones, projected with Lambert conformal conic
Source: Chrismurf at English Wikipedia

## Introduction to QGIS
QGIS is a free and open source software used to visualize, create, edit, analyze, and publish geospatial data that runs on Windows, Mac, Linux, and BSD. It helps us answer geographic questions and to create persuasive maps.

-	Official QGIS site: http://qgis.org/
-	QGIS Map Showcase: https://www.flickr.com/groups/qgis/pool/

First, let’s review what comes with a QGIS download: 
-	GRASS GIS – (Geographic Resources Analysis Support System) is free; it is used for geospatial data management and analysis, image processing, production of maps and graphics, spatial modeling, and other visualizations. It can be used as a stand-alone program or directly in QGIS  by opening “QGIS Desktop 3.10. with GRASS 7.8.2”
-	QGIS – (previously, Quantum Geographic Information System) is free; it is used to create, edit, visualize, analyze, and publish geospatial information. Desktop – Start new projects, edit data, perform geospatial analyses. Again, you can open Desktop with GRASS for more analysis options.
-	Qt Designer – to create QGIS plugins’ interface dialogs, but also to create highly customized feature forms for editing vector layers’ attributes in QGIS projects.
-	SAGA GIS (2.3.2) – (System for Automated Geoscientific Analyses) is a GIS software with immense capabilities for geodata processing and analysis. SAGA is programmed in the object oriented C++ language and supports the implementation of new functions with a very effective Application Programming Interface (API).
-	Setup – a windows installer for Open Source GIS project that tracks different open source software and notifies you of newer versions so you can simply upgrade programs.

### Exercise 1. Getting started with QGIS
Start QGIS: Start, (Type or search) QGIS 3.10, QGIS 3.10.7-A Coruña

Step | Image
--- | ---
Start QGIS: Start, (Type or search) QGIS 3.10, QGIS 3.10.7-A Coruña| ![alt text](./images/Vector_ClassifiedRoads.PNG "Classified Roads")
1| ![alt text](./images/Vector_ClassifiedRoads.PNG "Classified Roads")
2| ![alt text](./images/Vector_ClassifiedRoads.PNG "Classified Roads")
3| ![alt text](./images/Vector_ClassifiedRoads.PNG "Classified Roads")
4| ![alt text](./images/Vector_ClassifiedRoads.PNG "Classified Roads")
5| ![alt text](./images/Vector_ClassifiedRoads.PNG "Classified Roads")
6| ![alt text](./images/Vector_ClassifiedRoads.PNG "Classified Roads")

