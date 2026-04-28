# Procesos Estocásticos

Este repositorio recoge las prácticas realizadas para la asignatura de **Procesos Estocásticos**. A lo largo del curso, iré subiendo distintos trabajos prácticos centrados en la simulación y visualización de modelos probabilísticos.

Veamos las diferentes prácticas que incluye:

### 1. Visualizaciones de diferentes gráficas de Paseos Aleatorios Simples.
En esta práctica he implementado una función llamada `simular_PAS` para simular paseos aleatorios simples (PAS) generando distintas trayectorias a partir de pasos +1 y -1 con probabilidad $p$ dada. A partir de esta función he realizado 3 tipos de visualizaciones distintas:

La primera de ellas, llamada `graficas_pas_1` en la que represento diferentes trayectorias del PAS con distintos valores de $p$.

La segunda visualización, llamada `graficas_pas_2` en la que utilizo lo ejecutado en la primera visualización añadiéndole la media teórica y las bandas de ±1σ y ±2σ, con la que compruebo que las trayectorias se distribuyen alrededor de la media, ya que la mayoría están contenidas en estas bandas.

Y la tercera visualización, llamada `graficas_pas_3` en la que comparo la media empírica con la media teórica, comprobando que conforme mayor es el número de trayectorias que usamos, más converge la media empírica hacia la media teórica. 

### 2. Simulaciones de Procesos Gaussianos (GPs)
En esta práctica simularemos distintos Procesos Gaussianos implementando distintas funciones como `simular_GP_RBF`, `simular_GP_periodic` y `simular_GP_DPKpoly`, utilizando los contenidos teóricos vistos en clase. De esta manera obtendremos diferentes gráficas tras visualizar dichas funciones con distintos parámetros. 

