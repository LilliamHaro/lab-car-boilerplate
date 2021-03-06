# LAB-CAR

Usando los recursos de bootstrap y Google Maps Api logramos desarrollar una página web responsive para el servicio de taxis Labcar en el cual el usuario puede realizar un trazado de ruta entre dos puntos ingresados mediante inputs y visualizarlo en un mapa.

![labcar](https://user-images.githubusercontent.com/32288575/36438557-4d1596b0-1638-11e8-83f6-9c7a88eb1217.png)

## Desarrollado para [Laboratoria](http://www.laboratoria.la/)

## Herramientas utilizadas
	- HTML5
	- CSS3
	- JS
	- Bootstrap
	- Google Maps api
	- Api de HTML5 (Geolocation)

## Funcionamiento

**Autocompletado de direcciones**

Para el autocompletado de direcciones se uso la función de la biblioteca de Places de la Google Maps JavaScript API. Esta herramienta se uso con la finalidad de darlea la aplicación el comportamiento de escritura anticipada para simplicar el trabajo del usuario y evitar errorer de escrituras

![Recursos](assets/images/autocompletado.png)

**Trazado de rutas**
El trazado de ruta se uso una key única dentro de un script ubicado dentro del html en el cual se esta integrando como callback a la funcion de inicio para el trazado(callback=initMap) y la libreria de autocompletado de google maps. Este sería el resultado en el mapa.
![Recursos](assets/images/trazado.png)


**RESULTADO FINAL**

![Recursos](assets/images/desktop.png)

**MODALES**

![Recursos](assets/images/modal-1.png)

![Recursos](assets/images/modal-2.png)

![Recursos](assets/images/modal-3.png)

![Recursos](assets/images/mobile.png)

## Fuentes de Consulta
 - Documentacion de Google Api [Ver.](https://developers.google.com/maps/documentation/?hl=es-419)
 - Laboratoria Lms [Ver.](https://lms.laboratoria.la/)
 - Documentacion de Bootstrap [Ver.](https://getbootstrap.com/docs/3.3/getting-started/)

  ![Labcar-icon](assets/images/logoForma.png)
