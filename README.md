# Simulación virtual de contagio adaptado al COVID-19

Este estudio pretende mostrar una demostración práctica (Simulación Virtual) sobre dos escenarios de contagio distintos: 

En el primero de ellos muestra una situación normal. Con una media de 1 a 6 contactos diarios entre personas. 

En el segundo se intenta reflejar una situación con estado de alarma. Con una media de 0 a 4 contactos diarios entre personas. 

Los pasos del **algoritmo** son: 

1. Creación de una población virtual (10 millones de habitantes) 
2. Generación de relaciones entre los individuos, serán los canales que utilizará el virus para propagarse. 
3. Se infectará al azar a 3 individuos 
4. Se simulará día a día, en cada día los individuos contagiados podrán trasferir el virus con una determinada probabilidad a aquellos con los que se hayan relacionado. 
5. Una vez contagiado un individuo entra en un periodo de incubación de dos días. Durante la incubación el individuo no podrá contagiar. A los 12 días de contagiarse cada individuo para curarse con un 95% de probabilidad o fallecer. Los individuos que superén la enfermedad no pueden volver a ser contagiados.
