
Información de las otras reinas:
-posición de las otras reinas.
Por cada reina tendré que ejecutar el método
position()
Me devólverá la fila y la columna en donde se encuentra la reina.
reina1(position)
devolvera una fila y una columna (1F,1C)

Cambiar el valor de empty a false de la position de la reina.

tanto el número de la fila como la columna no se podrán usar. 
 - recorrer la fila 1 e ir cambiando los valores de threat a true hasta que acabe la fila. 
 - recorrer la columna 1 e ir cambiando los valores de threat a true hasta que acabe la columna. 

tendré que sacar la posición en diagonal que tampoco se podrán usar:
iterar la matriz partiendo de la posición de la reina1. en cada nueva posición cambiará el valor de threat a tue hasta que  x o y llegue a 0: 
dada la posición de la reina1[x,y]
posiciones: [x+1, y+1] 
            [x+1, y-1]
            [x-1, y-1]
            [x+1, y-1]


condiciones para añadir una reina.
-empty(position):true
-threats(position): false;

si las pasa:
withQueen(Queen): Board

