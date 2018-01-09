### [datourbano](https://github.com/datourbano): Bases de BiciMAD - Madrid

* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/ubicacion_18.png) Ciudad: [Madrid](https://datourbano.github.io/madrid)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/origen_18.png) Origen: [Portal de datos abiertos del Ayuntamiento de Madrid](http://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=f17b841a2c7d6410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/calendario_18.png) Fecha: 01-01-2018
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/carpeta_18.png) Repositorio: https://github.com/datourbano/madrid/tree/master/movilidad/bici/servicios
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/enlace_18.png) LinkedData: [28079_bases_bicimad.geojson](https://raw.githubusercontent.com/datourbano/madrid/master/movilidad/bici/servicios/28079_bases_bicimad.geojson)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/mapa_18.png) Visualización: [Bases BiciMAD - Madrid](https://datourbano.github.io/madrid/movilidad/bici/servicios/28079_bases_bicimad)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/notas_18.png) Notas:
  
  (Portal de datos abiertos del Ayuntamiento de Madrid)

  "El alquiler de bicicleta pública es un servicio dirigido a todos los ciudadanos y visitantes de la ciudad de Madrid, como elemento alternativo de transporte limpio que contribuye a un modelo de movilidad más sostenible y al fomento de hábitos de transporte más equilibrados y saludables. 

  Cada estación se compone del tótem (CIC) que es el centro de interacción con el ciclista y de los anclajes para la colocación de las bicicletas.

  El servicio de bicicleta pública está sujeto a unas tarifas aprobadas por el Ayuntamiento de Madrid, las cuales incluyen un seguro que cubre cualquier percance sufrido durante su utilización. 

  El horario de funcionamiento es de forma ininterrumpida durante las 24 horas del día los 365 días del año.

  Este conjunto presenta la misma información que el denominado "Bici: Bases de Bicimad, servicio público de bicicleta eléctrica de la ciudad de Madrid", pero en un formato que permite su visualización directa en Google Maps, Google Earth y otras aplicaciones GIS."

* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/herramienta_18.png) Tratamiento:
  
  Versión: 21-01-2017 

  >Los datos originales se encuentran en formato kmz, conteniendo cada elemento sus datos asociados en una tabla *html*.  Esto permite un resultado visual estructurado en GoogleEarth, pero dificulta el procesamiento de datos en su conjunto.
  >
  >Se han extraído individualmente los elementos del fichero kmz, almacenándose todos ellos en un fichero GeoJSON, lo que permite un tratamiento general de datos más cómodo.
  >
  >Los datos finales se ofrecen en coordenadas geográficas OGC CRS:84 (EPSG:4326 lon-lat), utilizando una codificación de caracteres UTF8, manteniéndose todo el conjunto de atributos asociados.
  >  
  >  Se ha realizado un muestreo aleatorio de la precisión y exactitud geográfica, no habiéndose detectado problemas de geolocalización.
  
  Versión: 03-11-2017

  >No se aprecia una actualización de datos desde la versión anterior.  

  Versión: 01-01-2018
  
  >No se aprecia una actualización de datos desde la versión anterior.
  >
  >Se ha ajustado la precisión del fichero GeoJSON a siete decimales de grado.
  >
  >El fichero original kmz ofrece para cada punto, datos de coordenadas UTM ETRS89 Huso 30 (EPSG:25830) y geográficas (EPSG:4326), siendo la precisión de la latitud de estas últimas superior a 1 metro (5 decimales). Por esta razón para la georreferenciación de esta versión se ha optado por utilizar las coordenadas EPSG:25830, ya que ofrecen más exactitud, lo que puede producir un desplazamiento de los puntos respecto a los datos de versiones anteriores de algún decímetro.