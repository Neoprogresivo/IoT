# iot

Repositorio con proyectos para IOT

Pasos para poder programar ESP32 C3 (y otros) con Arduino IDE

1.- Descargar e instalar la última versión de Arduino IDE de acuerdo a tu sistema operativo

2.- Correr Arduino IDE

3.- Agregar el paquete de ESP32 al Arduino IDE
Para ello se debe realizar lo siguiente:

Ir a File > Preferences, y completar en "Additional Boards Manager URLs" con la siguiente url: 

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

Después ir a Tools > Board > Boards Manager..., escribe "esp32" en el cuadro de búsqueda, 
selecciona la última versión de esp32 y haz click en instalar. 

4.- Selecciona tu placa y puerto

Placa

Ir a  Tools > Board > ESP32 Arduino y seleccionar "XIAO_ESP32C3" (o el ESP32 que corresponda). 

La lista de placas es larga y es posible que sea necesario bajar para encontrarla.

Puerto

Ir a Tools > Port y seleccionar el nombre del puerto serial al que está conectada XIAO ESP32C3. 

Es común que el puerto por defecto sea el COM3 o uno superior (ya que el COM1 y el COM2 por lo general están reservador para los puertos seriales de tu dispositivo).
