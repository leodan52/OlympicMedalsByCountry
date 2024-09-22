# OlympicMedalsByCountry

## Introducción

**OlympicMedalsByCountry** es un proyecto de análisis de datos centrado en las medallas ganadas por diferentes países en los juegos olímpicos, tanto los de verano como los de invierno. Este análisis explorará el rendimiento olímpico de cada país, comparándolo con características geográficas como el continente al que perteneces, el número de habitantes, etcétera.

El proyecto estará estructurado en base a notebooks IPYNB, los cuales incluirán las visualizaciones y estadísticas realizadas para el análisis. Cada notebook tendrá un objetivo diferente: Extracción de datos, tratamiento de datos, análisis descriptivo y análisis predictivo.

### Objetivo del proyecto

El objetivo principal del presente proyecto es didáctico. Probar ideas para explorar y analizar un conjunto de datos y así encontrar patrones, aplicando conocimientos en Estadística y *Machine Learning*, todo ejecutado con las herramientas que posee Python.

Técnicamente es un proyecto experimental qué trata de incluir varias técnicas de la Ciencia de Datos, tantas como sean posibles, y así practicar el uso de herramientas como Pandas, Seaborn, Matplotlib, Sklearn, entre otras.

## Requerimientos
El proyecto ha sido desarrollado usando **Python 3.8.10**, con los siguientes módulos,

 * countryinfo==0.1.2
 * geopandas==0.13.2
 * googletrans==4.0.0rc1
 * matplotlib==3.7.1
 * numpy==1.22.3
 * pandas==1.4.3
 * pycountry==24.6.1
 * requests==2.31.0
 * scikit_learn==1.3.0
 * seaborn==0.12.2
 * Unidecode==1.1.1

Y Pandas y Geopandas requieren otras dependencias para su funcionamiento óptimo. Se usaron lo siguiente,

 * beautifulsoup4==4.12.2
 * html5lib==1.1
 * lxml==4.9.3
 * fiona==1.9.6

Puede instalar estos paquetes exactos usando el archivo `requirements.txt`, ejecutando la siguiente linea en terminal:

```bash
pip install -r requirements.txt
```

## Estructuctura del proyecto
 0. [Extracción y tratamiento de datos](00-Tratamiento_de_Datos.ipynb)
    * [Anexo: Extracción de indicadores del Banco mundial](Anexo_Tratamiento_datos_WBG.ipynb)
 1. [Análisis descriptivo](01-Analisis_estadistico_descriptivo.ipynb)
 2. [Análisis predictivo (en proceso)](02-Analisis_predictivo.ipynb)

## Fuentes

Los datos se obtienen de las siguientes fuentes:

 * Colaboradores de Wikipedia (2024, 31 de agosto). *All-time Olympic Games medal table*. Wikipedia, The Free Encyclopedia. Fecha de consulta: Septiembre 7, 2024, desde https://en.wikipedia.org/w/index.php?title=All-time_Olympic_Games_medal_table&oldid=1243257136
 * *Anexo:Países por continentes*. (2024, 25 de junio). Wikipedia, La enciclopedia libre. Fecha de consulta: junio 25, 2024 desde https://es.wikipedia.org/w/index.php?title=Anexo:Pa%C3%ADses_por_continentes&oldid=160945926.
 * *Anexo:Comparación de los códigos del COI, la FIFA y la ISO 3166.* (2024, 7 de agosto). Wikipedia, La enciclopedia libre. Fecha de consulta: 14:42, agosto 7, 2024 desde https://es.wikipedia.org/w/index.php?title=Anexo:Comparaci%C3%B3n_de_los_c%C3%B3digos_del_COI,_la_FIFA_y_la_ISO_3166&oldid=161734382.
 * Una serie de indicadores obtenidas de las bases de dados del [Banco Mundial](https://data.worldbank.org/).