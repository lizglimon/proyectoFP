proyectoFP
==========
Proceso  #BUSCAMINAS#
=======
En consola

Config
Allegro5

--------------------
cd Desktop 

//Carpeta con codigo

cd trabajosc

cd brick 

//carpeta con archivo .c

-----------------------
definicion de librerias
Agregar
=======================
gcc main.c -o juego2 `pkg-config --libs allegro-5.0 allegro_main-5.0 allegro_image-5.0`

toma el archivo main.c y lo renombra "juego2"

-----------------------
utiliza el nombre con el que se redefinio

ejecutar juego
=======================
./juego2


Uso del juego
=======================

        printf("Para jugar, escriba la posicion a elegir:\n  Fila enter Columna\n\n");

Requiere que se ingresen dos numeros 

        scanf("%d", &fila);
        scanf("%d", &columna);

