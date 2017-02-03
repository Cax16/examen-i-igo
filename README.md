# examen-i-igo
primero cramos los routers  de cada ejercicio y le configuramos las entradas para interconectarlos, y los pasamaos a version 2
creamos la 2 primeras subredes con 2 ordenadores cada una con su ip cada ordenador y la primera subred sin conectar a los otros routers
 creamos otra subred con  3 ordenadores con una ip estatica  y otros 2 con dhcp para ello los ponemos en dhcp y creamos un servidor
 al cual le damos una ip y lo ponemos en dhcp poniendole la mascara la ip del router  y conectado a la subred
 creamos dos servidores con una web cada uno en el cual en el index ponemos lo  que se pide en el ejercicio
 web01 y web02 y creamos un servidor de dns, en este caso yo utilice un servidor anterior que ya tenai crado, uno de los de dhcp el segundo concretamente y  le añadimos la ip de los servidores de las pags web01 y web02 y le añadimos la direccion www.web01.es ...
 y ya tenemos nuestro servidor dns con las web funcionando
