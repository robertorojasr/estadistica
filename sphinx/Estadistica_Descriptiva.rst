
=======================
Estadística Descriptiva
=======================

Es la que consolida los datos, ordena, resume y representa. O sea describe entrega ciertas
características de la muestra sin decir mucho de que tan buen trabajo está haciendo con
respecto a la población, no hace predicciones ni proyecciones, solo da información sobre
los datos de la muestra.


Conceptos básicos
#################

Graficar y tabular
******************

Graficar y tabular como todo tiene su ciencia y su arte, puede ser la diferencia entre
auditores interesados que aprenden y auditores que no entienden nada y se duermen. Además
si no se hace con cuidado puede distorsionar la información percibida. Lo dicen 8 de cada
10 dentistas.

Hay muchas formas de tabular y graficar datos, cada una tiene sus usos, gracias y
desgracias, lo primero es identificar que tipo de variable (:ref:`escalas de medida
<escalas-de-medida>`) vamos a representar:

Nominales (no ordenables)
=========

Tablas
------
Basta con cuantas veces se repite cada valor y eso seria, también se puede agregar el % de cada uno.

Gráficos
--------
Son preferibles los circulares, se pueden usar tambien de barras pero las variables al
no tener orden no se gana nada con ponelas en ejes y se pierde la visualización de
la proporción con el total. Con el circular el orden no importa (es un circulo) y no
solo se representan las relaciones entre las variables, también se representan sus
relaciones con respecto al total de yapa.

Ordinales (ordenables)
======================

Tablas
------
Aquí como se pueden y deben ordenar hace sentigo agregar la columna de acumulado, en esta
se van sumando las frecuencias de las variables menores (recordar que siempre se ordena de
menor a mayor), así se tiene la gracia de poder ver rápidamente por ejemplo todos los que
miden menos de 1,75m sin necesidad de tomar una calculadora y sumar todas las frecuencias.

Gráficos
--------
Aquí se pueden usar de barra o circulares, pero suelen ser mejores los de barra por que:

+ En el circular se pierde el orden (que con las nominales no teniamos pero ahora si),
  podriamos acordar que partimos arriba y seguimos en sentido horario pero es trabajo
  adicional innecesario y nos carga ese tipo de trabajo.

+ Si tenemos muchos posibles valores para las variables o simplificamos los datos y
  agrupamos por rango, perdiendo información o nos va a quedar un gráfico circular ilegible,
  diferenciar el ancho de una tajada de un 1% y una de un 3% es bastante dificil y hasta los
  colores y su posición relativa a los vecinos alterna la percepción del área de dicha
  tajada. Con un grafico de barras basta con ensanchar el gráfico y adelgazar las barras
  (acá es el alto el que nos da la información no el ancho).

Intervalares (ordenable Y operables)
====================================

Tablas
------
Aquí se pueden usar tablas parecidas a las Ordinales pero mejor usamos lo último de la
tecnología en tablas con el diagrama de tallo y hoja inventado en 1977 por Turkey. Con
esta maravilla de la tecnología se separan los valores por orden y se enlistan las
unidades o sea para:

{ 12, 13, 13, 14, 15, 23, 23, 23, 45, 46, 46, 47 }

queda

1 | 2 3 3 4 5
2 | 3 3 3
4 | 5 6 6 7

y con:

{ 123, 123, 124, 134, 135, 135, 136, 137, 141, 141, 142 }

queda

1 | 2 | 3 3 4
  | 3 | 4 5 5 6 7
  | 4 | 1 1 2

Notese que para hacer la vida más placentera ordenamos los datos antes de hacer cualquier
cosa.

La gracia de este tabulado es que no se pierde información, es fácil de interpretar y si
torcemos nuestras cabezas 90° en el sentido del reloj y voilá tenemos un grafico de
frecuencia agrupado por decenas.

Gráficos
--------
Se pueden mostrar:

**Frecuencias**: cada barra muestra la frecuencia de dado valor en el valor de altura de 1.70m
             va la frecuencia de las personas que miden 1.70.

**Frecuencias acumuladas**: cada barra indica su frecuencia y las frecuencias de los valores
                        más chicos por eso acumulada asi en la altura de 1.70m van todas
                        las personas que miden menos de 1.70m

Y para eso se usan los gráficos:

**Grafico de barras**: se usan para variables discretas y se dibujan con sus barras separadas
entre si.

**Histogramas**: se usan para variables continuas y se dibujan con las barras pegadas a sus
vecinos.

**Grafico de línea**: en vez de hacer rectángulos se tira una línea en el valor dado, cuando
es de frecuencias acumuladas se llama OJIVA, ni idea de porque se llama así. No se suelen
usar si son de frecuencias, se usa el de los anteriores que corresponda.

.. note::
   Si al hacer la tabla se agrupan los datos en distintos rangos ej:

   +--------+------+-------+-------+
   | edad   | freq | largo | freq* |
   +--------+------+-------+-------+
   | 0 - 3  |  30  |   3   |  10   |
   +--------+------+-------+-------+
   | 3 - 5  |  50  |   2   |  25   |
   +--------+------+-------+-------+
   | 5 -10  |  40  |   5   |   8   |
   +--------+------+-------+-------+
   | 10 -30 |  60  |   20  |   3   |
   +--------+------+-------+-------+

   Vemos que en el primer rango 3 - 0 = 3, y el tercero 5 - 10 = 5, lo que se refleja en
   la tercera columna, para ajustar las frecuencias y hacer que los gráficos que salgan de
   aquí se vean representativos se divide la frecuencia por el largo y ESO se grafica.


Estadígrafos y estadisticos
***************************



Probabilidades
##############


Variables aleatorias DISCRETAS
##############################


Variables aleatorias CONTINUAS
##############################





