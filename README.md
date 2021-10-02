# SSOO-tarea01
Katerina Peñaloza Caballería - katerina.penaloza@alumnos.uv.cl

1.- Para la primera parte de explicar y dar ejemplos de los comandos solicitados, se realizo una búsqueda en internet en donde explican con sus propias palabras los comandos, además se buscó con el comando man, el significado oficial del comando.
2.- Para explicar los metacaracteres se buscó se internet su significado, luego me di cuenta de que se usa principalmente en regex, así que a pesar de tener una vaga idea de lo que es el regex, se buscó igualmente su significado y uso. Para los ejemplos de uso de los metacaracteres, se pusieron caso de la vida real en los que hemos utilizado esto.
3.- Primero para el problema de la expansion de llaves, se verificó lo más basico que es la expansión de numeros, en la consola se puso:
echo {1..10}
lo que dio como resultado 1 2 3 4 5 6 7 8 9 10
Luego ejecute el comando echo 2021-{01..12}-{01-31} para dar forma a la estructura de carpeta
Por lo tanto usando el comando mkdir para crear directorios, el comando final para resolver el problema es:
mkdir 2021-{01..12}-{01-31}
