---
layout: post
title: Clase 1 de Electronica basica
description: Clase sobre Ley de ohm, Calculos de resistencia (circuitos series, paralelos y mixtos)
author: David Antonio Toro Medina (dtorome - correo: david-toro92@hotmail.com)
---

# INTRODUCCIÓN

Un circuito electrico es un sistema que tiene varios componentes, consta de una resistencia electrica, un voltaje y una corriente.

![Figura 1. Elementos de un circuito electronico](/Imagenes/Imagen1.png)

En la figura 1 se observa varios elementos como un interruptor el cual permite o no el flujo la corriente un elemento que consume la corriente como el motor y la resistencia, ya que si se cierra el circuito sin elementos provocará un corto circuito en la fuente. A lo largo de estas clases se explicara los conceptos y cálculos básicos de electrónica. 

##  RESISTENCIA

Una resistencia eléctrica es aquella que limita la corriente del sistema.

![Figura 2. Ilustración de resistencias eléctricas](/Imagenes/Imagen10.png)

En la Figura 2 se observa dos simbologías de resistencia, siendo la primera del sistema inglés y la segunda es del sistema internacional (SI). 

Para conocer el valor de la resistencia estas tienen un codigo de colores los cuales se ve en la figura 3.

![Figura 3. Codigo de valor de Resistencias](/Imagenes/Imagen11.png)

En un circuito electrónico podemos encontrar principal tres tipos de conexiones los cuales son:

1. Resistencia en Serie:

![Figura 4. Resistencias en Serie](/Imagenes/Imagen3.png)

En la figura 4 se tienen tres resistencias en serie, esto se dice si se cumple la condición de "Si los elementos comparten un solo nodo (un solo punto de conexión) y este no este conectado con otro elemento, se dice que es en serie" (Ver Figura 5).

![Figura 5. Identificación de Resistencias en Serie](/Imagenes/Imagen12.png)

¿Para que saber si el circuito esta en serie o no? Es necesario saber ya que los calculos de este es diferente que los otros, para una resistencia en serie la corriente (A) es la misma para cada una de las que este en este modo. Mientras que el voltaje de la fuente se distribuye para cada uno (NOTA: No es equitativa, esto depende de la resistencia).

$$ Vt-V1-V2-V3=0 $$
$$ It=I1=I2=I3 $$

Siendo Vt voltaje (Tensión en algunos libros) de la fuente y It como corriente de tensión.

Para calcular la resistencia equivalente en serie se hace de la siguiente forma:

$$ Req=R1+R2+R3 $$

2. Resistencia en Paralelo:

![Figura 6. Resistencias en Paralelo](/Imagenes/Imagen4.png)

En la figura 6 se tienen tres resistencias en paralelo, esto se dice si se cumple la condición de "Si los elementos comparten dos nodos (dos punto de conexión), se dice que es en paralelo" (NOTA: Paralelo en electrónica no quiere decir lo mismo que en geometría) (Ver Figura 7).

![Figura 7. Identificación de Resistencias en Paralelo](/Imagenes/Imagen13.png)

Como en circuito de serie, las resistencias en paralelo el voltaje es el mismo, mientras que la corriente se distribuye entre cada elemento (NOTA: No es equitativa, esto depende de la resistencia).

$$ It-I1-I2-I3=0 $$
$$ Vt=V1=V2=V3 $$

Siendo Vt voltaje (Tensión en algunos libros) de la fuente y It como corriente de tensión.

Para calcular la resistencia equivalente en paralelo se hace de la siguiente forma:

$$ 1/Req=1/R1+1/R2+1/R3 $$

Para calcular la forma más efectiva se recomienda realizar la siguiente ecuación con solo dos elementos.

$$ Req=(R1+R2)/(R1*R2) $$

La resistencia equivalente debe ser menor que la menor de las resistencias en paralelo.

3. Resistencia Mixto:

La resistencia en mixto es la mezcla de resistencias en serie y paralelo.

![Figura 8. Identificación de Resistencias Mixto](/Imagenes/Imagen2.png)

## LEY DE OHM

Este es una formula, la cual ayuda a obtener valores ya sea resistencia, corriente o voltaje.

$$ V=I*R $$ Calculo para obtener voltaje
$$ I=V/R $$ Calculo para obtener corriente
$$ R=V/I $$ Calculo para obtener resistencia

Con estas formulas y la de las resistencias series y paralelo se podra calcular todos los valores deseados.

## MEDICIÓN DE CIRCUITOS

Para medir un circuito electrónico se debe saber que uno de los medidores es el multimetro, este tiene dos principales mediciones los cuales son:

1. Voltaje

Para medir voltaje en un circuito se debe tener en cuenta que se comporta como una resistencia por lo que se debe conectar en paralelo del elemento para obtener el voltaje exacto.

![Figura 9. Medición de voltaje con un multimetro](/Imagenes/Imagen5.png)

2. Corriente

El multimetro tiene otra opción que es de medir corriente, pero este se debe cambiar las terminales de conexión y se recomienda que el circuito electrónico debe estas sin alimentación, ya que se debe intervenir y poner en serie para obtener la corriente como las resistencias en serie.

![Figura 10. Medición de Corriente con un multimetro](/Imagenes/Imagen6.png)

## EJEMPLO

Se tiene el siguiente circuito:

![Figura 11. Ejemplo de Ley de ohm](/Imagenes/Imagen8.png)

En este circuito tenemos corriente y una resistencia, por lo que podemos calcular el voltaje (o tensión) total del circuito, por medio de la formula de la ley de ohm.

$$ V=I*R $$
$$ V=1*100 $$
$$ V=100V $$

## BIBLIOGRAFÍA

1. Agarwal, A., & Lang, J. H. (2008). Foundations of Analog and Digital Electronic Circuits. Massachusetts, Estados Unidos: Elsevier.
2. All About Circuits. (s.f.). Recuperado el 23 de 09 de 2012, de http://www.allaboutcircuits.com/vol_6/chpt_2/4.html
3. Boylestad, R. L. (2007). Introductory Circuit Analysis (11 ed.). Upper Saddle River: Pearson Prentice Hall.
4. Electronics Teacher. (s.f.). Recuperado el 23 de 09 de 2012, de http://www.electronicsteacher.com/alternating-current/complex-numbers/more-on-ac-polarity.php
5. Clase de electrónica Basica de la Universidad EAFIT.