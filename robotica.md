Robótica

#Sensores

##Visión artificial: 

Puede ser muy diferente de lo que entendemos:

* Otro tipo de ojos 
 - insectos: ojos compuestos de sensores independientes, ejemplo de como ve una mosca en movimiento
 - ojos de precisión: 
   * sensores en determinados puntos aseguran la alineación de piezas, ejemplo: colocación de parabrisas en coches por medio de robots
   * alineación de tuneladoras con láser
* Otras radiaciones
  - sensores de calor en misiles

Posicionamiento por GPS

Las lecturas de todos los sensores se pueden agrupar en un mapa, del que podemos tomar "imágenes"

Podemos aplicar técnicas tradicionales de reconocimiento y procesamiento de imágenes

Los ojos pueden ser:
* en color
* en escala de grises
* en blanco y negro

Nuestro robot tendrá 2 en blanco y negro y 2 en escala de grises

#Actuadores y accionamiento

Tenemos un conjunto de variables que definen el estado de las salidas. A veces usando viables digitales (on/off), otras veces analógicas (movimiento, giro, velocidades, aceleraciones)

#Estado y posición 
Definiremos unas coordenadas que definen el estado y/o posición de la maquina.
Estos valores pueden estar referidos a un sistema absoluto e independiente de la máquina o definidos de una forma relativa como si la máquina fuera el centro del universo.

Necesitamos las coordenadas absolutas porque nuestra maquina está incluida en el mundo y además nuestro objetivo es que interaccione con él

Las coordenadas relativas son las más sencillas de usar y representan el estado de nuestra maquina
Estas coordenadas relativas no tienen que ser independientes sino que están relacionadas con su geometría.

Para poder controlar nuestra maquina tendremos que programar operaciones de transformación entre ambas, tanto en sentido directo como inverso.
Habitualmente sabemos en que punto del espacio queremos posicionar nuestra herramienta. A

* * *
Fucionalidades

El software define el comportamiento
