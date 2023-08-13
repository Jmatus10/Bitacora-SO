# Bitacora-SO
Comandos usados durante el curso
|Comando|Descripcion|Ejemplo de uso|
|--|--|--|
|`ls`|Lista los archivos|`ls` va a mostrar la lista de los archivos|
|`cd`|Cambia el directorio actual|`cd` cd/ruta/directorio|
|`pwd`|Muestra la ruta del directorio actual|`pwd` + el nombre de la carpeta te dira donde esta| 
|`mkdir`|Crea un nuevo directorio|`mkdir` nuevo directorio|
|`rm`|Elimina archivos o directorios|`rm` nombre del archivo.txt|
|`chmod`|Cambia los permisos de un archivo|`chmod` +x script.sh|
|`chown`|Cambia el propietario de un archivo o directorio|`chown` usuario archivo.txt|
|`ps`|Muestra los procesos en ejecucion|`ps aux`|
|`top`|Muestra la lista de los procesos en tiempo real|`top`|
|`kill`|Termina un proceso|`kill PID`|
|`sudo`|Ejecuta un comando como superusuario|`sudo` apt-get update|
|`apt-get`|Gestiona los paquetes|sudo `apt-get` install nombre_paquete|
|`df`|Muestra el espacio en disco disponible|`df`-h|
|`ifconfig`|Muestra la configuracion de red|`ifconfig`|
|`ssh`|Inicia una sesion SSH en un servidor remoto|`ssh` usuario@servidor|
|`cp`|Copia de archivos o directorios| `cp` archivo.txt destino/|
|`mv`|Mueve o renombra archivos o directorios|`mv` archivo.txt nuevo_nombre|
|`cat`|Muestra el contenido de un archivo sin abrirlo|`cat` archivo.txt|
|`tar`|Comprime y descomplime archivos en la terminal|`tar` -cvf archivo.tar directorio|
|`zip`|Crea archivos ZIP|`zip` archivo.zip archivo.txt|
|`unzip`|Descomprime archivos ZIP|`unzip` archivo.txt|
|`nano`|Editor de texto en la terminal|`nano` archivo.txt
|`vim`|Editor de texto avanzado|`vim` archivo.txt|
|`history`|Muestra el historial de los comandos ejecutados|`history`|
|`date`|Muestra la fecha y hora actual|`date`|
|`echo`| Muestra un mensaje en la terminal|`echo` "Hola Mundo"|
|`reebot`|Reinicia el sistema| sudo `reboot`|
|`find`|Busca archivos y directorio|`find` /ruta -name "archivo"|
|`curl`|Realiza solicitudes HTTP desde la linea de comando|`curl` https://www.miejemplo.com|
|`adduser`|Añade un nuevo usuario|sudo `adduser` nuevo_usuario|
|`usermod`|Modifica la configuracion del usuario|sudo `usermod` -aG grupo usuario| 
|`passwd`|Cambia la contraseña del usuario|`passwd` usuario|
|`chroot`|Cambia el directorio de raiz para un proceso|sudo `chroot` /nuevo/directorio /bin/bash
|`du`|Muestra el uso de espacio por directorio|`du` -sh directorio|
|`scp`|Copia archivos a traves de SSH|`scp` archivo.txt usuario@servidor:~/|
|`cal`|Muestra el calendario|`cal`|
|`Isof`|Lista de archivos abiertos por procesos|`Isof` -i :puerto|
|`hostname`|Muestra o cambia el nombre del host|`hostname`|
|`nano prueba.text`|Te permite crear y editar el archivo de texto "prueba.txt|`nano prueba.txt`|
|`clear`|Limpia la pantalla|`clear`|
|`man ls`|Muestra los parametros de un comando| `man ls`|
|`su`|Activa el super-usuario|sudo `su`|
|`sudo pacman -Sy`|Se usa para actualizar la lista de los paquetes disponibles en los repositorios y sincronizar la informacion|`sudo pacman -Sy`|
|`sudo pacman -S unrar zip unzip gzip bzip2`|Se usa para instalar varios paquetes relacionados con la manipulacion y compresion de archivos|`sudo pacman -S unrar zip unzip gzip bzip2`|
|`sudo pacman -S yay`|Se utiliza para instalar el programa "yay"|`sudo pacman -S yay`|
|`sudo yay -S --needed base-devel`|este comando utiliza "yay" para instalar el grupo de paquetes "base-devel" desde el AUR. El grupo "base-devel" es necesario para compilar y construir paquetes desde el AUR, ya que contiene herramientas y bibliotecas esenciales para el desarrollo|`sudo yay -S --needed base-devel`|
|`yay -S google-chrome`|Se utiliza para instalar Google Chrome en el sistema Manjaro, utilizando AUR|`yay -S google-chrome`|
|`sudo systemctl start httpd`|Se utiliza en Manjaro para iniciar el servicio del servidor web Apache (HTTPD)|`sudo systemctl start httpd`|
| `uname -a`|Se utiliza para obtener información detallada sobre el sistema operativo y el hardware en el que estás trabajando|`uname -a`|
|`git clone`|Se usa para clonar un repositorio de Git desde una ubicación remota a tu sistema local|`git clone` https://github.com/mortasoft/linux-scripts|
|`ls /bin`|Se usa para ver los archivos ejecutables esenciales en el directorio /bin, que son vitales para el funcionamiento del sistema operativo y para ejecutar comandos básicos en Manjaro y otras distribuciones Linux y Unix|`ls /bin`|
|'exit'|Salir del root |'exit' si ya no se necesita el root|
|'more'|Muestra el resultado de la ejecución de un comando en la terminal de a una página a la vez|ps-ef'more'La pantalla se llenará
con una lista de datos, pero se detendrá al final de la página con el mensaje "more"|
|'whoami'|Saber el usuario |'whoami' en el terminal te dirá en el usuario que estás|
