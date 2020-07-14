# Conferencia Virtual de QGIS en America del Norte: Taller Intro
http://qgis.us/qgis-na-2020  

La Conferencia Virtual de QGIS en America del Norte es un evento en línea que está programado para las siguientes fechas, todos los días viernes: 17 de julio, 24 de julio, y 31 de julio. Cada día comienza con un taller de 2 a 4 horas, dichos talleres se llevaran a cabo en la plataforma Zoom, y la otra mitad del día habrá presentaciones hechas via streaming de YouTube. Las sesiones se presentarán en ingles, pero el primer día habrá un taller en español. Los siguientes talleres que se ofrecen son los siguientes:  
17 de julio: Introducción de QGIS (opciones en íngles y español) 
24 de julio: Visualización 2D de geología con QGIS 
31 de julio: Recolección de datos con "Input" y QGIS  

El registro es gratuito, pero es un requisito para recibir la liga de Zoom.  

* * *
## Workshop Details
NEW YORK, United States | MEXICO CITY, Mexico | SANTIAGO DE CHILE, Chile | MADRID, Spain
--- | --- | --- | --- 
10:00a Fri, Jul 17 2020 to 2:00p Fri, Jul 17 2020 | 9:00a Fri, Jul 17 2020 to 1:00p Fri, Jul 17 2020 | 10:00a Fri, Jul 17 2020 to 2:00p Fri, Jul 17 2020 | 4:00p Fri, Jul 17 2020 to 8:00p Fri, Jul 17 2020

Este taller cubrirá los conceptos básicos de los sistemas de información geográfica, los cuales incluyen los cinco componentes principales: el hardware, el software, los datos, los procesos y metodologias, y las personas involucradas. Habrá una presentación de un resumen del hardware y los software más comunes. La sesión utilizará datos públicos como fuentes de información y explicará los procesos comunes para la recolección de datos, incluyendo recolección móvil de datos y hojas de trabajo de campo. Habrá modulos para poner los conceptos en practica y crecer sus capacidades en los siguientes temas: 

- Visualización de datos 
- Propiedades de la capa 
- Herramientas básicas 
- Tablas de atributos 
- Selecciones espaciales y no espaciales 
- Herramientas de geoprocesos y la caja de herramientas de procesamiento 
- Plugins 
- Diseño geográfico y vista de impresión

La sesión terminará con un diálogo sobre la movilización de sus redes individuales e institucionales para crecer un programa eficiente y productivo de sistemas de información geográfica, utilizando ejemplos de Mexico, Ucrania, y Nueva York.

## Objectives
- Review the QGIS software and methods for adding spatial data.
-	Evaluate various image enhancement techniques for both vector and raster data. 
-	Edit existing vector datasets.
-	Review the components of metadata and databases.
-	Use basic tools and panels in QGIS.
-	Manipulate an attribute table in QGIS, including table joins.
-	Phrase an expression to select attribute features.
-	Select features based on their relative relationship to other features (e.g. location).
-	Use common geoprocessing tools.
-	Download new plugins. 
-	Learn basic principles of cartographic design.
-	Use the print layout in QGIS to create a final map product.

