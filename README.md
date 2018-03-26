# rpi3router
Script para convertir la raspberry pi, Orange Pi u otras placas en un ruter que se conecta a una señal wifi y ofrece internet a traves del puerto ethernet.
Conectando un Switch o un router al puerto ethernet podemos dar internet a varios equipos.
Si el router es un router wifi pudes hacer una especie de repetidor que creando otra red distinata.
Para ello hay que deshabilitar el dhcp en el router y poner puerta de enlace la 192.168.0.1
Si le pillas el wifi al vecino o al bar de abajo puedes tener internet gratis en casa.
Yo lo he probado con una antena Yagi grande de exteriores, pasando el cable a dentro de la casa, conectado a una tarjeta alpha de potencia buena a la antena y la tarjeta a la raspberry por usb. El puerto ethernet conectado a un router wifi. 
El resultado: tienes tu propia wifi gratis. 


Ejecutar como administrador asi:
......$ sudo su

......# ./rpi3installer
