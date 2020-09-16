# Simulación virtual de contagio adaptada al COVID-19

Este estudio tiene la finalidad de presentar los resultados de una simulación virtual sobre un modelo de contagio adaptada al COVID-19. Se han simulado varios escenarios:

- En el primero de ellos muestra una situación normal, sin medidas de prevención.

- En el segundo se intenta reflejar una situación con reducción en la libre circulación de personas y por lo tanto las exposiciones con los individuos de su entorno. 

- En el tercer escenario se simula el uso de mascarilla, disminuyendo la posibilidad de contagio entre los individuos.

- En el último escenario vamos a simular una vacunación del 40% de la población, aumentando el porcentaje inmunes hasta el 60%.

Descripción del **algoritmo** y parámetros utilizados:

1. Creación de una población virtual (10 millones de habitantes).
2. Generación de relaciones entre los individuos, serán los canales que utilizará el virus para propagarse. En el primero de los escenarios las relaciones entre individuos serán de 1 a 15 relaciones y el segundo de 1 a 5 relaciones diarias.
3. Se contagia al azar a 3 individuos.
4. Se simulará día a día, en cada día los individuos contagiados podrán transferir el virus con una probabilidad del 10% a aquellos con los que se hayan relacionado. 
5. Una vez contagiado un individuo entra en un periodo de incubación de dos días. Durante la incubación el individuo no podrá contagiar. A los 15 días de contagiarse cada individuo para curarse con un 90% de probabilidad o fallecer. Los individuos que superen la enfermedad no pueden volver a ser contagiados.
6. El algoritmo detiene la simulación cuanto ningún miembro de la población está contagiado.


