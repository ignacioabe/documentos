---
title: "Una ciudad oculta: herramientas geoespaciales en la era de los datos"
author: Ignacio Abé
---

<!-- introducción más general sobre el valor de los datos GEO. -->

## Introducción

El mundo está viviendo lo que denomina por varios una nueva revolución industrial, en la que el centro del desarrollo y el imaginario de la sociedad es internet y la información que aquí se crea y transmite. Los datos se generan y consumen a una velocidad inconmensurable e incomprensible por una mente humana, convirtiéndose en una nueva forma de poder. Esto ha afectado a muchas disciplinas, entre estas la del Urbanismo. Las ciudades siempre se han planeado en base a la información disponible, pero antes su recolección era un proceso costoso, lento y artesanal mientras que hoy en día la pregunta parece ser ¿Qué se puede hacer con tanta información?

El análisis de estos datos no pretende reemplazar la intuición, sino más bien informarla, potenciarla y permitir una visión más amplia y multidimensional del ámbito urbano, que permita leer sus dinámicas y contrastes.

Trabajar con sistemas de información geográfica (SIG) ya no es exclusivo de ministerios o de unas pocas consultoras con respaldo económico, gracias a que, por un lado, muchos gobiernos publican sus datos de modo abierto, existen extensas bases de datos colaborativas, y a que por otro lado, ha surgido un interesante ecosistema de herramientas libres para trabajar con datos geoespaciales.

El propósito del workshop es, en primer lugar, entregar herramientas prácticas para poder desarrollar tareas básicas en cuanto al manejo de datos. Esto abarca principalmente la obtención, el procesamiento, la visualización cartográfica y el análisis estadístico, etapas que serán revisadas a partir de ejercicios prácticos aplicados al caso de estudio (los campus UC). Para agilizar los procesos se dispondrá de un conjunto de sets de datos ya preparado, lo que permitirá introducir temas de cartografía y análisis rápidamente.

Un aspecto fundamental de la metodología es que se propone el uso exclusivo de herramienta gratuitas, de código abierto y multi plataforma, para que los alumnos tengan absoluta libertad de continuar usándolas durante su trabajo académico y profesional posterior.

## Metodología

### Sesión 1: obtención de datos

La idea es comenzar con una introducción breve de la importancia y utilidad del trabajo con datos geoespaciales, poniendo énfasis cómo el desarrollo tecnológico y cultural de los últimos años ha democratizado este campo del conocimiento. Luego veremos algunos aspectos técnicos fundamentales de SIG que facilitarán el trabajo posterior, como proyecciones, formatos, soportes, metodologías, fuentes y otros.

Posteriormente veremos aspectos más prácticos del trabajo con datos geoespaciales, enfocándonos en la obtención de datos. Para esto veremos algunas de las fuentes principales, con foco en Openstreetmap (un mapa colaborativo del mundo) y datos abiertos gubernamentales. Veremos además herramientas que nos permitan revisar y depurar los datos recolectados.

Para acelerar y facilitar el trabajo se proporcionarán los siguientes conjuntos ya procesados.

