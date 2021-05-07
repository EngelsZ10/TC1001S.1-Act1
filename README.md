# TC1001S.1.Act1
Actividad 1. Juego Pintando: modificamos el script paint.py del paquete freegames de python para agregar:
- Un color nuevo (naranja)
- Funcionalides para: 
  -  Dibujar un círculo 
  -  Completar el rectángulo
  -  Completar el triángulo 
 
 Integrantes: 
 - Engels Emiliano Miranda Palacios A01423398
 - Ronaldo Jesús Ruíz Álvarez A01424337


Log de Ronaldo:

De la línea 44 a la 58, agregué una porción de código que nos ayudará a la creación del rectángulo
donde se creó un for repetido dos veces para que en ese mismo se dibujara un lado de la base y otro 
de la altura.

De la línea 59 a la 71, se creó la función de dibujar un triángulo, utilizando unas variables similares
a las demás funciones pero con un for repetido 3 veces y que la flecha de una vuelta de 120 grados a la 
izquierda para que de esta manera complete el dibujo del triángulo.

Log Emiliano:

De las lineas 38 a 42 mueve el cursor (del dibujo) al centro entre el punto start y el punto end, calcula `r` como la distancia entre start y end para dibujar un circulo de diametro `r` usando la funcion `dot(r)`.

En la linea 98 cambia el atributo color a naranja cuando el usuario tecleas *sift + o*.
