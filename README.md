#Tutorial de LeafletJS

Guía básica para iniciarse en Leaflet, librería open source de JavaScript para crear mapas, presentado en las [Jornada de herramientas cartográficas. Election Maps](http://medialab-prado.es/article/herramientas-cartograficas-election-maps) del grupo de periodismo de datos de Medialab Prado.

Link a la presentación: http://adrianblanco.github.io/leafletjs-tutorial/

###Paso 1: Esqueleto HTML
Para empezar tenemos que crear el esqueleto HTML en el que introduciremos más tarde el código CSS y Javascript.
ATENCIÓN: Aunque en este ejemplo vamos a guardar el código en un mismo fichero html para facilitar la comprensión del ejercicio, lo ideal sería escribir el código html, css y javascript en ficheros separados.
Archivo: [tutorial_leaflet_1.html] (https://github.com/adrianblanco/leafletjs-tutorial/blob/gh-pages/Tutorial%20paso%20a%20paso/tutorial_leaflet_1.html)

###Paso 2: Crear el <div></div>
Creamos el div, la "caja" donde irá el mapa.
Archivo: [tutorial_leaflet_2.html] (https://github.com/adrianblanco/leafletjs-tutorial/blob/gh-pages/Tutorial%20paso%20a%20paso/tutorial_leaflet_2.html)

###Paso 3: Script sources
Enlazamos dentro de la <head> a los ficheros de código fuente que nos permitirán trabajar con Leaflet.
Archivo: [tutorial_leaflet_3.html] (https://github.com/adrianblanco/leafletjs-tutorial/blob/gh-pages/Tutorial%20paso%20a%20paso/tutorial_leaflet_3.html)

###Paso 4: CSS
Dentro de la etiqueta <style></style> introducimos el código CSS.
Archivo: [tutorial_leaflet_4.html] (https://github.com/adrianblanco/leafletjs-tutorial/blob/gh-pages/Tutorial%20paso%20a%20paso/tutorial_leaflet_4.html)

###Paso 5: Dibujar mapa base
Comenzamos con Javascript, a partir de ahora el cógio que escribamos irá dentro de la etiqueta <script></script>, dentro del body de nuestro código HTML.
Archivo: [tutorial_leaflet_5.html] (https://github.com/adrianblanco/leafletjs-tutorial/blob/gh-pages/Tutorial%20paso%20a%20paso/tutorial_leaflet_5.html)

###Paso 6: Mi primer marcador
Nueva variable de Javascript en la que introduciremos la geolocalización de la misma, así como el texto que queremos que muestre entre " ".
Archivo: [tutorial_leaflet_6.html] (https://github.com/adrianblanco/leafletjs-tutorial/blob/gh-pages/Tutorial%20paso%20a%20paso/tutorial_leaflet_6.html)

###Paso 7: Mi primer popup
Cambia el nombre de la variable, en lugar de "marker", escribimos "popup". El procedimiento es el mismo.
Archivo: [tutorial_leaflet_7.html] (https://github.com/adrianblanco/leafletjs-tutorial/blob/gh-pages/Tutorial%20paso%20a%20paso/tutorial_leaflet_7.html)

###Paso 8: Mi primer Polyline
Por último, dibujamos una línea en el mapa mediante la sucesión de unas coordenadas.
Archivo: [tutorial_leaflet_final.html] (https://github.com/adrianblanco/leafletjs-tutorial/blob/gh-pages/Tutorial%20paso%20a%20paso/tutorial_leaflet_final.html)

###Quiero saber más
El mejor recurso para ampliar información es la *documentación* que puede encontrarse en la web de [Leaflet JS](http://leafletjs.com/reference.html). Además, también hay unos [tutoriales](http://leafletjs.com/examples.html) muy sencillos para aprender de forma práctica

###Paso 7: Mi primer popup
Archivo: tutorial_leaflet_7.html

###Paso 8: Mi primer Polyline
Archivo: tutorial_leaflet_final.html
