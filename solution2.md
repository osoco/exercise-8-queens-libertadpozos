para añadir una reina necesito comprobar
- preguntar la información de los board existentes
        board()
    esta información contendrá una matriz con todas las posiciones en donde la reina de ese board representa una amenaza threat(position)=true  (la fila, la columna y la diagonal)en donde no sea una amenaza será threat(position)=false y contendrá la casilla en donde se encuentra empty(position)=false. 
- tendrá que recorrer cada casilla y comprobar si la casilla es false.
    si threat(position) es false y empty() es true se podrá colocar la nueva reina withQueen()  