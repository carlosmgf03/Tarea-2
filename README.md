# Tarea 2 – Arquitecturas de Cómputo Emergentes

Este repositorio contiene la investigación de diferentes arquitecturas de cómputo avanzadas: **cuántica, neuromórfica, biológica, heterogénea y de borde**.  
Cada sección incluye definiciones, arquitecturas, historia, ventajas, desventajas.

📌 Primer Punto – Computación Cuántica
¿Qué es?

La computación cuántica es un paradigma de computación que utiliza principios de la mecánica cuántica para procesar información. A diferencia de los bits clásicos (0 o 1), emplea qubits, que pueden estar en superposición (0 y 1 al mismo tiempo).

Arquitectura

Qubits: unidades básicas de información.

Puertas cuánticas: operaciones que modifican el estado de los qubits.

Circuito cuántico: secuencia de puertas cuánticas.

Medida: conversión de estados cuánticos a resultados clásicos.

Hardware físico: superconductores, iones atrapados, fotones, etc.

Historia

1980s: Richard Feynman y David Deutsch plantean la idea de computación cuántica.

1994: Peter Shor desarrolla algoritmo de factorización.

2001: IBM implementa algoritmo de Shor en un computador cuántico experimental.

Actualidad: IBM, Google, Rigetti y D-Wave desarrollan prototipos de uso limitado.

Ventajas

Resolución de problemas intratables para computadoras clásicas.

Criptografía avanzada y simulaciones moleculares.

Desventajas

Alta tasa de errores y decoherencia.

Costos elevados, criogenia y complejidad técnica.

Conceptos clave

Superposición: un qubit puede estar en 0 y 1 simultáneamente.

Entrelazamiento: correlación entre qubits, esencial para velocidad cuántica.

Interferencia cuántica: cancelación o refuerzo de probabilidades.

Medición probabilística: el resultado no es determinista, sino basado en probabilidades.

Decoherencia: pérdida de información cuántica por interacción con el ambiente.

Comunicación cuántica: transmisión segura mediante entrelazamiento.

📌 Segundo Punto – Computación Neuromórfica
¿Qué es?

Es un tipo de computación inspirada en el cerebro humano, que busca emular las redes neuronales biológicas mediante chips especializados.

Arquitectura

Neuronas artificiales: nodos que procesan señales.

Sinapsis electrónicas: conexiones que transmiten y adaptan señales.

Eventos asincrónicos: procesamiento solo cuando ocurre un estímulo.

Funcionamiento

Imita la dinámica del sistema nervioso, procesando información de manera paralela, masiva y eficiente en energía.

Hardware

IBM TrueNorth: chip neuromórfico con 1 millón de neuronas artificiales.

Intel Loihi: chip con aprendizaje autónomo en hardware.

SpiNNaker (Manchester University): sistema con millones de núcleos de procesamiento neuromórfico.

Tipos de computación neuromórfica

Basada en hardware digital (Loihi, TrueNorth).

Basada en dispositivos analógicos (memristores, sinapsis electrónicas).

Simulaciones de gran escala (SpiNNaker).

Ventajas

Bajo consumo de energía.

Alta eficiencia en tareas cognitivas (reconocimiento de voz, imágenes).

Desventajas

Tecnologías aún inmaduras.

Dificultad de programación.

Falta de estandarización.

📌 Tercer Punto – Computación Biológica
¿Qué es?

La computación biológica utiliza sistemas vivos (como ADN, proteínas o células) para realizar cálculos.

Arquitectura

ADN como soporte de información (bits reemplazados por nucleótidos).

Reacciones bioquímicas que representan operaciones lógicas.

Sistemas celulares modificados como procesadores biológicos.

Tipos

Computación basada en ADN: utiliza cadenas de ADN para resolver problemas matemáticos (ej. problemas de grafos).

Computación con proteínas y enzimas: emplea interacciones químicas.

Computación celular: células programadas para realizar tareas (biología sintética).

Hitos

1994: Leonard Adleman usa ADN para resolver un problema de grafos.

2002: creación de “computadoras moleculares” basadas en enzimas.

Hoy: biología sintética aplicada a biosensores y medicina personalizada.

Ventajas

Alta densidad de almacenamiento.

Computación paralela masiva.

Desventajas

Velocidad de cálculo baja en comparación con hardware electrónico.

Complejidad biotecnológica.

📌 Cuarto Punto – Computación Heterogénea
¿Qué es?

Es un enfoque donde se combinan distintos tipos de procesadores (CPU, GPU, FPGA, ASIC, etc.) para aprovechar lo mejor de cada uno.

Historia

Década de 2000: auge del uso de GPU para cómputo general.

Hoy: arquitecturas en supercomputadores, inteligencia artificial y móviles.

Ventajas

Mayor eficiencia y rendimiento.

Optimización según tipo de tarea.

Escalabilidad en supercomputación.

Desventajas

Complejidad de programación.

Mayor costo y consumo energético.

Dificultades de portabilidad.

📌 Quinto Punto – Computación en el Borde (Edge Computing)
¿Qué es?

Es un paradigma donde el procesamiento de datos se realiza cerca de la fuente de generación (sensores, dispositivos IoT) en lugar de enviarlos a la nube.

Historia

Surge con la expansión de IoT y 5G (2010 en adelante).

Adoptado en aplicaciones críticas (autos autónomos, salud conectada).

Ventajas

Baja latencia.

Mayor privacidad (los datos no siempre van a la nube).

Optimización del ancho de banda.

Desventajas

Requiere infraestructura distribuida.

Limitación en capacidad de cómputo local.

Mantenimiento más complejo.
