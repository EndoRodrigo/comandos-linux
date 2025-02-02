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
Ejecuta un comando con privilegios de superusuario (root).
```bash
sudo apt update
```
Apaga o reinicia el sistema.
```bash
sudo shutdown -h now
```
Reinicia el sistema.
```bash
 sudo reboot
```
Muestra información sobre el espacio libre y usado en los sistemas de archivos montados.
```bash
df -h
```
Muestra información sobre el uso de la memoria del sistema.
```bash
free -h
```
Muestra el tiempo de actividad del sistema y la carga promedio.
```bash
uptime
```
Muestra el manual de un comando.
```bash
man ls
```

## Comandos para gestión de paquetes (en distribuciones basadas en Debian/Ubuntu):
Gestor de paquetes para instalar, actualizar o eliminar software.
```bash
sudo apt-get install paquete
```
Comando alternativo para gestionar paquetes (más sencillo que apt-get).
 ```bash
sudo apt update
```
Herramienta para instalar, eliminar y gestionar paquetes .deb.
 ```bash
sudo dpkg -i paquete.deb
```

## Comandos para compresión y archivado:
Crea o extrae archivos tar (archivos comprimidos).
 ```bash
tar -czvf archivo.tar.gz carpeta/
```
Comprime archivos utilizando el algoritmo gzip.
 ```bash
gzip archivo.txt
```
Extrae archivos comprimidos en formato .zip.
 ```bash
unzip archivo.zip
```

## Comandos para manejo del historial:
history

Descripción: Muestra el historial de comandos ejecutados en la terminal.
Ejemplo: history
!n

Descripción: Ejecuta el comando en la posición n del historial.
Ejemplo: !20 (ejecuta el comando número 20 del historial)
¡Espero que esta organización te sea útil! Si tienes alguna otra duda o necesitas más información, no dudes en preguntar.
