# Arquitectura 2025 II P2-1

## Objetivo

Familiarizar al estudiante con la sintaxis del lenguaje ensamblador MIPS32 y su ejecución en el entorno MARS, resolviendo problemas clásicos de programación, prestando especial atención a la gestión de registros, llamadas a funciones, estructuras de control, camino de datos, manejo de la pila y configuración/utilización del ambiente de trabajo.

## Actividades

1.  Implementar en MIPS32 el Algoritmo de Ordenamiento Quicksort
2.  Implementar en MIPS32 un Algoritmo de Ordenamiento de su preferencia

## Informe

1.  ¿Qué diferencias existen entre registros temporales ($t0–$t9) y registros guardados ($s0–$s7) y cómo se aplicó esta distinción en la práctica?
2.  ¿Qué diferencias existen entre los registros $a0–$a3, $v0–$v1, $ra y cómo se aplicó esta distinción en la práctica?
3.  ¿Cómo afecta el uso de registros frente a memoria en el rendimiento de los algoritmos de ordenamiento implementados?
4.  ¿Qué impacto tiene el uso de estructuras de control (bucles anidados, saltos) en la eficiencia de los algoritmos en MIPS32?
5.  ¿Cuáles son las diferencias de complejidad computacional entre el algoritmo Quicksort y el algoritmo alternativo? ¿Qué implicaciones tiene esto para la implementación en un entorno MIPS32?
6.  ¿Cuáles son las fases del ciclo de ejecución de instrucciones en la arquitectura MIPS32 (camino de datos)? ¿En qué consisten?
7.  ¿Qué tipo de instrucciones se usaron predominantemente en la práctica (R, I, J) y por qué?
8.  ¿Cómo se ve afectado el rendimiento si se abusa del uso de instrucciones de salto (j, beq, bne) en lugar de usar estructuras lineales?
9.  ¿Qué ventajas ofrece el modelo RISC de MIPS en la implementación de algoritmos básicos como los de ordenamiento?
10. ¿Cómo se usó el modo de ejecución paso a paso (Step, Step Into) en MARS para verificar la correcta ejecución del algoritmo?
11. ¿Qué herramienta de MARS fue más útil para observar el contenido de los registros y detectar errores lógicos?
12. ¿Cómo puede visualizarse en MARS el camino de datos para una instrucción tipo R? (por ejemplo: add)
13. ¿Cómo puede visualizarse en MARS el camino de datos para una instrucción tipo I? (por ejemplo: lw)
14. Justificar la elección del algoritmo alternativo
15. Análisis y Discusión de los Resultados

## Entrega

1.  Práctica de Laboratorio Individual o en Pareja.
2.  Se deben enviar al correo los archivos .asm junto con el documento (.tex y .pdf) con las respuestas.
3.  Se debe garantizar la correcta ejecución de los archivos .asm y visualización del documento (.tex y .pdf) con las respuestas en la fecha prevista para la defensa.
4.  La defensa presencial de cada práctica de laboratorio es obligatoria.
5.  La fecha máxima de entrega y fecha de defensa es el día martes 24 de febrero de 2026 en las instalaciones del laboratorio.
