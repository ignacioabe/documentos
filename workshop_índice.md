# Índice workshop

## Estructura general sesiones

- primera mitad: teoría y práctica (80 min)
- pausa 20 minutos
- segunda mitad: encargo y revisión entregas (80 minutos)

Excepto en la primera y última sesión.

## Sesión 1: obtención de datos

<!-- TEORÍA -->

<!-- 30 minutos -->
- introducción (usar pdf mapas)
  - presentación personal
    <!-- - experiencia como arquitecto
    - viaje por europa en bicicleta
    - fundación de pedaleable.org
    - Mapocho pedaleable y Elqui p.
    - investigación sobre ámbitos geoespaciales
    - trabajo en la Municipalidad de Santiago
    - trabajo en la Corporación Ciudades -->

- explicación estructura sesiones: trabajo con datos
  <!-- simplemente leer la pauta y anotar el título en la lámina -->
  1. obtención y depuración
  2. creación
  3. análisis y visualización
  4. cierre y revisión resultados

- evolución tecnológica SIG (hitos recientes)
  - satélites (GPS y fotografía)
  - teléfonos inteligentes (creación y consumo de información)
  - filosofía de código abierto
    - software (qgis y muchos más)
    - openstreetmap (y otros)
    - gobierno
    - datos de otras fuentes (fotos, DEM, etc)

<!-- esto amerita tener unos esquemas ya diseñados -->
- sistemas de referencia de coordenadas (proyecciones)
  - no hay solución perfecta
  - familias de proyecciones (planas, cilíndricas y cónicas)
  - distorsiones (forma, área, dirección, distancia)
  - sistemas comunes
    - wgs84 (EPSG:4326)
    - wgs84 / pseudo mercator (EPSG:3857)
    - utm19s (EPSG:32719)

- secuencia común en el trabajo con datos
  - obtención y/o creación
  - revisión y preparación
  - análisis y visualización

- soportes gráficos
  - estáticos
    - impresos (láminas, diarios, libros, etc)
    - digitales
  - interactivos
    - web
    - aplicaciones móviles

- formatos
  - vectoriales
    - CSV
    - shapefile
    - geojson
    - geopackage
    - teselas
  - raster
    - TIFF
    - DEM
    - txt
    - teselas

- fuentes
  - de terceros
    - openstreetmap
    - datos abiertos gubernamentales
    - ONGs
    - aplicaciones / empresas
  - propias (sesión 2)
    - catastros en terreno
    - trazado de imágenes
    - encuestas

<!-- PRÁCTICA -->

<!-- 60 minutos -->
- herramientas (funcionalidad e interfaces)
  - QGIS
  - openrefine
  - Kepler.gl

<!-- 60 minutos -->
- obtención de datos
  - OSM
    - qué es
    - wiki
    - API overpass turbo (web y qgis)
  - gubernamentales
    - <geoportal.cl> (infraestructura de datos espaciales)
    - <CONASET.cl>
    - <earthexplorer.usgs.gov/>

- revisión de los datos en qgis
- depuración en openrefine
- visualización en kepler

## Sesión 2: creación de datos

<!-- TEORIA: 30 minutos -->

- introducción
- modos de creación de información geoespacial
  - vectorial
    - levantamiento en terreno (con o sin gps)
    - trazado fotos
    - encuestas
    - aplicaciones (uber, strava, etc)
    - geocodificación
    - derivada (procesos vectoriales)
  - raster
    - vuelos
    - satélites
    - drones
    - derivada (procesos raster)

- tipos de información
  - vectorial
    - puntos
    - líneas
    - vectores
    - mixta*
    - otros (mesh, LIDAR, etc)
  - raster
    - mapas de bits
    - multiespectrales
    - otros

<!-- PRÁCTICA: 75 minutos -->

- herramientas
  - en terreno
    - GPS o app equivalente (opentracks)
    - papel o field papers
  - en el escritorio
    - QGIS
      - importación de datos GPS
      - interoperabilidad con AUTOCAD
      - edición de capas
        - creación de columnas nuevas y derivadas
      - creación de capas
        - src y campos
        - imágenes de fondo (google + sectra)
        - dibujo de geometrías
        - ingreso datos
        - edición de geometrías
        - herramientas básicas de selección
        - herramienta vectoriales
          - de geoproceso
          - de geometría
          - de análisis
    - OPENSTREETMAP
      - creación de cuenta
      - edición en ID
        - puntos clave antes de editar*
        - importación de datos GPS
        - trazado
        - claves / valores

<!-- CORRECCIÓN PARCIAL DE TAREAS: 60 minutos -->
<!-- ENTREGA DE TAREA 3: 15 minutos -->

## Sesión 3: visualización de datos

- introducción
  - en qué consiste la visualización de datos (variables a dimensiones)
  - metodología (intención a herramientas)

- tipos de visualizaciones
  - gráficos
    - dispersión
    - líneas / áreas
    - barras / histograma
    - red
    - gantt
    - etc...
  - cartográficos
    - puntos
    - cúmulos (clusters)
    - agregación geométrica
    - cloroplastos
    - flujos

- visualización de datos geoespaciales
  - estáticos
    - QGIS
  - interactivos / web
    - kepler.gl
    - umap
    - leaflet
    - mapbox

- visualización de datos en general
  - tabulares
    - python
    - jupyter notebooks / google collab
  - otros tipos de datos
    - raster
    - sonido
    - etc

## Sesión 4: recapitulación, anexos y otros

- revisión final de los trabajos
- anexos
  - leaflet
  - mapbox
  - osmnx
