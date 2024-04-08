
## Para usar el codigo de matlab
* Solo descarga el archivo llamado app10.
* Una vez que esté en tu computadora, abre matlabe
* Desde matlab busca el archivo que descargaste y trata de abrirlo. Eso basta para que se abra la aplicacion y puedas usarla

## Para el codigo del sensor
* Asegurate de tener configurado el ArduinoIDE para usar ESP32.
    * Para ello pega los siguientes links en la parte de: File > Preferences > Additional boards manager URLs
        http://arduino.esp8266.com/stable/package_esp8266com_index.json
      
        https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

* Despues abre el archivo .ino que se llama i2c-sensorCode, desde el ArduinoIDE.
* Subelo a la esp32 asegurandote de seleccionar la placa ESP32 Dev Module y el puerto serial correcto.
