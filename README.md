# PL-SQL PRACTICA = AUTOBUS 
Hare la una practica de PL/SQL de una compañia de autobuses, donde pondre el SCRIPT y su solución (HAY MÁS DE UNA)

# ENUNCIADO

Ejercicio 1
Realiza los módulos de programación necesarios para mostrar el panel de información de
salidas y llegadas de una estación de autobuses. La aplicación recibirá como parámetro el
nombre de la ciudad donde se ubica la estación y mostrará un listado con las cuatro
últimas salidas y las cuatro últimas llegadas desde o hacia esa ciudad.
En caso de que no hayan llegadas a esa ciudad no se mostrará el listado de llegadas. En
caso de que no hayan salidas desde esa ciudad no se mostrará el listado de salidas. Si
hay menos de cuatro salidas o llegadas, se mostrarán las que hayan. Si la ciudad no existe
se levantará una excepción informando del hecho.
El formato será el siguiente:
Salidas
Anden Destino HoraSalida HoraEstimadaLlegada MatrículaBus
…
...
…
Llegadas
Anden Origen HoraEstimadaLlegada MatrículaBus
…
...
…
Para resolver dicho ejercicio es conveniente:
• Crear una función que devuelva la hora de llegada de un viaje a partir de la fecha y
hora de salida y la duración en minutos de la ruta.
• Crear un procedimiento al que se le pase el código de una ruta y devuelva el
origen, destino y duración en minutos de la misma.
Ejercicio 2
Realiza los módulos de programación necesarios para que desde el servicio de atención
telefónica de la compañía, cuando un cliente quiera reservar un billete para ir de un origen
a un destino en un día determinado, la telefonista pueda informarle de todos los posibles
viajes que la compañía le ofrece (descartando los que no tengan ya plazas disponibles),
incluyendo hora de salida, hora de llegada estimada y precio del billete.
Deben contemplarse las siguientes excepciones: Ciudad Origen Inexistente, Ciudad
Destino Inexistente, Ruta no Operada ese día, Ruta sin billetes disponibles ese día.
Nota: Se considera fundamental la división adecuada en subprogramas cuando resulte
procedente y la correcta legibilidad del código, así como la minimización del número de
consultas realizadas al servidor.
