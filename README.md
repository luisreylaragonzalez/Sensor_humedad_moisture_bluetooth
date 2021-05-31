# Sensor_humedad_moisture_bluetooth
Proyecto de Sensor de humedad moisture + bluetooth

En este proyecto se utiliza: Esp32 + sensor capacitative Soil Moisture Sensor 2.0 + bluetooth

Se documenta codigo 
Se adjuntan imágenes
El sensor emite el valor de 3632 cuando está seco
El sensor emite el valor de 1354 cuando se encuentra dentro de agua
Se saca el porcentaje tomando en cuenta los valores anteriores

El código emite la cadena string completa cuando se utiliza el método SerialBT.println
En caso de utilizar el metodo "SerialBT.write" se tuvo problemas con las cadenas.

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
      
