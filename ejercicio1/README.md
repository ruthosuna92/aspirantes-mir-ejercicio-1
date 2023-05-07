Abrir la consola e imprimir la ubicación actual. se hace con pwd 
Crear una carpeta llamada ejercicios en el escritorio desde la consola, si no estas en la ruta del escritorio, muevete a ella. Para ir a escritorio utilicé el comando cd , escribiendo la ruta: /c/Users/57312/Desktop
Luego de que me ubiqué en Escritorio creé una carpeta llamada Ejercicios por medio del comando mkdir 
Cambiar la ubicación a la nueva carpeta que crearon. Se hace con cd
Abrir la carpeta con VSCode. Para abrir la carpeta en vs code utilicé el comando "code ."
En VSCode crear una carpeta ejercicio1. Creada
Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1. listo
Configurar nombre e email globalmente en git. realizado con "git config --global user.email alejandraop391@gmail.com"
Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios. desde la carpeta ejercicios hago el comando git init para iniciar un repositorio, se valida con el comando "ls -al" para ver los archivos ocultos
Crear un primer commit con el mensaje “Versión Inicial”. se usa el comando "git status" para ver si está "Trackeado" el archivo que hemos Creado , aparece que creamos una carpeta llamada ejercicios1 (en el cual creamos un documento README.md), aparece que no esta trackeado, para ello utilizamos el comando "git add ." para hacer el git commit -m 'Versión Inicial' hacer un git commit es asignar un mensaje a un archivo que se creó
Agregar al README.md los comandos que ejecutaron en cada paso. luego se le vuelve a dar git status y ahí debe aparecer que no hay nada para hacer commit, se está trabajando con un árbol limpio
Crear un nuevo commit con el mensaje “Agrega solución primer ejercicio”. Otra vez se utiliza el comando "git commit -m 'Texto'"
Publicar a Github en un repositorio llamado aspirantes-mir-ejercicio-1.
Enviar el link del repositorio en Github a su mentor(a).