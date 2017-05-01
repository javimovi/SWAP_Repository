# Práctica 4

### 1. Instalar un certificado SSL autofirmado para configurar el acceso HTTPS a los servidores.

Configuramos el acceso https

![GitHub Logo](Ejercicio1_1.JPG)

![GitHub Logo](Ejercicio1_2.JPG)

Editamos el archivo default-ssl

![GitHub Logo](Ejercicio1_3.JPG)

Y por último reiniciamos el servicio para actualizar la configuración:

![GitHub Logo](Ejercicio1_4.JPG)

### 2. Configurar las reglas del cortafuegos con IPTABLES para asegurar el acceso a
los servidores web, permitiendo el acceso por los puertos de HTTP y HTTPS.
Esta configuración se puede hacer en la misma máquina balanceadora. En
cualquier caso se debe poner en un script que se ejecute en el arranque del
sistema.

Compruebo el estado del cortafuegos

![GitHub Logo](Ejercicio2_1.JPG)

Creo el script que servirá para aceptar tráfico por HTTP y HTTPS

![GitHub Logo](Ejercicio2_2.JPG)

Y por último ejecuto el script

![GitHub Logo](Ejercicio2_3.JPG)
