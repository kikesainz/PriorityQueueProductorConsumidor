# PriorityQueueProductorConsumidor
Programa que implementa dos hilos de forma muy sencilla: un productor y un consumidor.

Ambos trabajan sobre una PriorityQueue la cual le da más prioridad a la edad.

El hilo productor producirá una persona aleatoria** cada X segundos (nombre y edad) y se dormirá, se esperará si la cola sobrepasa X personas (las cantidades y tiempos están parametrizadas en un fichero de constantes)

El hilo consumidor consumirá la persona de mayor prioridad (la quita de la cola) y se esperará si la cola está vacía.

Podéis bajaros el programa, ver cómo está hecho y cambiarle cosas para ver cómo se comporta.

**Para la generación de los nombres de personas he utilizado una librería que se llama java faker**, el id lo he generado de forma aleatoria.

Proyecto de javafaker: https://github.com/DiUS/java-faker

Jars necesarios (con todas sus dependencias) para el uso de javafaker: https://jar-download.com/artifacts/com.github.javafaker
