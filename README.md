# Modelado de Sistemas Fisiológicos. Práctica 2: Sistema respiratorio [Rivera22210427]

## Autor
Mariana Rivera Peñuelas

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l22210427@tectijuana.edu.mx

## Objetivos general
Diseñar un controlador que permita formular un protocolo de tratamiento para que un paciente con efisema (caso) presente la misma presion alveolar que un individuo 
sano (control).

## Actividades
1. Calcular analiticamente la funcion de transferencia del sistema pulmonar.
2. Establecer el modelo de ecuaciones integro-diferenciales.
3. Determinar el error en estado estacionario y la estabilidad del sistema en lazo abierto.
4. Construir el diagrama de bloques como se indica en la Figura 5.4.
5. Diseñar el controlador con Simulink utilizando el bloque PID Controller y la herramienta Tune para sintonizar los valores Ûptimos para cada una de las ganancias kP, kI y kD.
6. Ilustrar el cambio del flujo de aire y el volumen tidal en respuesta a las siguientes formas de onda de presion sinusoidal en la apertura de la via aerea [Pao(t)]:
a) 15 respiraciones por minuto con una amplitud (A) de 2.5 cmH2O, es decir, respiracion normal
