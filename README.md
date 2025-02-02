# comandos-linux

ls

Descripción: Muestra una lista de archivos y directorios en el directorio actual.
Ejemplo: ls -l
pwd

Descripción: Muestra el directorio de trabajo actual.
Ejemplo: pwd
cd

Descripción: Cambia el directorio actual de trabajo.
Ejemplo: cd /home/usuario
cat

Descripción: Muestra el contenido de un archivo en la terminal.
Ejemplo: cat archivo.txt
more

Descripción: Muestra el contenido de un archivo de texto, pero permite paginarlo si es demasiado largo.
Ejemplo: more archivo.txt
less

Descripción: Similar a more, pero permite desplazarse hacia atrás en el archivo.
Ejemplo: less archivo.txt
head

Descripción: Muestra las primeras líneas de un archivo.
Ejemplo: head archivo.txt
tail

Descripción: Muestra las últimas líneas de un archivo.
Ejemplo: tail archivo.txt
Comandos para manipulación de archivos:
cp

Descripción: Copia archivos o directorios de una ubicación a otra.
Ejemplo: cp archivo.txt /home/usuario/
mv

Descripción: Mueve o renombra archivos o directorios.
Ejemplo: mv archivo.txt /home/usuario/
rm

Descripción: Elimina archivos o directorios.
Ejemplo: rm archivo.txt
touch

Descripción: Crea un archivo vacío o actualiza la fecha y hora de acceso de un archivo existente.
Ejemplo: touch archivo.txt
mkdir

Descripción: Crea un nuevo directorio.
Ejemplo: mkdir nuevo_directorio
rmdir

Descripción: Elimina un directorio vacío.
Ejemplo: rmdir viejo_directorio
Comandos para permisos y propietarios:
chmod

Descripción: Cambia los permisos de acceso a archivos o directorios.
Ejemplo: chmod 755 archivo.sh
chown

Descripción: Cambia el propietario y el grupo de un archivo o directorio.
Ejemplo: chown usuario:grupo archivo.txt
Comandos de búsqueda y filtrado:
grep

Descripción: Busca un patrón dentro de un archivo o salida de comandos.
Ejemplo: grep "error" archivo.log
find

Descripción: Busca archivos y directorios en una ubicación especificada.
Ejemplo: find /home/usuario/ -name "*.txt"
locate

Descripción: Busca archivos rápidamente en el sistema utilizando una base de datos de ubicación pre-generada.
Ejemplo: locate archivo.txt
Comandos para gestión de procesos:
ps

Descripción: Muestra los procesos en ejecución.
Ejemplo: ps aux
top

Descripción: Muestra los procesos en ejecución en tiempo real y estadísticas del sistema.
Ejemplo: top
kill

Descripción: Envía señales a un proceso (como terminarlo).
Ejemplo: kill 1234 (termina el proceso con PID 1234)
killall

Descripción: Termina todos los procesos con el nombre especificado.
Ejemplo: killall firefox (termina todos los procesos de Firefox)
Comandos para administración del sistema:
sudo

Descripción: Ejecuta un comando con privilegios de superusuario (root).
Ejemplo: sudo apt update
shutdown

Descripción: Apaga o reinicia el sistema.
Ejemplo: sudo shutdown -h now
reboot

Descripción: Reinicia el sistema.
Ejemplo: sudo reboot
df

Descripción: Muestra información sobre el espacio libre y usado en los sistemas de archivos montados.
Ejemplo: df -h
free

Descripción: Muestra información sobre el uso de la memoria del sistema.
Ejemplo: free -h
uptime

Descripción: Muestra el tiempo de actividad del sistema y la carga promedio.
Ejemplo: uptime
man

Descripción: Muestra el manual de un comando.
Ejemplo: man ls
Comandos para gestión de paquetes (en distribuciones basadas en Debian/Ubuntu):
apt-get

Descripción: Gestor de paquetes para instalar, actualizar o eliminar software.
Ejemplo: sudo apt-get install paquete
apt

Descripción: Comando alternativo para gestionar paquetes (más sencillo que apt-get).
Ejemplo: sudo apt update
dpkg

Descripción: Herramienta para instalar, eliminar y gestionar paquetes .deb.
Ejemplo: sudo dpkg -i paquete.deb
Comandos para compresión y archivado:
tar

Descripción: Crea o extrae archivos tar (archivos comprimidos).
Ejemplo: tar -czvf archivo.tar.gz carpeta/
gzip

Descripción: Comprime archivos utilizando el algoritmo gzip.
Ejemplo: gzip archivo.txt
unzip

Descripción: Extrae archivos comprimidos en formato .zip.
Ejemplo: unzip archivo.zip
Comandos para manejo del historial:
history

Descripción: Muestra el historial de comandos ejecutados en la terminal.
Ejemplo: history
!n

Descripción: Ejecuta el comando en la posición n del historial.
Ejemplo: !20 (ejecuta el comando número 20 del historial)
¡Espero que esta organización te sea útil! Si tienes alguna otra duda o necesitas más información, no dudes en preguntar.
