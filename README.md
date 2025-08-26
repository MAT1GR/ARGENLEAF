# ArgenLeaf: Iluminación Inteligente DIY con Arduino 💡

¡Una versión DIY de los paneles de luz inteligentes al estilo Nanoleaf, creada con Arduino!

## Descripción

ArgenLeaf es un proyecto escolar que te permite construir tus propios paneles de luz modulares y personalizables. Conecta y organiza los paneles de diferentes formas, controla los colores, efectos y anímate a experimentar con nuevos modos de iluminación.

Este proyecto fue una excelente oportunidad para aplicar y mejorar nuestras habilidades en electrónica, programación y diseño, además de fomentar el trabajo en equipo para crear una solución creativa e innovadora.

## Características

* **Modular y personalizable**: Crea la forma que más te guste conectando los paneles.
* **Control total con Arduino**: El corazón del proyecto es un Arduino que gestiona todos los efectos y colores.
* **Fácilmente programable**: El código está diseñado para ser entendido y modificado, permitiendo añadir nuevas funcionalidades.
* **Múltiples modos de iluminación**:
    * **Color Fijo**: Establece un color estático para todos los LEDs.
    * **RGB**: Un ciclo que alterna entre los colores primarios (Rojo, Verde, Azul).
    * **Fade**: Una transición suave y continua a través de una paleta de 20 colores predefinidos.
    * **Bouncing Rainbow**: Un efecto dinámico donde un arcoíris de 7 colores "rebota" de un extremo a otro de la tira de LEDs.

## Componentes y Librerías

* **Hardware**: Arduino, Tira de LEDs WS2812B (NeoPixel).
* **Software**:
    * [`Adafruit NeoPixel`](https://github.com/adafruit/Adafruit_NeoPixel)
    * `SoftwareSerial` para la comunicación.

## Instalación y Uso

1.  **Conexión**:
    * Conecta el pin de datos de la tira de LEDs al pin digital 6 del Arduino.
    * Asegúrate de alimentar correctamente la tira de LEDs y el Arduino.
2.  **Código**:
    * Abre el archivo `ARGENLEAF.ino` en el IDE de Arduino.
    * Ajusta la variable `NUMPIXELS` según la cantidad de LEDs de tu tira.
    * Sube el código a tu placa Arduino.
3.  **Control**:
    * El sistema se controla enviando comandos a través del puerto serie. Puedes enviar valores RGB en formato `"R,G,B"` para establecer un color específico, o los caracteres `'a'`, `'b'`, o `'c'` para activar los diferentes modos predefinidos.

¡Esperamos que disfrutes de este proyecto tanto como nosotros al crearlo!
