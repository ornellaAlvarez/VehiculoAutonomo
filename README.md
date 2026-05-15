# VehiculoAutonomo
El objetivo fue diseñar un Sistema Embebido que controle el sentido de giro de dos motores D.C para darle movimiento a un auto robot. Se desea que avance en línea recta mientras no detecte la presencia de un obstáculo, información que medirá  a través de un sensor de proximidad. En caso de encontrar un obstáculo deberá realizar un giro cambiando la dirección.

El sistema deberá tener las siguientes características:
  * Si la distancia recibida por el sensor es mayor a 15 cm, los dos motores deben avanzar hacia adelante. 
  * Si la distancia recibida por el sensor es menor o igual a 15 cm, uno de los motores debe girar hacia atrás y el otro hacia adelante. 

Este proyecto consistió en la implementación de un sistema embebido, capaz de detectar y esquivar obstáculos gracias a su sensor de proximidad y sus 4 motores D.C (Corriente continua). Se buscó integrar teoría y práctica en el diseño del sistema, aplicando el control de los motores a través de un puente H y la programación del microcontrolador Arduino Uno (con el entorno de Arduino IDE). 

Al integrar cada uno de los componentes, se buscó un comportamiento casi autónomo en respuesta a los estímulos del entorno.
