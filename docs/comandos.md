# Comandos

Tal y como hemos avanzado en la introducción, la forma más rápida y eficiente de interacturar con un sistema operativo GNU/Linux es a través de la terminal. En este apartado procederemos a explicar con más detalle que es la terminal, el intérprete de comandos y algunos comandos útiles para empezar a navegar por el sistema.

## ¿Qué es la terminal?

La Terminal de Linux es una consola, similar a CMD o PowerShell(pero mucho más avanzada que ambas), utilizada para permitir a los usuarios más avanzados y técnicos controlar hasta el más mínimo detalle del sistema operativo.

Desde esta consola podemos ejecutar todo tipo de binarios, aunque lo suyo es ejecutar aquellos que no tienen interfaz gráfica y que deben usarse mediante comandos. Igual que en otros sistemas operativos, podemos ejecutar cualquier binario o script directamente desde su directorio. Además, Linux tiene también un PATH donde podemos guardar binarios y ejecutarlos sin tener que desplazarnos hasta su directorio. Por defecto, el PATH de Linux está formado por los siguientes directorios (donde se busca el comando en orden):

/usr/local/sbin
/usr/local/bin
/usr/sbin
/usr/bin
/sbin
/bin
/usr/games
/usr/local/games
/snap/bin

La terminal de Linux se basa en un lenguaje de scripting conocido como Bash, heredada de sh, la consola de Unix. Podemos ejecutar scripts desde la consola, ejecutar binarios y realizar todo tipo de tareas. A diferencia de Windows, Linux cuenta en su terminal una gran cantidad de herramientas muy avanzadas para administrar y controlar el sistema operativo.

Para abrir una terminal en la mayoría de las distribuciones de GNU/Linux debemos pulsar las teclas:

    ctrl + alt + t

O en su defecto buscarla en el menú de aplicaciones.

## ¿Qué es un intérprete de comandos?

![bash](images/bash-logo.jpg)

GNU Bash o simplemente Bash (Bourne-again shell) es una popular interfaz de usuario de línea de comandos, específicamente un shell de Unix; así como un lenguaje de scripting. Bash fue originalmente escrito por Brian Fox para el sistema operativo GNU, y pretendía ser el reemplazo de software libre del shell Bourne.​ Lanzado por primera vez en 1989, se ha utilizado ampliamente como el intérprete de inicio de sesión (login) predeterminado para la mayoría de las distribuciones de GNU/Linux, y también de Mac OS X de Apple hasta la versión 10.15​. Una versión también está disponible para Windows 10 y Android.​ También es el intérprete de órdenes de usuario predeterminado en Solaris 11.

Bash es un intérprete de órdenes que generalmente se ejecuta en una ventana de texto donde el usuario escribe órdenes en modo texto. Bash también puede leer y ejecutar órdenes desde un archivo, llamado guion o 'script'. Al igual que todos los intérpretes de Unix, es compatible con el agrupamiento de nombres de archivo (coincidencia de comodines), tuberías, here documents, sustitución de comandos, variables y estructuras de control para pruebas de condición e iteración. Las palabras reservadas, la sintaxis, las variables de ámbito dinámico y otras características básicas del lenguaje se copian de sh. Otras características, por ejemplo, el historial, se copian de csh y ksh. Bash es un intérprete de órdenes compatible con POSIX, pero con varias extensiones.

## Algunos comandos básicos
cd 
ls 
pwd 
grep
cat
mkdir
touch
rm
man
sudo
## Ejercicio
