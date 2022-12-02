# Proyecto-Parcial-1
# 1. OBJETIVOS 
1.1 Objetivo General 
* •	Analizar y demostrar el respectivo funcionamiento que tiene el circuito que mide el nivel de agua y de igual manera realizar el respectivo armado correspondiente a dicho circuito 

1.2. Objetivos Especificos
*  •	Analizar el funcionamiento de cada parte que posee el circuito en cuestión para su respectivo entendimiento dentro del circu
*  •	Demostrar en el circuito armado el correcto funcionamiento de cada parte del circuito
*  •	Observar en el circuito armado que cada pieza cumple su función 

# MARCO TEORICO 
El presente circuito contiene varios componentes no complejos los cuales le dan el funcionamiento correcto para poder realizar la medición del nivel de agua.

En este caso el primer componente a mencionar es el transistor NPN 2N3904 cuenta con 3 pines que son base, colector y emisor, donde el emisor se encarga de emitir o inyectar electrones, la base permite transferir o pasar los electrones y el colector se encarga de colectar electrones. 

Este transistor es de propósito general y está diseñado para aplicaciones lineales y de conmutación, es utilizado comúnmente como amplificador de media potencia. Funciona en tres regiones semiconductoras, las cuales son: corte, saturación y amplificación. Se puede aplicar una pequeña corriente en la región base, para controlar una corriente mayor que fluirá entre las regiones (emisor y colector). Este transistor es de bajo costo, practico para conectarlo a un protoboard. Con este componente logramos recibir, transferir y amplificar la corriente negativa que pasar por nuestro circuito.

Las resistencias en este caso son parte fundamental del circuito eléctrico ya que son las encargadas de actuar como obstáculo cuando pasa la corriente eléctrica por el circuito de esta manera evitando así la sobrecarga en este.
# MATERIALES
* •	Placa de pruebas (Protoboard)
* •	3 transistores NPN 2N3904
* •	3 resistores de 510 Ω
* •	1 resistor 1 kΩ
* •	3 luces led 
* •	Cables macho macho o jumpers
* •	Pila de 9 V
# PROCEDIMIENTO 
* •	Conectamos a la placa de pruebas los 3 transistores NPN 2N3904 con la parte plana del transistor observando hacia nosotros
* ![image](https://user-images.githubusercontent.com/116832991/205128270-d6b2e976-0983-41d7-b61e-bd830f63e627.png)
* •	Realizamos conexiones con los cables macho macho o jumpers en la pata emisora del transistor llevándolos hacia la terminal negativa por donde pasara la corriente y lo conectamos
* ![image](https://user-images.githubusercontent.com/116832991/205128379-34e2055b-782f-470f-a099-d9a1b9428e2e.png)
* •	Conectamos nuestras resistencias de 510 Ω en la pata colectora del transistor pasando el canal central de la placa de pruebas y la conectamos
* ![image](https://user-images.githubusercontent.com/116832991/205127583-7db54431-8b3e-47f5-a64c-91d7e9e4754f.png)
* •	Procedemos a conectar las luces led con el ánodo conectado en la terminal positiva de corriente y el cátodo haciendo conexión en la parte del resistor que estaba suelta, estas resistencias cumplen la función de regular la corriente que pasa hacia la luz led para que no se queme
* ![image](https://user-images.githubusercontent.com/116832991/205127650-e4b8a783-b3ba-4e8e-8043-1baacdd00b16.png)
*  •	La resistencia de 1 kΩ la conectamos desde la terminal positiva por donde pasa la corriente hacia el nodo por donde circula la corriente para las resistencias de 510 Ω
*  ![image](https://user-images.githubusercontent.com/116832991/205127756-19b48af7-c124-4519-9032-b1aaffd5397e.png)
* •	Realizamos la conexión de jumpers con el primero conectándolo en donde quedo la resistencia de 1 kΩ, el segundo jumper lo conectamos en la pata base del primer transistor, el tercer jumper de igual manera conectándolo en la pata base del segundo transistor y el ultimo jumper conectándolo igual en la pata base del ultimo transistor
* ![image](https://user-images.githubusercontent.com/116832991/205127786-89900e48-21dc-46d4-90b1-8a335509293a.png)
* •	Conectamos nuestra fuente de voltaje al circuito en este caso la batería de 9 V
*  •	Procedemos a verificar si las conexiones están realizadas de una manera correcta introduciendo los jumpers sueltos a un vaso con agua y observar si las 3 luces led se encienden correctamente 
*  ![image](https://user-images.githubusercontent.com/116832991/205127827-23f1e636-c45c-4de9-9bef-0de7d45742d6.png)
* •	Por último, arreglamos nuestros jumpers a la altura deseada y el circuito armado estará correctamente realizado verificando que a medida que el agua los va tocando las luces led se van encendiendo
* ![image](https://user-images.githubusercontent.com/116832991/205127898-8ce7cd10-5e42-49d7-8c3b-93c3e86511f4.png)
# DIAGRAMA CIRCUITAL
![WhatsApp Image 2022-12-01 at 1 26 35 PM](https://user-images.githubusercontent.com/116832991/205194061-9df66e28-8b7e-4f82-b638-3bdbeef3d5f7.jpeg)

#CIRCUITO ARMADO
![WhatsApp Image 2022-11-30 at 11 48 40 PM](https://user-images.githubusercontent.com/116832991/205121868-4188f7f6-8d5a-407f-a74f-bcd56cf89c14.jpeg)
![WhatsApp Image 2022-11-30 at 11 48 40 PM (2)](https://user-images.githubusercontent.com/116832991/205122127-011ee8f7-550a-4de7-bf35-abdd7304804e.jpeg)

# VIDE EN YOUTUBE
* https://www.youtube.com/watch?v=YbOOiUMdjYI
# CONCLUISIONES 
* •	Como se ah podido observar en el circuito el transistor se encarga de recibir, transferir y emitir corriente negativa hacia la luz led 
* •	De este modo se puede entender que la resistencia de 1 kΩ se encarga de proteger el circuito de la corriente positiva para que este no se sobrecargue y mediante el uso del jumper cargamos el vaso de agua con corriente positiva 
* •	Para finalizar gracias a la base del transistor la cual se encarga de transferir la corriente negativa que le llega mediante la pata receptora podemos cargar negativamente el agua con los jumpers y gracias a eso el circuito funciona correctament  
