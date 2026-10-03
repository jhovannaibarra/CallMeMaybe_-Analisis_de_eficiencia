# CallMeMaybe_Analisis_de_eficiencia
CallMeMaybe — Análisis de eficiencia de operadores 
Contexto y problema.

CallMeMaybe es un proyecto de análisis de datos para una empresa de telecomunicaciones. El objetivo fue analizar el desempeño de los operadores e identificar aquellos que presentaban indicadores asociados con una posible ineficiencia.

La empresa contaba con información sobre llamadas entrantes y salientes, llamadas perdidas y tiempos de espera. El reto consistía en transformar estos datos en indicadores que permitieran comparar el desempeño de los operadores y detectar posibles casos de ineficiencia.

Mi contribución.
Me encargué del proceso completo de análisis, desde la preparación y limpieza de los datos hasta la identificación de operadores potencialmente ineficaces y la validación estadística de los resultados.

Trabajé con dos conjuntos principales de datos: registros de llamadas y datos de clientes.

Proceso y decisiones:
* Revisé la estructura y calidad de los datos antes de comenzar el análisis.
* Identifiqué y eliminé 4,900 registros duplicados, trabajando finalmente con 49,002 registros.
* Analicé variables relacionadas con llamadas perdidas, tiempo de espera y llamadas salientes.
* Definí criterios para identificar operadores potencialmente ineficaces.
* Utilicé medidas como la mediana para comparar el comportamiento de diferentes grupos.
* Apliqué la prueba estadística de Mann–Whitney para comprobar si las diferencias entre los grupos eran estadísticamente significativas.
* Clasifiqué a los operadores según la cantidad de indicadores de ineficiencia que cumplían.

Resultado y aprendizaje.

El análisis permitió identificar 10 operadores potencialmente ineficaces entre los operadores evaluados.

Los resultados mostraron diferencias estadísticamente significativas entre los grupos en tasa de llamadas perdidas, tiempo de espera y volumen de llamadas salientes.

Este proyecto me permitió fortalecer mis habilidades en limpieza de datos, creación de métricas, análisis exploratorio y validación estadística, además de aprender a convertir indicadores operativos en criterios de análisis.

Herramientas:
Python · Pandas · NumPy · Matplotlib · Seaborn · Statistical Analysis · Mann–Whitney U Test
