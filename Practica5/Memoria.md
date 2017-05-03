# Práctica 5

### 1. Crear una BD con al menos una tabla y algunos datos.

Vemos la secuencia de creación:

![GitHub Logo](Ejercicio1_1.JPG)

### 2. Realizar la copia de seguridad de la BD completa usando mysqldump.

Realizamos la copia de seguridad siguiendo los pasos del manual de prácticas:

![GitHub Logo](Ejercicio2_1.JPG)

![GitHub Logo](Ejercicio2_2.JPG)

### 3. Restaurar dicha copia en la segunda máquina (clonado manual de la BD).

Nos llevamos el fichero de copia de seguridad a una segunda máquina.

![GitHub Logo](Ejercicio3_1.JPG)

Lo añadimos a nuestra BDD y vemos que se copian los datos:

![GitHub Logo](Ejercicio3_2.JPG)

### 4. Realizar la configuración maestro-esclavo de los servidores MySQL para que la replicación de datos se realice automáticamente.

Conectando mysql en la máquina 1

![GitHub Logo](Ejercicio4_1.JPG)

Conectando mysql en la máquina 2

![GitHub Logo](Ejercicio4_2.JPG)

Creando configuración MASTER 

![GitHub Logo](Ejercicio4_3.JPG)

Creando configuración SLAVE

![GitHub Logo](Ejercicio4_4.JPG)

Vemos que no sale null y no ha habido fallos

![GitHub Logo](Ejercicio4_5.JPG)

Pero a la hora de la inserción he tenido problemas, he buscado soluciones por internet al problema de tener el mismo UUID en las máquinas pero no he podido solucionarlo.

![GitHub Logo](Ejercicio4_6.JPG)