- [OpenStreetMap](https://www.openstreetmap.org/#map=15/-33.4390/-70.6341)
- [censo 2017, INE](http://www.censo2017.cl/servicio-de-mapas/)
- [catastro nacional de condominios sociales, MINVU](http://minvuhistorico.minvu.cl/opensite_20160405114853.aspx) o [aquí](http://www.ide.cl/index.php/planificacion-y-catastro/item/1851-catastro-nacional-de-condominios-sociales)
- [indicadores SIEDU, CNDU](http://siedu.ine.cl/)
- [accidentes peatón y ciclista, CONASET](http://mapas-conaset.opendata.arcgis.com/)
- [permisos de edificación, INE](http://geoine-ine-chile.opendata.arcgis.com/search?q=permisos)
- [institutos de educación parvularia, escolar y superior, MINEDUC](http://www.geoportal.cl/geoportal/catalog/search/resource/resumen.page?uuid=%7BDF31295E-846D-49A0-A964-2A0641133194%7D)

Otras fuentes interesantes para revisar

- [shapes CIAS](https://drive.google.com/drive/folders/1_sMfB5Q0YtzBtf2akEehj9_7WlysHU3R?usp=sharing) 
- [certificados de recepción final](http://geoine-ine-chile.opendata.arcgis.com/search?q=certificados)

### Herramientas

QGIS, Kepler.gl, openRefine

#### Tarea propuesta

Exploración libre de los datos proporcionados o encontrados, en busca de hallazgos interesantes que puedan informar los proyectos, sobre todo en las áreas de estudio. Creación de mapas con la suma de dos o más capas y anotaciones sobrepuestas de hallazgos relevantes, en kepler.gl (o qgis si descubren cómo).

La tarea consiste en familiarizarse con los conceptos, herramientas y fuentes de información revisadas durante la primera sesión. Para esto, se explorarán libremente los datos proporcionados o encontrados por los alumnos en qgis, open refine y kepler.gl, con el objetivo de comprenderlos y representarlos.

La entrega consiste en un PDF en el que se recopilarán mapas (hechos en kepler) que representen la información geoespacial, idealmente diferenciando según atributos y sumando distintas capas.

Los mapas deben ir acompañados textos descriptivos y anotaciones que sinteticen los hallazgos más relevantes encontrados durante el proceso de exploración.

### Sesión 2: creación de datos

<!-- Para la información geoespacial, las restricciones de acceso y uso, junto con la enorme inconsistencia en el modo de denominar y representar elementos es un dolor de cabeza a la hora de trabajar. Un proyecto que pretende resolver algunos de estos problemas y que ha revolucionado el ámbito geoespacial es Openstreetmap (u OSM), una base de datos geográficos del mundo entero. En esta sesión se mostrará cómo funciona OSM, cómo se puede descargar y añadir información y cómo puede utilizarse. -->

Como no basta con la información que se encuentra, en esta sesión veremos algunos métodos básicos para crear datos desde cero o derivados de lo existente. Para esto se hará una revisión teórica breve de los métodos actuales de levantamiento y recolección y de las categorías en la que estos datos se pueden clasificar.

Luego, haremos una revisión práctica de cómo crear información nueva o derivada con herramientas abiertas o de fácil acceso, con foco en el trazado, la recolección en terreno, la superposición de capas y algunos geoprocesos. En esta misma línea, también se hará un tutorial de cómo editar y añadir información a OpenStreetMap.

#### Herramientas_

QGIS, GPS, field papers, openstreetmap

#### Tarea propuesta_

Creación de información relevante al área de estudio, con recolección en terreno y trazado de fotos satelitales.

Edición en OSM, mejorando y complementando los datos en las los polígonos de condominios sociales, con especial énfasis en los bloques de departamentos. Lo mismo para las inmediaciones del campus San Joaquín (los otros ya están relativamente mapeados).

### Sesión 3: visualización de datos

El volumen de la información y los sets de datos en general, hace que prácticamente sólo sea posible extraer ideas y conocimientos a partir de herramientas de análisis. Con la información geográfica ocurre lo mismo. Generalmente un sólo elemento puede contener muchos atributos, y estos pueden ser visualizados de muchos modos distintos. En esta sesión revisaremos un poco de la teoría básica de visualización de datos, y la aplicaremos a los geodatos seleccionados y encontrados por los alumnos. Como complemento veremos algunos tipos de análisis y visualizaciones no geográficas, basadas en un lenguaje de programación llamado python.

#### Herramientas___

kepler-gl, QGIS y python / google collab

#### Tarea propuesta___

Creación de visualizaciones geográficas que permitan entender fenómenos urbanos del área de estudio (campus), idealmente combinando dos o más fuentes de información y utilizando visualización por atributos. Estas visualizaciones deben estar anotadas con hallazgos e ideas relevantes. Entrega en PDF y un mapa de KEPLER.

### Sesión 4: cierre y revisión resultados

Esta sesión estará principalmente dedicada a revisar los resultados del workshop, haciendo hincapié tanto en las dudas y dificultades que han surgido como en las nuevas perspectivas que se han alcanzado. Si el tiempo lo permite, revisaremos algunas herramientas muy relevantes en el trabajo con datos pero que no alcanzan a ser cubiertas adecuadamente en el workshop, como librerías para mapeo web, interacción y otros.

#### Herramientas (opcionales)

leaflet, mapbox, osmnx, etc
