# comandos-linux

## Comandos para navegación y visualización de archivos:

Muestra una lista de archivos y directorios en el directorio actual.
```bash
ls -l
``` 
Muestra el directorio de trabajo actual.
```bash
pwd
``` 
Cambia el directorio actual de trabajo.
```bash
cd /home/
``` 
Muestra el contenido de un archivo en la terminal.
```bash
cat archivo.txt
``` 
Muestra el contenido de un archivo de texto, pero permite paginarlo si es demasiado largo.
```bash
more archivo.txt
``` 
Similar a more, pero permite desplazarse hacia atrás en el archivo.
```bash
less archivo.txt
``` 
Muestra las primeras líneas de un archivo.
```bash
head archivo.txt
``` 
Muestra las últimas líneas de un archivo.
```bash
tail archivo.txt
``` 

## Comandos para manipulación de archivos:
Copia archivos o directorios de una ubicación a otra.
```bash
cp archivo.txt /home/usuario/
``` 
Mueve o renombra archivos o directorios.
```bash
mv archivo.txt /home/usuario/
``` 
rm
Elimina archivos o directorios.
```bash
rm archivo.txt
```
Crea un archivo vacío o actualiza la fecha y hora de acceso de un archivo existente.
```bash
touch archivo.txt
```
Crea un nuevo directorio.
```bash
mkdir nuevo_directorio
```
Elimina un directorio vacío.
```bash
rmdir viejo_directorio
```

## Comandos para permisos y propietarios:
Cambia los permisos de acceso a archivos o directorios.
```bash
chmod 755 archivo.sh
```
Cambia el propietario y el grupo de un archivo o directorio.
```bash
chown usuario:grupo archivo.txt
```

## Comandos de búsqueda y filtrado:
Busca un patrón dentro de un archivo o salida de comandos.
```bash
grep "error" archivo.log
```
Busca archivos y directorios en una ubicación especificada.
```bash
find /home/usuario/ -name "*.txt"
```
Busca archivos rápidamente en el sistema utilizando una base de datos de ubicación pre-generada.
```bash
locate archivo.txt
```

## Comandos para gestión de procesos:
Muestra los procesos en ejecución.
```bash
ps aux
```
Muestra los procesos en ejecución en tiempo real y estadísticas del sistema.
```bash
top
```
Envía señales a un proceso (como terminarlo).
```bash
kill 1234 (termina el proceso con PID 1234)
```
Termina todos los procesos con el nombre especificado.
```bash
killall firefox (termina todos los procesos de Firefox)
```

## Comandos para administración del sistema:
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
