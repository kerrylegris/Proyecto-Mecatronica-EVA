# Diseño
## Inspiración
Para cumplir con el requerimiento del proyecto de implementar una estética futurista, el diseño exterior del robot toma como inspiración directa al personaje EVA (Extraterrestrial Vegetation Evaluator) de la película de animación WALL-E.

La justificación de esta elección geométrica y visual para representar el "futuro" se sostiene en los siguientes puntos:

Minimalismo de Alta Tecnología: La ciencia ficción y el diseño industrial moderno asocian el futurismo con la limpieza visual. EVA carece de uniones visibles, engranajes expuestos o bordes afilados. Su geometría está basada en curvas continuas, superficies lisas y un contraste marcado entre el blanco puro y la pantalla negra de su rostro, emulando la sofisticación de los dispositivos tecnológicos.

El Movimiento: El concepto original de EVA es el de una sonda que levita o flota suavemente. Aunque el prototipo mecatrónico utiliza ruedas, la dinámica misma de un robot autobalancín —que constantemente ajusta su centro de masa para mantenerse erguido sobre un solo eje— genera un movimiento fluido que imita conceptualmente la sensación de "flotabilidad" o anti-gravedad, alineándose a la perfección con la percepción de un vehículo futurista.
![Inspiración: Personaje EVA](./Multimedia/eva.jpg)
## Iteraciones
El desarrollo físico del robot fue un proceso iterativo, motivado por la necesidad de conciliar la compleja geometría de EVA con los estrictos requerimientos dinámicos y de distribución de masa de un péndulo invertido.
Iteración 1: Diseño preliminar con placa vertical
El enfoque: El primer diseño computacional en Fusion 360 buscó integrar la carcasa estética de EVA con una única placa vertical dispuesta en el interior, la cual serviría como soporte central para ensamblar todos los componentes electrónicos y mecánicos.
El problema: Al evaluar este ensamble preliminar, se evidenció que la placa vertical concentraba el peso de manera subóptima y limitaba severamente la flexibilidad para distribuir la masa. Además, dificultaba la accesibilidad para el cableado y el ajuste de los componentes, comprometiendo la viabilidad del balanceo.
##Diseño final 
Iteración 2: Transición al chasis horizontal por niveles
La solución: Se descartó la placa vertical en favor de un chasis interno estructurado en pisos horizontales (mediante placas de acrílico cortadas en láser y separadores cilíndricos).
El impacto: Esta nueva arquitectura permitió independizar el sistema estructural de la carcasa externa. Al tener niveles, se logró bajar drásticamente el centro de gravedad ubicando la batería y los motores en la base, lo cual fue fundamental para compensar la alta inercia generada por el apéndice superior impreso en 3D (la cabeza de EVA).


