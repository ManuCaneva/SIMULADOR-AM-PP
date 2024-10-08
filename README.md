# Trabajo Practico Integrador - Sistemas Operativos 2020
## Simulador de Asignación de Memoria y Planificación de proceso

***
### Integrantes:
* Alegre Roth, Facundo Tahiel.
* Azula, Tomas.
* Dajruch, Pablo.
* Caneva, Franco Manuel.

***
Implementar un simulador de asignación de memoria y planificación de procesos según los siguientes
requerimientos.
El simulador deberá brindarla posibilidad de cargar procesos por parte del usuario. Para facilitar la implementación
se permitirán como máximo 10 procesos y la asignación de memoria se realizará con particiones fijas. El esquema
de particiones será el siguiente:
  * 100K destinados al Sistema Operativo
  * 250K para trabajos los más grandes.
  * 150K para trabajos medianos .
  * 50K para trabajos pequeños.

El simulador debe permitir ingreso de nuevos procesos cuando sea posible (manteniendo en grado de
multiprogramación en 5) La política de asignación de memoria será Worst-Fit, por cada proceso se debe leer
desde un archivo el Id de proceso, tamaño del proceso, tiempo de arribo y tiempo de irrupción. La planificación de
CPU será dirigida por un algoritmo Round-Robin con q=3.
El simulador deberá presentar como salida la siguiente información:
  * El estado del procesador (proceso que se encuentra corriendo en ese instante)
  * La tabla de particiones de memoria, la cual deberá contener (Id de partición, dirección de comienzo de
  partición, tamaño de la partición, id de proceso asignado a la partición, fragmentación interna)
  * El estado de la cola de procesos listos.
  * Al finalizar la simulación se deberá presentar un informe estadístico con, tiempo de retorno y espera para cada
  proceso y los respectivos tiempos promedios. También deberá calcular el rendimiento del sistema para la
  simulación (cantidad de trabajos terminados por unidad de tiempo)

***
* Las presentaciones de salida deberán realizarse cada vez que llega un nuevo proceso, se termina un proceso
en ejecución.
* No se permiten corridas ininterrumpidas de simulador, desde que se inicia la simulación hasta que termina el
último proceso.
* El proyecto deberá ser analizado e implementado por equipos de trabajo.
* El equipo deberá realizar el seguimiento del proyecto utilizando la herramienta Trello. El mismo deberá ser
presentado a los docentes cada vez que lo requieran.
* El programa deberá ser implementado, en lenguaje C o Python.
* El simular debe funcionar en una máquina de escritorio, no se permiten simuladores que funcionen on-line.
* No es necesario realizar el simulador con entorno gráfico.
* El simulador será entregado, vía campus virtual, en un paquete que contenga: el programa ejecutable, el
código fuente acompañado de una guía (howto) que indique como ejecutar el simulador.
* Se realizarán presentaciones de avances, antes de la entrega final, las cuales serán consideradas
obligatorias ya que conformarán el coloquio del TPI. Las fechas estipuladas son:
  ◦ 24/09 y 8/10
  ◦ 05/11 y 12/11
* La entrega final será el 22 de noviembre.
* El coloquio de defensa del TPI se llevará a cabo el 29/11 y 03/12 (a confirmar para cada grupo)
