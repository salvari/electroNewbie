¿Qué vamos a hacer? ¿Qué se describe en este documento?
=======================================================

Apuntes de electrónica por supuesto.

LEDS
====

> Wikipedia "Un led (del acrónimo inglés LED, light-emitting diode:
> ‘diodo emisor de luz’; el plural aceptado por la RAE es ledes ) es un
> componente optoelectrónico pasivo y, más concretamente, un diodo que
> emite luz."

Calculo de resistencias para leds
---------------------------------

**NO ESTÁ TERMINADO**

Un led y en general cualquier diodo es una unión de dos elementos
semiconductores. Este tipo de uniones tienen una caída de voltaje de
valor fijo (al menos en el rango de funcionamiento normal).

  ----------------------------------
  Color del led             Tensión
                            umbral
  ------------------------ ---------
  Rojo                       1,6 V

  Rojo alta luminosidad      1,9 V

  Amarillo                  1,7 2 V

  Verde                      2,4 V

  Naranja                    2,4 V

  Blanco Brillante           3,4 V

  Azul                       3,4 V

  Azul 430nm                 4,6 V
  ----------------------------------

  : Caída de tensión típica en leds

La corriente que necesita el led también depende del tipo de led, pero
en general están entre 10mA y 30mA. Con corrientes bajas obtendremos
poco brillo y el led durará mucho. Con corrientes altas obtendremos más
brillo y una vida útil más corta. Un valor de 20mA es un buen compromiso
entre ambos extremos.

META
====

De momento nos proponemos usar pandoc para generar los documentos, en
esta sección describiremos detalladamente como se generan los distintos
documentos de salida usando pandoc.
