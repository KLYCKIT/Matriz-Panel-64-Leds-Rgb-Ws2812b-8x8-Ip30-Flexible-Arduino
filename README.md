# Matriz-Panel-256-Leds-Rgb-Ws2812b-8x32-Ip30-Flexible-Arduino

Matriz RGB de Neopixel de 8x32 con 256 LEDs tipo 5050 en PCB flexible. Cada LED es controlado individualmente mediante comunicación serial en cascada, por lo que solo se necesita un GPIO de un Microcontrolador como Arduino o Raspberry, logrando así control total de la matriz con color de 24 bit por cada LED. El conexionado de la matriz es simple. Dispone de 2 puertos de 3 pines (uno de entrada y otro de salida), al de entrada se le conecta 5V, GND y el pin de datos. Cada LED puede llegar a consumir hasta 50mA (en blanco puro), por lo que el total del panel puede llegar a 12.8 Amperes, siendo aconsejable utilizar una fuente de alimentación adecuada. Debido a el control serial, es posible unir varias matrices para obtener un panel aún mayor.

Características:

• LEDs 256 RGB NeoPixel 5050 WS2812
• Tensión de Alimentación: 5 VDC

DIAGRAMA DE CONEXION:



![image](https://github.com/KLYCKIT/Matriz-Panel-256-Leds-Rgb-Ws2812b-8x32-Ip30-Flexible-Arduino/assets/83427440/4529cc64-6fea-4f32-81dd-cd11a95f2393)



LIBRERIAS

NEOPIXEL
https://github.com/adafruit/Adafruit_NeoPixel

NEOMATRIX
https://github.com/adafruit/Adafruit_NeoMatrix

FASTLED
https://github.com/FastLED/FastLED

Uso basico de la libreria FASTLED
https://github.com/FastLED/FastLED/wiki/Basic-usage
