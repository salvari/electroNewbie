¿Qué vamos a hacer? ¿Qué se describe en este documento?
=======================================================

Apuntes de electrónica por supuesto.

LEDS
====

> Wikipedia "Un led (del acrónimo inglés LED, light-emitting diode: ‘diodo emisor de luz’; el plural aceptado por la RAE es ledes ) es un componente optoelectrónico pasivo y, más concretamente, un diodo que emite luz."

Calculo de resistencias para leds
---------------------------------

**NO ESTÁ TERMINADO**

Un led y en general cualquier diodo es una unión de dos elementos semiconductores. Este tipo de uniones tienen una caída de voltaje de valor fijo (al menos en el rango de funcionamiento normal).

<table style="width:46%;">
<caption>Caída de tensión típica en leds</caption>
<colgroup>
<col width="33%" />
<col width="12%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Color del led</th>
<th align="center">Tensión umbral</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Rojo</td>
<td align="center">1,6 V</td>
</tr>
<tr class="even">
<td align="left">Rojo alta luminosidad</td>
<td align="center">1,9 V</td>
</tr>
<tr class="odd">
<td align="left">Amarillo</td>
<td align="center">1,7 2 V</td>
</tr>
<tr class="even">
<td align="left">Verde</td>
<td align="center">2,4 V</td>
</tr>
<tr class="odd">
<td align="left">Naranja</td>
<td align="center">2,4 V</td>
</tr>
<tr class="even">
<td align="left">Blanco Brillante</td>
<td align="center">3,4 V</td>
</tr>
<tr class="odd">
<td align="left">Azul</td>
<td align="center">3,4 V</td>
</tr>
<tr class="even">
<td align="left">Azul 430nm</td>
<td align="center">4,6 V</td>
</tr>
</tbody>
</table>

La corriente que necesita el led también depende del tipo de led, pero en general están entre 10mA y 30mA. Con corrientes bajas obtendremos poco brillo y el led durará mucho. Con corrientes altas obtendremos más brillo y una vida útil más corta. Un valor de 20mA es un buen compromiso entre ambos extremos.

META
====

De momento nos proponemos usar pandoc para generar los documentos, en esta sección describiremos detalladamente como se generan los distintos documentos de salida usando pandoc.
