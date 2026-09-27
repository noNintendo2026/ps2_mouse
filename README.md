# ps2_mouse
Repositorio grupo de ps2_mouse

## Conexiones fisicas del dispositivo

El ps/2 del mouse consta de un conector de 5 o 6 pines (dependiendo del dispositivo), los cuales asignan 4 pines em ambos casos, y es posible usar un adaptador de uno a otro, o lograr usar algún pin para otro proposito.

<img src="imagenes/conexiones1.png" width="300" alt="Conexiones del dispositivo ps/2">

<img src="imagenes/conexiones2.png" width="300" alt="Conexiones del dispositivo ps/2">



## Lista de paquetes de datos e informacion que envia el raton

Cuando el ratón PS2 envía información, debe enviar tres paquetes de datos consecutivos. Cada paquete contiene información diferente sobre el botón pulsado, el movimiento y la dirección del mismo. La tabla siguiente muestra la información que se envía en cada paquete.

Hay que tener en cuenta que esta información es general y puede variar según el fabricante. Esto se aplica a un ratón de dos botones; la asignación de bits para otros tipos de ratones (de tres botones o con rueda de desplazamiento) es diferente.

<img src="imagenes/comandos.png" width="500" alt="Lista de comandos de un raton ps/2 de tres botones">

## Forma de onda

<img src="imagenes/señales.png" width="500" alt="Especificaciones de señal del ps/2">
