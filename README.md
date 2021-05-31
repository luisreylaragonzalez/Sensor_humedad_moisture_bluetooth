# Sensor_humedad_moisture_bluetooth
Proyecto de Sensor de humedad moisture + bluetooth
<H1>
En este proyecto se utiliza: Esp32 + sensor capacitative Soil Moisture Sensor 2.0 + bluetooth
  </H1>
<p>
Se documenta codigo <p>
Se adjuntan imágenes<p>
El sensor emite el valor de 3632 cuando está seco<p>
El sensor emite el valor de 1354 cuando se encuentra dentro de agua<p>
Se saca el porcentaje tomando en cuenta los valores anteriores<p>

El código emite la cadena string completa cuando se utiliza el método SerialBT.println<p>
En caso de utilizar el metodo "SerialBT.write" se tuvo problemas con las cadenas.<p>

Se descarga la aplicación de Google Store "Bluetooth Terminal" y se instala en el movil <p>
Se tiene que vincular el movil con el Bueltooth del esp32<p>
Después de vincularlo, en la aplicación se busca el id_del_Bluetooth y se connecta
Solo se debe enviar un caracter del movil al esp32 para recibir los datos que envía el sensor.


<p>
  Videos de youtube relacionados y tomados como ejemplo: <p>
https://www.youtube.com/watch?v=nwuxZL9ktRk&t=135s
    <p>
https://randomnerdtutorials.com/esp32-bluetooth-classic-arduino-ide/
      <p>
http://www.esp32learning.com/code/esp32-and-soil-moisture-sensor-example.php
        <p>
