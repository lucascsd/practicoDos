Cohorte 15va
# Programación de microprocesadores
## Practica 2
### Resumen
Modularizar en funciones, archivos y capas, un proyecto de controlador de leds. Implementar un programa que controle la lógica de funcionamiento de una secuencia arbitraria de LEDs de la EDU-CIAA-NXP.
#### Condiciones de funcionamiento
###### Dependencias externas:
 - sAPI.h;
 - Usar delay no bloqueantes;

#### Modularización
![](https://github.com/lucascsd/practicoDos/blob/main/image/Capas%20Ejercicio%202.svg)

###### Funciones de modularización
| File name | hearders                    |
| ------------- | ------------------------------ |
| [ejercicio2.c](https://github.com/martinjrios/Practica2/blob/main/src/ejercicio2.c)     | `ejercicio2.h`     |
| `secuencia.c`      | `secuencia.h`     |
| `leds.c`      | `leds.h`     |
| `teclas.c`      | `teclas.h`     |