## Data
Download data [here](https://drive.google.com/drive/folders/17AXbAxIPZgEM1wNTVL_Mxe051HGYUzSi?usp=sharing).
Layer | Location | Year | Source
--- | --- | --- | ---
**Civil Boundaries**| New York State | 2019 | NYS Office of Information Technology Services GIS Program Office (GPO)
**Roadway Inventory System**| Tompkins County | 2018 | New York State Department of Transportation (DOT)
**Waterbody Inventory**| New York State | 2017 | NYS Department of Environmental Conservation, Division of Water, Bureau of Water Assessment and Management
**Land Use Land Cover**| Tompkins County | 2012 | [Tompkins County Planning Department](https://cugir.library.cornell.edu/catalog/cugir-008162)
**Digital Elevation Model**| Ithaca, Tompkins County | 1995 | [U.S. Geological Survey](https://cugir.library.cornell.edu/catalog/cugir-008186)
**Orthoimagery**| Ithaca, Tompkins County | 2018 | NYS Digital Ortho-imagery Program (NYSDOP), NYS Office of Information Technology Services, GIS Program Office

## Workshop Preparation
- Favor de rellenar este cuestionario antes del fin del día miercoles, 15 de julio: [Questionario para participantes del taller introductorio de QGIS](https://forms.gle/gc8jzvZejLUwRvZJ9);
- Leer las reglas de la reunión en la siguiente sección;
- Familiarizarse con [los términos de sistemas de información geográfica](https://gisgeography.com/gis-dictionary-definition-glossary/#B)--se puede traducir la página con Google Translate en Google Chrome
- Descargar [QGIS 3.10](https://qgis.org/en/site/forusers/download.html); y
- Descargar [los datos del taller en Google Drive](https://drive.google.com/drive/folders/17AXbAxIPZgEM1wNTVL_Mxe051HGYUzSi?usp=sharing).

## Workshop Expectations
1. Al comienzo de la reunión, asegúrese de que su micrófono esté silenciado. El único momento para activar el micrófono en la reunión principal es si usted ha levantado la mano y uno de las instructores ha dicho que lo activará para hablar. En los cuartos de asesoría simultánea, puede activar el sonido de sus micrófonos y hablar con sus compañeros de equipo, pero trate de mantenerse concentrado y enfocado en la tarea.
1. Puede tener su video activado o desactivado.
1. No interrumpa durante la presentación o las demostraciones de QGIS. Si tiene una pregunta, use el icono de levantar la mano en el chat o haga su pregunta directamente en el chat. Alguien estará monitoreando el chat para responder preguntas a medida que surjan. Las preguntas y comentarios también se pueden compartir en el cuarto de asesoría simultánea.
1. La instructora preguntará si los participantes están listos para pasar al siguiente tema o actividad. Los participantes harán clic en el icono "sí" o "no" en el chat de Zoom para informar al instructor si están listos o no. Si la mayoría de los participantes están listos, entonces el taller continuará. Si la mayoría de los participantes no están listos, la instructora revisará el chat para ver qué debería revisar antes de seguir adelante.
1. Solo las instructores pueden compartir su pantalla en la reunión principal. Es posible que usted pueda compartir su pantalla en el cuarto de asesoría simultánea cuando sea apropiado.

# Introduction of QGIS
## Introduction: Coordinate reference systems
Prior to opening any geographic information system (GIS), one should be familiar with coordinate reference systems as you will encounter several different systems in your career as a GIS user. Fundamentally, coordinate reference systems, or spatial reference systems, use coordinates to locate geographical entities, which are mapped using a unique map projection. Map projections differ by type (i.e. pseudocylindrical/cylindrical, pseudoconical/conic, and azimuthal, among others) and whether or not the projection distorts areas or shapes (i.e. equidistant, conformal, and equal-area, among others). All beginner QGIS users should know that EPSG codes are used to identify the coordinate reference system. EPSG stands for the European Petroleum Survey Group – who created the registry of coordinate reference systems codes, which are described at [epsg.io Coordinate Systems Worldwide](https://epsg.io/). 

Different organizations, institutions, and individuals may identify a standard coordinate reference system for homogeneity throughout mapping initiatives and projects. For this training, we will be using the World Geodetic System WGS84 ellipsoid and the Universal Transverse Mercator (UTM) coordinate system. Most of New York State is in the 18th zone of the northern hemisphere, which would be EPSG: 32618.
![alt text](./images/US_UTMzones.PNG "Contiguous US UTM Zones")
*Figure 1. Contiguous US UTM Zones, projected with Lambert conformal conic
Source: Chrismurf at English Wikipedia*

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

