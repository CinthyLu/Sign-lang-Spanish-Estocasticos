# Pasos

1. Descargar el dataset, y meterlo en una carpeta con el cuaderno de python

![Organización carpetas](image.png)


2. cargar y etiquetar los datos, manualmente el informe dice tener estos datos


Attribute Description Relevant
 x Positiononxaxis *
 y Positiononyaxis *
 z Positiononzaxis * // las imagenes son más estándares, entonces le voy a colocar valores más cercanos


 roll Palmrotation *  // no le veo tanta utilidad si manejamos las manos de frente


 pitch Nodescription
 yaw Nodescription   // no dice que son, pero son rotación no la usamos por el dataset


 thumb Thumbfingerposition *
 fore Forefingerposition *
 index Indexfingerposition *
 ring Ringfingerposition *
 little Littlefingerposition	// no tengo los valores para darme cómo guía
				// voy a colocar un numero por dedo, indicando 
				// qué tan flexionado está


 keycode Keyontheglobepressed  // botones, supongo que si los dedos hacen contacto


 gs1 Firststateoftheglove  //booleanos de si se usan o no las manos, First izquierda, 
 gs2 Secondstateoftheglove // Second derecha


 Sign Signal read  // valor del guante



SE ME OLVIDÓ PERO B, TIENE ROTACIÓN X 90 ROTACIÓN Z 180

## Para la el etiquetado de datos
![alt text](image-1.png)