# Proyecto-Mecatronica 4250-EVA
## Integrantes
* Agustín Ketterer
* Isabella Silva
* Katalyna Tapia
* Joaquín Zuñiga
## Profesor
* Harold Valenzuela
## Auxiliar
* Fernando Navarrete
## Ayudantes
* Valentina Abarca
* Emilia Gutiérrez
# Índice de contenidos
* [Descripción](#descripción)
* [Objetivos](#objetivos)
* [Listado de Materiales](./Listado%20de%20materiales/README.md#listado%20de%20materiales)
* [Diseño]
* [Electrónica]
* [Software y lógica]
* [Archivos CAD]
* [Códigos]
* [Multimedia]
  
# Descripción
El presente repositorio contiene la documentación, códigos y modelos 3D correspondientes al desarrollo del Robot Autobalancín "EVA".

El prototipo consiste en un péndulo invertido sobre dos ruedas capaz de mantener su verticalidad de forma autónoma frente a perturbaciones. A diferencia de los modelos clásicos, este proyecto destaca por incorporar un diseño estético basado en el personaje EVA de la película WALL-E, que responde a la solicitud de aplicar una estética futurista a nuestra propuesta, modelado íntegramente en Fusion 360. Para compatibilizar esta geometría con las exigencias dinámicas del equilibrio, se desarrolló una arquitectura interna estructurada en niveles que optimiza el centro de masa y permite un enrutamiento limpio del hardware.

A nivel de sistema, el robot es contorlado por una placa Arduino Uno, la cual procesa en tiempo real los datos de inclinación y aceleración capturados por un sensor inercial MPU-6050. Mediante la ejecución de un algoritmo de control PID ajustado experimentalmente, el microcontrolador gestiona la respuesta de los actuadores (motores DC), demostrando la aplicación práctica de principios de dinámica de cuerpos rígidos y sistemas de control en lazo cerrado.

Características principales:

* Modelado CAD: Diseño en Fusion 360 de la carcasa externa y el chasis interno por niveles.

* Fabricación: Combinación de impresión 3D (PLA) para la estética y corte láser (acrílico) para el chasis estructural.

* Electrónica: Integración de Arduino Uno, sensor MPU-6050, drivers de potencia y motores reductores.

* Control: Sistema de auto-balanceo mediante algoritmo PID en C++.
# Objetivos 
El objetivo principal de este proyecto es el diseño mecatrónico y la construcción de un robot autobalancín funcional inspirado en la estética de EVA (WALL-E). Lo central del desafío consiste en implementar un controlador PID capaz de mantener el equilibrio dinámico del sistema, compensando la inercia generada por la masa superior de su estructura.

Para lograr este objetivo, se integrarán componentes electrónicos esenciales utilizando un microcontrolador Arduino UNO como unidad central de procesamiento. Este gestionará la lógica de control programada en C++ y la lectura continua de datos del sensor inercial MPU-6050 (encargado de medir los ángulos de inclinación) para comandar los actuadores (motores DC acoplados a las ruedas). Además, el proyecto incluye el diseño de una estética original y atractiva, estructurando el modelo CAD en niveles internos para lograr la geometría fluida del personaje sin comprometer la viabilidad mecánica del péndulo invertido.

Es importante definir que el alcance del proyecto se centra en la integración exitosa del hardware y en la demostración de un sistema de autobalanceo. Por lo tanto, aunque el prototipo físico deba lidiar con las complejidades de un centro de masa elevado debido a su diseño asimétrico, el objetivo principal radica en la aplicación práctica de la teoría de control para superar este reto.
