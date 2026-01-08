Buenas!

Intentando seguir los pasos del gran Sthil Lauda, voy a crear este post para agrupar aquí la lista de macros que voy a ir creando para la versión web del cliente del juego (https://ultima-alianza.com/wiki/index.php/ClienteWEB)

Espero poder ir aportando scripts de forma continua, y hacer poco a poco una lista interesante para que los que jueguen con este maravilloso cliente se sientan cada vez más cómodos usándolo.

Cada script está en forma de enlace al propio archivo alojado en el repositorio de Github. Esto lo hago así para asegurar que la versión que vais a descargar sea siempre la más reciente.

----
# MACROS AUTOMÁTICAS:

* a01_quitar-veneno
* a02_heal
* a03_aviso-vida
* a04_aviso-pocion




# MACROS MANUALES:

* m01_montar-desmontar-montura
* m02_caja-trampa
* m03_runa-escape
* m04_in-mani
* m05_in-vas-mani
* m06_protection
* m07_bless
* m08_reactive-armor
* m09_magic-reflect
* m10_magic-arrow
* m11_explo
* m12_descarga
* m13_flame


----

# TUTORIAL MACROS AUTOMÁTICAS

1. Partimos del punto en el que ya se está ejecutando el cliente web correctamente, si no es tu caso, viene explicado todo https://ultima-alianza.com/wiki/index.php/ClienteWEB

2. Una vez dentro del juego, hacemos clic aquí:

3. Esto nos abrirá el menú para crear los scripts, en esta ventana tendremos que crear un nuevo script haciendo clic aquí:

4. Y luego crear el script, con el nombre que queramos, y seleccionando Typescript/Javascript en el segundo select, y dejando vacio el tercer select. Luego clic en Create Script

5. Esto nos creará una ventana nueva donde tendremos que pegar el script que hayamos copiado del repositorio (haciendo clic en el nombre de la macro, te envía al repositorio desde donde debes de copiar la macro) .

6. Lo copiamos, lo guardamos (control + s) y lo ejecutamos

7. Con el script ya en ejecución, podemos cerrar la ventana del ide, el script se seguirá ejecutando en segundo plano

8. Con esto ya quedaría el script corriendo en el juego, de igual forma que cuando le damos al play en el easyUO

----

# TUTORIAL MACROS MANUALES
Hay algunos scripts que no se quedan en bucle ejecutándose, sino que son asignados a una tecla que cuando se pulsa hace que se ejecute (vaya, las macros de toda la vida de pulsar una tecla), como por ejemplo el script de montar y desmontar una montura. Para estos casos es tan simple como:
1. Copiar del repositorio la macro manual que queramos
2. Pegarla en la ventana de las macros del juego
3. Hacer clic en el botón Not bound

4. Asignar la tecla que se quiera para dicho script.
5. Listo, ya podemos cerrar esta ventana, al pulsar la tecla se usará la macro 