# Simulación virtual de contagio adaptado al COVID-19

Este estudio tiene la finalidad de presentar los resultados de una simulación virtual sobre un modelo de contagio adaptado al COVID-19. Concretamente se han simulado dos escenarios de contagio distintos:

En el primero de ellos muestra una situación normal, sin medidas de prevención en cuanto a la libre circulación de personas. 

En el segundo se intenta reflejar una situación con estado de alarma, en este caso se reduce la circulación de personas y por lo tanto las exposiciones con los individuos de su entorno. 

Descripción del **algoritmo** y parámetros utilizados:

1. Creación de una población virtual (10 millones de habitantes).
2. Generación de relaciones entre los individuos, serán los canales que utilizará el virus para propagarse. En el primero de los escenarios las relaciones entre individuos serán de 1 a 6 relaciones y el segundo de 0 a 4 relaciones diarias.
3. Se contagia al azar a 3 individuos.
4. Se simulará día a día, en cada día los individuos contagiados podrán transferir el virus con una probabilidad del 10% a aquellos con los que se hayan relacionado.
5. Una vez contagiado un individuo entra en un periodo de incubación de dos días. Durante la incubación el individuo no podrá contagiar. A los 12 días de contagiarse cada individuo para curarse con un 95% de probabilidad o fallecer. Los individuos que superen la enfermedad no pueden volver a ser contagiados.
6. El algoritmo para cuanto ningún miembro de la población está contagiado.
