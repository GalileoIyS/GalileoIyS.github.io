---
layout: default
---

# [](#header-CAT)Plataforma de Catastro Open Source Galileo
Plataforma Open Source de consulta y explotación de Catastro en el ámbito de los países latinoamericanos.

Esta herramienta tecnológica, está orientada al análisis y explotación de datos catastrales, y está concebida como una plataforma que puede adaptarse a diferentes realidades jurídico-técnicas existentes en distintos países, así como escalar en funcionalidades ofertadas según demanda. 

Se trata de una plataforma de software libre con funcionalidades catastrales básicas que puede ser puesta en operación de forma rápida, y que permite adaptarse a la realidad de distintos países en cuanto a sus distintas especificaciones de modelos de datos catastrales básicos, o por supuesto, a funcionalidades específicas requeridas.


* * *
## [](#header-CargaInformacion)Carga de Información
La plataforma provee de un procedimiento de carga inicial de información en el sistema que ofrezce la posibilidad de poner en marcha la plataforma de forma autónoma. 
Este procedimiento de carga está convenientemente documentado en cuanto a los datos de entrada que podrá procesar el sistema, y que estarán basados en formatos abiertos en cuanto a formato y contenido. La plataforma usa:  
 *   formato de ficheros XML y contenido basado en el modelo LADM propuesto en el apartado 2.1. respecto a la información alfanumérica de base 
 *   formatos geográficos estándar como Shapefile o KML, respecto a la información geográfica (parcelario catastral), cuyo requisito fundamental será disponer de, al menos, un atributo alfanumérico (geocódigo) que deberá enlazar con el identificador predial existente en la información alfanumérica.

## [](#header-HerramientasConsulta)Herramientas de Consulta de Datos Prediales
La plataforma provee de herramientas de consulta que ofrecerá la posibilidad de disponer de formularios de extracción de datos catastrales según filtros definibles por el usuario por diferentes atributos de los predios, como cédula de identificación y/o nombre de los titulares, código de identificación predial y/o localización administrativa, etc.

Esta herramienta permite mostrar un formulario de detalle con los atributos del predio catastral seleccionado, y da la posibilidad de localizarlo en la ventana de mapa. 

El formulario de detalle muestra la información básica según modelo LADM, es decir, información física del predio, los sujetos del derecho (titulares) y los derechos que los relacionan.

## [](#header-Mapa)Ventana de Mapa
La solución dispone de una ventana de mapa desde la que los usuarios pueden acceder a la información geográfica catastral, o de otro tipo, que se desee integrar (tanto ráster como vectorial) ofreciendo funcionalidades básicas como:
 *   Herramientas de navegación como zoom in/out, desplazamiento continuo, zoom a una capa, etc.
 *   Posibilidad de imprimir la vista de mapa.
 *   Herramientas de medición lineal y poligonal.
 *   Leyenda que permita seleccionar, mostrar u ocultar capas, así como definir la opacidad de las mismas.
 *   Herramienta de solicitud de información de las parcelas del mapa.

## [](#header-HerramientasExplotacion)Herramientas de Explotación
La plataforma incluye la implementación de herramientas de tematización de datos prediales sobre la ventana de mapa, de modo que el usuario pueda seleccionar un atributo del repositorio de datos asociados a los predios y construir, de forma dinámica, un mapa temático por valores o por rangos, si el atributo es numérico, que sea proyectado en el mapa. 

El conjunto de predios a tematizar podrá ser el universo completo de capas, o estar pre-filtrado desde la herramienta de consulta de datos prediales.



[back](./)
