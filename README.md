# geochile

División político administrativa en formato shapefile/geojson

## Contenido
Entidades espaciales simplificadas (livianas) para el uso en aplicaciones web. La información base fue descargada desde [ide.cl](http://www.ide.cl/descarga/capas/item/division-politica-administrativa-poligonos.html). Sólo está presente la información de Chile continental (no está incluida el territorio Antártico, Isla de Pascua y Juan Fernández), y en un futuro será incluído Chile insular.

La referencia espacial para todos los archivos es [EPSG:4326](http://spatialreference.org/ref/epsg/wgs-84/) y la codificación es UTF-8.

La tabla de contenidos incluye:
- COD_REG: código regional (1 a 15) 
- COD_PRO: código provincial
- COD_COM: código comunal como texto (5 caracteres, incluyendo un cero inicial en el caso que corresponda)                                             
- NOM_REG: nombre completo de la región               
- NOM_PRO: nombre de la provincia              
- NOM_COM: nombre de la comuna
- DISTRITO: número del distrito de diputados
- CIRCUN: número de la circunscripción senatorial

En el caso del shapefile, todas las columnas son texto a excepción de las dos últimas (DISTRITO y CIRCUN).

El archivo geojson completo, está probado en [geojson.io](http://bl.ocks.org/d/2fcc318b6c7b2e0da843822879000179). También está dividido por región (número de región como nombre).

¡Cualquier aporte es bienvenido!

## Referencias
- [ide.cl](http://www.ide.cl/descarga/capas/item/division-politica-administrativa-poligonos.html)
- [Biblioteca del Congreso] (http://www.bcn.cl/siit/nuestropais/divisionelectoral/index.htm)







