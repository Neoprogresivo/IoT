# iot

Repositorio con proyectos para IOT

Pasos para poder programar ESP32 C3 (y otros) con Arduino IDE

1.- Descargar e instalar la última versión de Arduino IDE de acuerdo a tu sistema operativo

2.- Correr Arduino IDE

3.- Agregar el paquete de ESP32 al Arduino IDE
Para ello se debe realizar lo siguiente:

Navigate to File > Preferences, and fill "Additional Boards Manager URLs" with the url below: 
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

Navigate to Tools > Board > Boards Manager..., type the keyword "esp32" in the search box, 
select the latest version of esp32, and install it.

4.- Selecciona tu placa y puerto

Placa

Navigate to Tools > Board > ESP32 Arduino and select "XIAO_ESP32C3". 

The list of board is a little long and you need to roll to the buttom to reach it.

Puerto

Navigate to Tools > Port and select the serial port name of the connected XIAO ESP32C3. 

This is likely to be COM3 or higher (COM1 and COM2 are usually reserved for hardware serial ports).
