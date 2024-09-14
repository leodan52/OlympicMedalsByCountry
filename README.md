# OlympicMedalsByCountry

## Introducción

**OlympicMedalsByCountry** es un proyecto de análisis de datos centrado en las medallas ganadas por diferentes países en los juegos olímpicos, tanto los de verano como los de invierno. Este análisis explorará el rendimiento olímpico de cada país, comparándolo con características geográficas como el continente al que perteneces, el número de habitantes, etcétera.

El proyecto estará estructurado en base a notebooks IPYNB, los cuales incluirán las visualizaciones y estadísticas realizadas para el análisis.

Hasta el momento, el proyecto en su fase temprana consta del tratamiento de datos y la primera parte del análisis estadístico descriptivo. Los datos son guardados en dos archivos CSV, donde el principal se puede encontrar en [data/olympics.csv](data/olympics.csv).

También hay otro archivo llamado [data/info_countries.csv](data/info_countries.csv) con la información de países y una selección de indicadores que se usarán en el análisis de correlación.

## Estructuctura del proyecto:
 0. [Extracción y tratamiento de datos](00-Tratamiento_de_Datos.ipynb)
 1. [Análisis descriptivo (en proceso)](01-Analisis_estadistico_descriptivo.ipynb)

## Fuentes

Los datos se obtienen de las siguientes fuentes:

 * Colaboradores de Wikipedia (2024, 31 de agosto). *All-time Olympic Games medal table*. Wikipedia, The Free Encyclopedia. Fecha de consulta: Septiembre 7, 2024, desde https://en.wikipedia.org/w/index.php?title=All-time_Olympic_Games_medal_table&oldid=1243257136
 * *Anexo:Países por continentes*. (2024, 25 de junio). Wikipedia, La enciclopedia libre. Fecha de consulta: junio 25, 2024 desde https://es.wikipedia.org/w/index.php?title=Anexo:Pa%C3%ADses_por_continentes&oldid=160945926.
 * *Anexo:Comparación de los códigos del COI, la FIFA y la ISO 3166.* (2024, 7 de agosto). Wikipedia, La enciclopedia libre. Fecha de consulta: 14:42, agosto 7, 2024 desde https://es.wikipedia.org/w/index.php?title=Anexo:Comparaci%C3%B3n_de_los_c%C3%B3digos_del_COI,_la_FIFA_y_la_ISO_3166&oldid=161734382.
 * Una serie de indicadores obtenidas de las bases de dados del [Banco Mundial](https://data.worldbank.org/).