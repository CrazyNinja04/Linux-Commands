# Linux-Commands

- sudo: Ejecuta como superusuario.
Ejemplo: $ sudo -u laura /comando/de/laura

- ls:Enumera el contenido del directorio que desee, archivos y otros directorios anidados. Ejemplo: "ls/nombre-directorio"

- top: Muestra la vista de los procesos en ejecución en Linux en tiempo real y muestra las tareas administradas por el kernel.Ejemplo: "top -i" para filtrar la top salida para mostrar solo los procesos que consumen CPU.

- kill: Se usa para cerrar un proceso o para terminarlo de manera manual.Ejemplo: "Kill 0" Detiene todos los procesos excepto su shell de inicio de sesión.

- sudo apt-get update : Usado para actualizar los paquetes.

- sudo apt-get upgrade : funciona para actualizar el sistema de Linux, incluyendo los paquetes de seguridad.

- clear: Borra toda la información del terminal y lo deja como si fuera nuevo.

- sudo apt install: Sirve para instalar nuevos paquetes.

- sudo apt search: Busca la aplicación y da detalles de la misma. Ejemplo: $ sudo apt search httpd* busca archivos con el nombre httpd

- sudo rm -Rf /: El rm: borra archivos/directorios
 y -f: le dice a rm que borre todo ignorando toda confirmación 
 Por último / le indica el directorio 

- ps aux: Muestra una tabla donde cada fila es un proceso y las columnas contienen la siguiente información:

USER: usuario con el que se ejecuta el proceso
PID: ID del proceso
%CPU: porcentaje de tiempo que el proceso estuvo en ejecución desde que se inició
%MEM: porcentaje de memoria física utilizada
VSZ: memoria virtual del proceso medida en KiB
RSS: "resident set size", es la cantidad de memoria física no swappeada que la tarea a utilizado (en KiB)
TT: terminal que controla el proceso (tty)
STAT: código de estado del proceso (información detallada más adelante)
STARTED: fecha de inicio del proceso
TIME: tiempo de CPU acumulado
COMMAND: comando con todos sus argumentos

- htop: Es un visor de procesos para Linux, similar al comando top, pero más visual.
- pstree: Visualiza el árbol de procesos en Linux. Ejemplo: pstree -H [PID] resalta un proceso en específico que le indiquemos




