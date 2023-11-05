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



CONTROLAR LA MATRIZ CON WLED

WLED es un firmware para dispositivos basados ​​en ESP32 que le permite controlar fácilmente los LED RGB (como NeoPixels) a través de WiFi.

Esto puede ser realmente útil porque significa que no es necesario tener acceso físico al controlador para cambiar lo que se está reproduciendo. En este artículo, conectaremos una matriz de 16 × 16 a una placa ESP32 (la Smôl de SparkFun), la cargaremos en WLED y luego la controlaremos desde otra computadora en la red reproduciendo GIF animados.

WLED tiene muchas funciones y puede usarse para crear todo tipo de efectos de iluminación que lucen maravillosos, pero que no usaremos en este tutorial de hoy. Sin embargo, si está instalando iluminación LED, vale la pena navegar por el sitio web del proyecto , [kno.wled.ge](https://kno.wled.ge/). Una de las características realmente excelentes es lo fácil que es ponerlo en marcha. No necesita ninguna experiencia en programación ni ningún entorno de programación: simplemente apunte su navegador web a: [install.wled.me](https://install.wled.me/) . Si conecta su dispositivo ESP32 al puerto USB de su computadora y hace clic en Instalar, debería terminar con WLED instalado en su dispositivo.
