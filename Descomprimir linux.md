- [TAR Comprimir con tar:](#tar-comprimir-con-tar)
- [Descomprimir con tar:](#descomprimir-con-tar)
- [GZIP Comprimir con gzip:](#gzip-comprimir-con-gzip)
- [Descomprimir con gzip](#descomprimir-con-gzip)
  - [BZ2 Comprimir con bz2](#bz2-comprimir-con-bz2)
  - [Descomprimir con bz2](#descomprimir-con-bz2)
  - [ZIP Comprimir con zip](#zip-comprimir-con-zip)
  - [Descomprimir con unzip](#descomprimir-con-unzip)
  - [RAR Comprimir con rar:](#rar-comprimir-con-rar)
  - [Descomprimir con rar](#descomprimir-con-rar)
- [Ficheros tar](#ficheros-tar)
  - [Empaquetar](#empaquetar)
  - [Desempaquetar](#desempaquetar)
  - [Ver el contenido de un fichero .tar](#ver-el-contenido-de-un-fichero-tar)
- [Ficheros gz](#ficheros-gz)
  - [Comprimir o empaquetar](#comprimir-o-empaquetar)
  - [Descomprimir](#descomprimir)
- [Ficheros bz2](#ficheros-bz2)
  - [Comprimir](#comprimir)
  - [Descomprimir](#descomprimir-1)
- [Ficheros tar.gz](#ficheros-targz)
  - [Comprimir](#comprimir-1)
  - [Descomprimir](#descomprimir-2)
  - [Ver el contenido de un fichero comprimido](#ver-el-contenido-de-un-fichero-comprimido)
- [Ficheros tar.bz2](#ficheros-tarbz2)
  - [Comprimir](#comprimir-2)
  - [Descomprimir](#descomprimir-3)
  - [Ver el contenido de un fichero tar.bz2](#ver-el-contenido-de-un-fichero-tarbz2)
- [Ficheros zip](#ficheros-zip)
  - [Comprimir](#comprimir-3)
  - [Descomprimir](#descomprimir-4)
  - [Para ver el contenido de un fichero zip](#para-ver-el-contenido-de-un-fichero-zip)
- [Ficheros rar](#ficheros-rar)
  - [Comprimir](#comprimir-4)
  - [Descomprimir](#descomprimir-5)
  - [Para ver el contenido de un fichero rar](#para-ver-el-contenido-de-un-fichero-rar)
- [Introduction to Zip Command in Linux](#introduction-to-zip-command-in-linux)
  - [1) -u Option](#1--u-option)
  - [2) -d Option](#2--d-option)
  - [3) -m Option](#3--m-option)
  - [4) -x Option](#4--x-option)
  - [5) -r Option](#5--r-option)
  - [6) -v Option](#6--v-option)
- [SHUTDOWN](#shutdown)
  - [Shutdown system without specifying arguments of shutdown command](#shutdown-system-without-specifying-arguments-of-shutdown-command)
  - [Shutdown System Immediately using shutdown command](#shutdown-system-immediately-using-shutdown-command)
  - [Shutdown System after specified time using shutdown command](#shutdown-system-after-specified-time-using-shutdown-command)
  - [Shutdown System by sending message using shutdown command](#shutdown-system-by-sending-message-using-shutdown-command)
  - [Reboot System using shutdown command](#reboot-system-using-shutdown-command)
  - [Reboot system by specifying time and sending message using “shutdown” command](#reboot-system-by-specifying-time-and-sending-message-using-shutdown-command)
  - [Cancel shutodwn using "shutdown" command](#cancel-shutodwn-using-shutdown-command)
- [Cómo usar ps, kill y nice para administrar procesos en Linux](#cómo-usar-ps-kill-y-nice-para-administrar-procesos-en-linux)
  - [Cómo ver los procesos en ejecución en Linux](#cómo-ver-los-procesos-en-ejecución-en-linux)
    - [Comando top](#comando-top)
  - [Cómo usar ps para realizar una lista de procesos](#cómo-usar-ps-para-realizar-una-lista-de-procesos)
  - [Una nota sobre las ID de procesos](#una-nota-sobre-las-id-de-procesos)
  - [Cómo enviar señales a los procesos en Linux](#cómo-enviar-señales-a-los-procesos-en-linux)
    - [Cómo enviar señales a los procesos por PID](#cómo-enviar-señales-a-los-procesos-por-pid)
    - [Cómo usar señales para otros fines](#cómo-usar-señales-para-otros-fines)
    - [Cómo enviar señales a los procesos por nombre](#cómo-enviar-señales-a-los-procesos-por-nombre)
- [ps y kill - buscar y eliminar procesos en Linux](#ps-y-kill---buscar-y-eliminar-procesos-en-linux)
  - [Con el comando ps buscamos procesos en ejecución en el sistema.](#con-el-comando-ps-buscamos-procesos-en-ejecución-en-el-sistema)
  - [Si queremos buscar un proceso en concreto, por ejemplo el filezilla](#si-queremos-buscar-un-proceso-en-concreto-por-ejemplo-el-filezilla)
  - [Para eliminar el proceso del filezilla hay que utilizar el comando](#para-eliminar-el-proceso-del-filezilla-hay-que-utilizar-el-comando)
  - [Por ejemplo si queremos eliminar el proceso del filezilla podemos hacer dos cosas, buscarlo](#por-ejemplo-si-queremos-eliminar-el-proceso-del-filezilla-podemos-hacer-dos-cosas-buscarlo)
  - [O podemos eliminarlo por le nombre](#o-podemos-eliminarlo-por-le-nombre)
- [LISTA DE COMANDOS](#lista-de-comandos)
  - [COMANDO PS](#comando-ps)
  - [COMANDO PSTREE](#comando-pstree)
  - [COMANDO KILL](#comando-kill)
  - [COMANDO KILLALL](#comando-killall)
  - [COMANDO NICE](#comando-nice)
  - [COMANDO RENICE](#comando-renice)
  - [COMANDO NOHUP Y &](#comando-nohup-y-)
  - [COMANDO JOBS](#comando-jobs)
  - [COMANDO TOP](#comando-top-1)
- [Comandos Linux para Discos duros y particiones](#comandos-linux-para-discos-duros-y-particiones)
  - [COMANDOS](#comandos)
    - [LSCSI](#lscsi)
    - [LSBLK](#lsblk)
    - [FDISK](#fdisk)
    - [SFDISK](#sfdisk)
    - [DF](#df)
    - [CFDISK](#cfdisk)
    - [PARTED](#parted)
    - [BLKID](#blkid)
  - [CREAR PARTICIONES CON FSDISK EN LINUX](#crear-particiones-con-fsdisk-en-linux)
  - [FORMATEAR PARTICIONES EN LINUX](#formatear-particiones-en-linux)
- [](#)
- [FIREWALL](#firewall)



Es muy necesario tener a la mano los comandos para comprimir y descomprimir archivos en Linux desde la consola. Por lo general cuando se hacen instalaciones en servidores no se cuenta con el modo gráfico para ejecutar este tipo de tareas.

En este post explico la forma de comprimir y descomprimir archivos usando los comandos tar, gzip, bzip, zip, unzip y rar desde la consola.


# TAR Comprimir con tar:
```bash

tar -zcvf nombre-archivo-resultante.tar.gz nombre-directorio-o-archivo

Explicación del comando:

    -z: Comprimir un archivo usando el gzip
    -c: Crear un nuevo archivo
    -v: Mostrar el proceso de compresión
    -f: Nombre del archivo
```

# Descomprimir con tar:
```bash

tar -xvzf archivo-comprimido.tar.gz

Explicación del comando:

    -x: Extrae el contenido del archivo comprimido
    -v: Mostrar el proceso de descompresión
    -f: Nombre del archivo
```

# GZIP Comprimir con gzip:
```bash

gzip -9 nombre-archivo-no-directorio

Explicación del comando:

    -9: Es el nivel de compresión se puede usar desde -1 hasta -9. Donde -9 es compresión óptima y es más lento.
```

# Descomprimir con gzip
```bash
gzip -d nombre-archivo-comprimido.gz

Explicación del comando:

    -d: Descomprimir
```

## BZ2 Comprimir con bz2
```bash
bzip archivo-no-directorio
```
## Descomprimir con bz2
```bash
bzip2 -d archivo.bz2
```
## ZIP Comprimir con zip
```bash
zip archivo.zip archivo-comprimir
```
## Descomprimir con unzip
```bash
unzip archivo.zip
```
## RAR Comprimir con rar:
```bash

rar -a nombre-archivo-resultante.rar archivo-o-carpeta


Explicación del comando:

    -a: Comprimir un archivo
```

## Descomprimir con rar
```bash
rar -x archivo.rar

Explicación del comando:

    -x: Extrae el contenido del archivo comprimido
```



# Ficheros tar
## Empaquetar
```bash
tar -cvf archivo.tar /dir/a/comprimir/

    -c : indica a tar que cree un archivo.

    -v : indica a tar que muestre lo que va empaquetando.

    -f : indica a tar que el siguiente argumento es el nombre del fichero.tar.
```
## Desempaquetar
```bash
tar -xvf archivo.tar

    -x : indica a tar que descomprima el fichero.tar.

    -v : indica a tar que muestre lo que va desempaquetando.

    -f : indica a tar que el siguiente argumento es el nombre del fichero a desempaquetar.
```
## Ver el contenido de un fichero .tar
```bash
tar -tf archivo.tar

    -t : Lista el contenido del fichero .tar

    -f : indica a tar que el siguiente argumento es el nombre del fichero a ver.
```
 
# Ficheros gz
## Comprimir o empaquetar
```bash
gzip -9 fichero

    -9 : le indica a gz que utilice el mayor factor de compresión posible.
```
## Descomprimir
```bash
gzip -d fichero.gz

    -d : indica descompresión
``` 
# Ficheros bz2
## Comprimir
```bash
bzip fichero
```
## Descomprimir
```bash
bzip2 -d fichero.bz2

    -d : indica descompresión.
```
Nota: Tanto el compresor gzip como bzip2, solo comprimen ficheros, no directorios, para comprimir directorios (carpetas), se debe de usar en combinación con tar.
 
# Ficheros tar.gz
## Comprimir  
```bash
tar -czfv archivo.tar.gz ficheros

    -c : indica a tar que cree un archivo.

    -z : indica que use el compresor gzip

    -f : indica a tar que el siguiente argumento es el nombre del fichero.tar

    -v : indica a tar que muestre lo que va empaquetando
```
## Descomprimir 
```bash
tar -xzvf archivo.tar.gz

    -x : le dice a tar que extraiga el contenido del fichero tar.gz

    -z : le indica a tar que esta comprimido con gzip

    -v : va mostrando el contenido del fichero
    -f : le dice a tar que el siguiente argumento es el fichero a descomprimir.
```
 
## Ver el contenido de un fichero comprimido   
```bash
tar -tzf archivo.tar.gz
```
 
# Ficheros tar.bz2
## Comprimir

Para comprimir en tar.bz2, se hace uso del parámetro pipeline ( | ), que consiste en que “filtra” la salida de un comando a la entrada de otro, como es en este ejemplo: tar empaqueta los distintos ficheros o directorios y su salida lo pasa al comando bzip2 para que este lo comprima y el resultado de este, lo redirecciona ( > ) al fichero final tar.bz2
```bash
tar -c ficheros | bzip2 > archivo.tar.bz2
```
## Descomprimir
```bash
bzip2 -dc archivo.tar.bz2 | tar -xv
```
## Ver el contenido de un fichero tar.bz2
```bash
bzip2 -dc archivo.tar.bz2 | tar -t
```
 
# Ficheros zip
## Comprimir
```bash
zip archivo.zip ficheros-a-comprimir
```
## Descomprimir

```bash
unzip archivo.zip
```
## Para ver el contenido de un fichero zip
```bash
unzip -v archivo.zip
```
 
# Ficheros rar
## Comprimir
```bash
 rar -a archivo.rar ficheros
```
## Descomprimir

```bash
 unrar -x archivo.rar
```
## Para ver el contenido de un fichero rar
```bash 
 unrar -v archivo.rar

 unrar -l archivo.rar
```

# Introduction to Zip Command in Linux
## 1) -u Option

Updates the file in the zip archive. This also updates an existing entry in the zip archive, and only if it has been modified more now than the version already in the zip archive.

Command:
```bash
zip –u file_name.zip file.txt
```
Suppose we have the files in the current directory are listed below:

file1.txt
file2.txt
file3.txt
file4.txt

Command:
```bash
zip –u file_name.zip file5.txt
``` 

After updating file5.txt from file_name.zip file, the files will be restored with unzip command.

Command:
```bash
unzip file_name.zip
ls command
```

## 2) -d Option

It deletes the file from the zip archive. This option deletes the created zip file. Suppose we have the files in the current directory are listed below:

file1.txt,file2.txt,file3.txt,file4.txt,file5.txt

Syntax:
```bash
$zip –d file_name.zip file.txt
```
Command:
```bash
zip –d file_name.zip file5.txt
```
After removing file5.txt from file_name.zip file, the files will be restored using unzip command

Command:
```bash
unzip file_name.zip
ls command
```

## 3) -m Option

Will delete original/main files after zipping. It will move the files by making zip and delete the original files/folder.

If a directory becomes empty after deleting files, the respective directory is also deleted. No deletions are completed until the zip has created archive without any error. So this is useful in maintaining disk space, but ultimately unsafe while removing all input files.

Syntax:
```bash
zip –m file_name.zip file.txt
```
Suppose we have the files in the current directory are listed below:

file_1.txt,file_2.txt,file_3.txt,file_4.txt

Command :
```bash
zip –m file_name.zip *.txt
```
After the execution of this command on the terminal here is the result:

Command:
```bash
ls command
```

## 4) -x Option

It will exclude files when we are going to create the zip. Let say you are going to zip all the files in the present directory and want to exclude few files which are not needed. So you can exclude these files which are not needed using the -x option.

Syntax:
```bash
zip –x file_name.zip file_to_be_excluded
```
Suppose we have the files in the current directory are listed below:

file_1.txt,file_2.txt,file_3.txt,file_4.txt

Command:
```bash
zip –x file_name.zip file_3.txt
```
This command while executing will compress every file except file_3.txt

Command:
```bash
ls command
```

## 5) -r Option

It will recursively zip the files inside it and then folders inside it.

Syntax:
```bash
zip –r file_name.zip directory_name

Suppose we have the files in the current directory (doc) are listed below:

a.pdf
b.pdf
c.pdf

Command:

zip –r filedir.zip doc
```
## 6) -v Option

Using the Verbose mode option we will print diagnostic version information. This option will display the progress indicator during compression and request verbose information about the zip structure.

Syntax:
```bash 
zip –v file_name.zip file.txt

Suppose we have the files in the current directory are listed below:

file_1.txt,file_2.txt,file_3.txt,file_4.txt

Command:

zip -v file1.zip *.txt
```
# SHUTDOWN
## Shutdown system without specifying arguments of shutdown command

By running mentioned below command your System will be shutdown using shutdown command:
```bash
$ sudo shutdown

The system will shut down after 1 minute as the default time is 1 minute.
```
## Shutdown System Immediately using shutdown command

We can shut down our system immediately without waiting for default time of 1 minute using “now” after shutdown command by below mentioned command:
```bash
sudo shutdown now
```
## Shutdown System after specified time using shutdown command

To shut down system after specified time, we use time argument with shutdown command so its syntax would become:
```bash
sudo shutdown [time]
```
The time can have two formats; hh:mm set time according to timezone and +m will shut down System after specified minutes.

To shut down System at 11:50 or 5 min after you run the below mentioned commands:
```bash
sudo shutdown 11:50
sudo shutdown +5
```
## Shutdown System by sending message using shutdown command

We can also send notification at the time of shutdown by using message argument after time in shutdown command. The mentioned message will be aired at the time of shutdown, run the below mentioned command to broadcast “System update” message with the help of shutdown command:
```bash
$ sudo shutdown +2 “System update”

It will broadcast a message after shutdown command execution.
```
## Reboot System using shutdown command

We can also reboot our system using using “-r” flag after shutdown command as mentioned below:
```bash
$ sudo shutdown -r

It will start reboot after default time of “1 minute”
```
## Reboot system by specifying time and sending message using “shutdown” command

We can also fix the time for reboot as we do for shutdown. To reboot System after 3 min by airing “Update System” run the below mentioned command:
```bash
$ sudo shutdown +3 –r “Update System”
```
## Cancel shutodwn using "shutdown" command
After you run the command "shutdown" you can cancel it with the below command:
```bash
sudo shutdown -c
```
# Cómo usar ps, kill y nice para administrar procesos en Linux
## Cómo ver los procesos en ejecución en Linux
### Comando top

La forma más sencilla de averiguar qué procesos se están ejecutando en su servidor es ejecutar el comando top:
```bash 
$ top
```
La parte superior de la información ofrece estadísticas del sistema, como la carga del sistema y el número total de tareas.

Se puede ver fácilmente que hay 1 proceso en ejecución y 55 procesos en reposo (es decir, inactivos/que no usan los recursos de la CPU).

La parte inferior tiene los procesos en ejecución y las estadísticas de uso.
htop

Una versión mejorada de top, llamada htop, está disponible en los repositorios. Instálelo y pruebelo con siguientess comandos:
```bash 
sudo apt-get install htop

htop***
```

## Cómo usar ps para realizar una lista de procesos

top y htop proporcionan una buena interfaz para ver los procesos en ejecución, similar a la de un administrador de tareas gráfico.

Sin embargo, estas herramientas no siempre son lo suficientemente flexibles para cubrir adecuadamente todos los escenarios. Un poderoso comando llamado ps generalmente es la respuesta a estos problemas.

Cuando se invoca sin argumentos, el resultado puede ser un poco escaso:
```bash 
ps

  PID TTY          TIME CMD  1017 pts/0    00:00:00 bash  1262 pts/0    00:00:00 ps
```
Este resultado muestra todos los procesos asociados con el usuario actual y la sesión de terminal. Eso tiene sentido porque, actualmente, solo estamos ejecutando bash y ps con este terminal.

Para obtener un panorama más completo de los procesos en este sistema, podemos ejecutar lo siguiente:
```bash 
ps aux

USER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND root         1  0.0 
```
Estas opciones ordenan a ps que muestre los procesos de propiedad de todos los usuarios (independientemente de su asociación con el terminal) en un formato fácil de usar.

Para ver una vista de estructura jerárquica, en la que se ilustran las relaciones jerárquicas, podemos ejecutar el comando con las siguientes opciones:
```bash 
ps axjf
```
El proceso kthreadd se muestra como proceso principal de kstadd/0 y los demás

## Una nota sobre las ID de procesos

En Linux y sistemas tipo Unix, a cada proceso se le asigna un ID de proceso o PID. Esta es la forma en que el sistema operativo identifica y realiza un seguimiento de los procesos.

Una forma rápida de obtener el PID de un proceso es con el comando pgrep:
```
pgrep bash***

1017
```
Esto simplemente consultará el ID del proceso y lo mostrará en el resultado.

El primer proceso que se generó en el arranque, llamado init, recibe el PID “1”.
```bash
pgrep init***

1
```
Entonces, este proceso es responsable de engendrar todos los demás procesos del sistema. Los procesos posteriores reciben números PID mayores.

Un proceso principal es el proceso que se encargó de generarlo. Los procesos principales tienen un PPID, que puede ver en los encabezados de las columnas en muchas aplicaciones de administración de procesos, incluidos top, htop y ps.

Cualquier comunicación entre el usuario y el sistema operativo sobre los procesos implica traducir entre los nombres de procesos y los PID en algún momento durante la operación. Este es el motivo por el que las utilidades le indican el PID.
Las relaciones principal-secundario

Para crear un proceso secundario se deben seguir dos pasos: fork(), que crea un nuevo espacio de direcciones y copia los recursos propiedad del principal mediante copy-on-write para que estén disponibles para el proceso secundario; y exec(), que carga un ejecutable en el espacio de direcciones y lo ejecuta.

En caso de que un proceso secundario muera antes que su proceso principal, el proceso secundario se convierte en un zombi hasta que el principal haya recopilado información sobre él o haya indicado al núcleo que no necesita esa información. Luego, los recursos del proceso secundario se liberarán. Sin embargo, si el proceso principal muere antes que el secundario, init adoptará el secundario, aunque también puede reasignarse a otro proceso.
## Cómo enviar señales a los procesos en Linux

Todos los procesos en Linux responden a señales. Las señales son una forma de decirle a los programas que terminen o modifiquen su comportamiento.
### Cómo enviar señales a los procesos por PID

La forma más común de pasar señales a un programa es con el comando ```kill```.

Como es de esperar, la funcionalidad predeterminada de esta utilidad es intentar matar un proceso:
```bash
kill PID_of_target_process

Esto envía la señal TERM al proceso. La señal TERM indica al proceso debe terminar. Esto permite que el programa realice operaciones de limpieza y cierre sin problemas.
```
Si el programa tiene un mal comportamiento y no se cierra cuando se le da la señal TERM, podemos escalar la señal pasando la señal KILL:
```bash
kill -KILL PID_of_target_process

Esta es una señal especial que no se envía al programa.
```
En su lugar, se envía al núcleo del sistema operativo, que cierra el proceso. Eso se utiliza para eludir los programas que ignoran las señales que se les envían.

Cada señal tiene un número asociado que puede pasar en vez del nombre. Por ejemplo, puede pasar “-15” en lugar de “-TERM” y “-9” en lugar de “-KILL”.
### Cómo usar señales para otros fines

Las señales no solo se utilizan para cerrar programas. También pueden usarse para realizar otras acciones.

Por ejemplo, muchos demonios se reinician cuando reciben la señal HUP o la señal de colgar. Apache es un programa que funciona así.
```bash
sudo kill -HUP pid_of_apache

El comando anterior hará que Apache vuelva a cargar su archivo de configuración y reanude sirviendo contenidos.
```
Puede enumerar todas las señales que puede enviar con kill escribiendo lo siguiente:
```bash
kill -l***

1) SIGHUP	 2) SIGINT	 3) SIGQUIT	 4) SIGILL	 5) SIGTRAP  6) SIGABRT	 7) SIGBUS	 8) SIGFPE	 9) SIGKILL	10) SIGUSR1 11) SIGSEGV	12) SIGUSR2	13) SIGPIPE	14) SIGALRM	15) SIGTERM . . .
```
### Cómo enviar señales a los procesos por nombre

Aunque la forma convencional de enviar señales es mediante el uso de PID, también hay métodos para hacerlo con nombres de procesos regulares.

El comando pkill funciona casi exactamente igual que kill, pero funciona con un nombre de proceso en su lugar:
```bash
pkill -9 ping
```
El comando anterior es el equivalente a:
```bash
kill -9 `pgrep ping`
```
Si quiere enviar una señal a todas las instancias de un determinado proceso, puede utilizar el comando killall:
```bash
killall firefox

El comando anterior enviará la señal TERM a todas las instancias de firefox que se estén ejecutando en el equipo.

Cómo ajustar las prioridades de los procesos
```
A menudo, querrá ajustar qué procesos reciben prioridad en un entorno de servidor.

Algunos procesos pueden considerarse como una misión crítica para su situación, mientras que otros pueden ejecutarse siempre que haya recursos sobrantes.

Linux controla la prioridad a través de un valor llamado niceness.

Las tareas de alta prioridad se consideran menos buenas porque no comparten los recursos tan bien. Por otro lado, los procesos de baja prioridad son buenos porque insisten en tomar solo los recursos mínimos.

Cuando ejecutamos top al principio del artículo, había una columna marcada como “NI”. Este es el valor bueno del proceso:
```bash
top***

Los valores buenos pueden oscilar entre “-19/-20” (máxima prioridad) y “19/20” (mínima prioridad) dependiendo del sistema.
```
Para ejecutar un programa con un determinado valor bueno, podemos usar el comando nice:
```bash
nice -n 15 command_to_execute
```
Esto solo funciona cuando se inicia un nuevo programa.

Para alterar el valor bueno de un programa que ya se está ejecutando, usamos una herramienta llamada renice:
```bash 
renice 0 PID_to_prioritize
```
Nota: Mientras que nice funciona necesariamente con un nombre de comando, renice funciona invocando al PID del proceso

# ps y kill - buscar y eliminar procesos en Linux
 A veces es necesario buscar y eliminar procesos del sistema, es decir matarlos, para que dejen de ejecutarse por diversos motivos. Para buscar procesos podemos hacerlo de dos formas desde el Monitor de Sistema o desde la linea de comandos,

## Con el comando ps buscamos procesos en ejecución en el sistema.

ps -ef
Muestra los procesos que hay en el sistema ejecutándose.

## Si queremos buscar un proceso en concreto, por ejemplo el filezilla
```bash
ps -ef | grep filezilla
```

## Para eliminar el proceso del filezilla hay que utilizar el comando
```bash 
kill -9 número-de-proceso
O el comando

killall nombre-del-proceso
```

## Por ejemplo si queremos eliminar el proceso del filezilla podemos hacer dos cosas, buscarlo
```bash
ps -ef | grep filezilla
Y cuando lo encontramos eliminarlo con el id

Con el número de id de proceso ( 26005 ) lo eliminamos

kill -9 26005
```
## O podemos eliminarlo por le nombre
```bash
killall filezilla 
```
# LISTA DE COMANDOS
## COMANDO PS
```bash 
ps -e    

(-e muestra todos los procesos)
  
  PID TTY          TIME CMD
    1 ?        00:00:01 init
    2 ?        00:00:00 kthreadd
    3 ?        00:00:00 migration/0
    4 ?        00:00:00 ksoftirqd/0

ps -ef    

(-f muestra opciones completas)

UID        PID  PPID  C STIME TTY          TIME CMD
root         1     0  0 10:12 ?        00:00:01 init [5]
root         2     0  0 10:12 ?        00:00:00 [kthreadd]
...
root      6130  5662  0 10:24 pts/0    00:00:00 su -
root      6134  6130  0 10:24 pts/0    00:00:00 -bash
sergon    6343  5604  0 10:28 ?        00:00:00 kio_file [kdeinit] file /home/sergon/tmp/ksocket-sergon/kl
root      6475  6134  0 10:38 pts/0    00:00:00 ps -ef

ps -eF    

(-F muestra opciones completas extra)

UID        PID  PPID  C    SZ   RSS PSR STIME TTY          TIME CMD
root         1     0  0   412   556   1 16:59 ?        00:00:01 init [5]
root         2     0  0     0     0   1 16:59 ?        00:00:00 [kthreadd]
sergon    8326  8321  0   902  1272   0 17:07 ?        00:00:00 /bin/sh /usr/lib/firefox-2.0.0.8/run-mozilla.sh /usr/lib/f
sergon    8331  8326  4 53856 62604   0 17:07 ?        00:00:50 /usr/lib/firefox-2.0.0.8/mozilla-firefox-bin
sergon    8570  7726  2 15211 37948   0 17:17 ?        00:00:10 quanta

ps ax     

(formato BSD sin guión, a muestra todos, x sin mostrar tty)
  
  PID TTY      STAT   TIME COMMAND
    1 ?        Ss     0:01 init [5]
    2 ?        S<     0:00 [kthreadd]
    3 ?        S<     0:00 [migration/0]
    4 ?        S<     0:00 [ksoftirqd/0]

ps aux   

(formato BSD sin guión, u muestra usuarios y demás columnas)

USER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root         1  0.0  0.0   1648   556 ?        Ss   16:59   0:01 init [5]
root         2  0.0  0.0      0     0 ?        S<   16:59   0:00 [kthreadd]
root         3  0.0  0.0      0     0 ?        S<   16:59   0:00 [migration/0]
root         4  0.0  0.0      0     0 ?        S<   16:59   0:00 [ksoftirqd/0]
root         5  0.0  0.0      0     0 ?        S<   16:59   0:00 [migration/1]

ps -eo user,pid,tty   

(-o output personalizado, se indican los campos separados por coma, ver ps --help o ps L)

USER       PID TT
root         1 ?
root         2 ?
sergon    8570 tty 1
root      8876 pts/1

ps -eH  (muestra árbol de procesos)

ps axf  (lo mismo en formato BSD)

ps -ec  (el comando  que se esta ejecutando, sin la ruta, solo el nombre real)

ps -el  (muestra formato largo de varias columnas, muy práctico)

ps L    (No muestra procesos, lista todos los códigos de formatos)
```
## COMANDO PSTREE
Muestra los procesos en forma de árbol, pstree --help te da las opciones más comunes. Recomiendo uses lo uses con la opción -A y -G para que te un árbol con líneas con líneas estilo ASCII y de terminal VT100 respectivamente, puedes añadir también -u para mostrar entre paréntesis al usuario propietario del proceso: 
```bash
pstree -AGu
init---acpid
     |-atd(daemon)
     |-automount----2*[{automount}]
     |-avahi-daemon(avahi)
     |-beagled(sergon)----7*[{beagled}]
     |-beagled-helper(sergio)----3*[{beagled-helper}]
     |-compiz(sergon)----kde-window-deco
     |-console-kit-dae----61*[{console-kit-dae}]
     |-crond
     |-dbus-daemon(messagebus)
     |-dbus-daemon(sergio)
     |-dbus-launch(sergio)
     |-dcopserver(sergio)
     |-dhclient
     |-gam_server(sergio)
     |-gconfd-2(sergio)
     |-hald(haldaemon)----hald-runner(root)----hald-addon-acpi(haldaemon)
     |                                       |-hald-addon-cpuf
     |                                       |-hald-addon-inpu
     |                                       |-hald-addon-stor
     |-httpd---8*[httpd(apache)]
     |-2*[ifplugd]
     |-ipw3945d
     |-kaccess(sergio)
```
## COMANDO KILL
El comando kill, que literalmente quiere decir matar, sirve no solo para matar o terminar procesos sino principalmente para enviar señales (signals) a los procesos. La señal por default (cuando no se indica ninguna es terminar o matar el proceso), y la sintaxis es kill PID, siendo PID el número de ID del proceso. Asi por ejemplo, es posible enviar una señal de STOP al proceso y se detendrá su ejecución, después cuando se quiera mandar una señal de CONTinuar y el proceso continuara desde donde se quedo.
```bash
kill -l    

(lista todas las posibles señales que pueden enviarse a un proceso)

1) SIGHUP       2) SIGINT       3) SIGQUIT      4) SIGILL
 5) SIGTRAP      6) SIGABRT      7) SIGBUS       8) SIGFPE
 9) SIGKILL     10) SIGUSR1     11) SIGSEGV     12) SIGUSR2
13) SIGPIPE     14) SIGALRM     15) SIGTERM     16) SIGSTKFLT
17) SIGCHLD     18) SIGCONT     19) SIGSTOP     20) SIGTSTP
21) SIGTTIN     22) SIGTTOU     23) SIGURG      24) SIGXCPU
25) SIGXFSZ     26) SIGVTALRM   27) SIGPROF     28) SIGWINCH
29) SIGIO       30) SIGPWR      31) SIGSYS      34) SIGRTMIN
35) SIGRTMIN+1  36) SIGRTMIN+2  37) SIGRTMIN+3  38) SIGRTMIN+4
39) SIGRTMIN+5  40) SIGRTMIN+6  41) SIGRTMIN+7  42) SIGRTMIN+8
43) SIGRTMIN+9  44) SIGRTMIN+10 45) SIGRTMIN+11 46) SIGRTMIN+12
47) SIGRTMIN+13 48) SIGRTMIN+14 49) SIGRTMIN+15 50) SIGRTMAX-14
51) SIGRTMAX-13 52) SIGRTMAX-12 53) SIGRTMAX-11 54) SIGRTMAX-10
55) SIGRTMAX-9  56) SIGRTMAX-8  57) SIGRTMAX-7  58) SIGRTMAX-6
59) SIGRTMAX-5  60) SIGRTMAX-4  61) SIGRTMAX-3  62) SIGRTMAX-2
63) SIGRTMAX-1  64) SIGRTMAX

kill -9 11428        

(termina, mata un proceso completamente)

kill -SIGKILL 11428  

(Lo mismo que lo anterior)
```
## COMANDO KILLALL
El comando killall, que funciona de manera similar a kill, pero con la diferencia de en vez de indicar un PID se indica el nombre del programa, lo que afectará a todos los procesos que tengan ese nombre. Asi por ejemplo si se tienen varias instancias ejecutándose del proxy server squid, con killall squid eliminará todos los procesos que se esten ejecutando con el nombre 'squid'.

```bash
killall -l             
(lista de posibles señales)

killall -HUP httpd     

(manda una señal de "colgar", detenerse releer sus archivos de configuración y reiniciar)

killall -KILL -i squid 

(manda señal de matar a todos los procesos squid pero pide confirmación en cada uno)
```
## COMANDO NICE
Permite cambiar la prioridad de un proceso. Por defecto, todos los procesos tienen una prioridad igual ante el CPU que es de 0. Con nice es posible iniciar un programa (proceso) con la prioridad modificada, más alta o más baja según se requiera. Las prioridades van de -20 (la más alta) a 19 la más baja. Solo root o el superusuario puede establecer prioridades negativas que son más altas. Con la opción -l de ps es posible observar la columna NI que muestra este valor.
```bash
nice             (sin argumentos, devuelve la prioridad por defecto )
0

nice -n -5 comando  

(inicia comando con una prioridad de -5, lo que le da más tiempo de cpu)
```
## COMANDO RENICE
Asi como nice establece la prioridad de un proceso cuando se incia su ejecución, renice permite alterarla en tiempo real, sin necesidad de detener el proceso.
```bash
nice -n -5 yes   (se ejecuta el programa 'yes' con prioridad -5)
                  (dejar ejecutando 'yes' y en otra terminal se analiza con 'ps')

ps -el

F S   UID   PID  PPID  C PRI  NI ADDR SZ WCHAN  TTY          TIME CMD
4 S     0 12826 12208  4  75  -5 -   708 write_ pts/2    00:00:00 yes

renice 7 12826

12826: prioridad antigua -5, nueva prioridad 7

ps -el

F S   UID   PID  PPID  C PRI  NI ADDR SZ WCHAN  TTY          TIME CMD
4 S     0 12826 12208  4  87   7 -   708 write_ pts/2    00:00:15 yes

(obsérvese el campo NI en el primer caso en -5, y en el segundo con renice quedó en 7, en tiempo real)
```
## COMANDO NOHUP Y &
Cuando se trata ejecutar procesos en background (segundo plano) se utiliza el comando nohup o el operador & . Aunque realizan una función similar, no son lo mismo.

Si se desea liberar la terminal de un programa que se espera durará un tiempo considerable ejecutándose, entonces se usa . Esto funciona mejor cuando el resultado del proceso no es necesario mandarlo a la salida estándar (stdin), como por ejemplo cuando se ejecuta un respaldo o se abre un programa Xwindow desde la consola o terminal. Para lograr esto basta con escribir el comando en cuestión y agregar al final el símbolo & (ampersand).
```bash
yes > /dev/null &

tar czf respaldo /documentos/* > /dev/null/ &   

konqueror & (con estos ejemplos se ejecuta el comando y se libera la terminal regresando el prompt)
```
Sin embargo lo anterior produce que el padre del proceso PPID que se invocó sea el proceso de la terminal en si, por lo que si cerramos la terminal o salimos de la sesión también se terminaran los procesos hijos que dependan de la terminal, no muy conveniente si se desea que el proceso continué en ejecución.

Para solucionar lo anterior, entonces se usa el comando nohup que permite al igual que '&' mandar el proceso y background y que este quede inmune a los hangups (de ahí su nombre nohup) que es cuando se cuelga o termina la terminal o consola de la cual se ejecutó el proceso.
```bash
nohup yes > /dev/null &

nohup czf respaldo /documentos/* > /dev/null/  

nohup konqueror 

Asi se evita que el proceso se "cuelgue" al cerrar la consola.
```
## COMANDO JOBS
Si por ejemplo, se tiene acceso a una única consola o terminal, y se tienen que ejecutar varios comandos que se ejecutarán por largo tiempo, se pueden entonces como ya se vió previamente con nohup y el operador '&' mandarlos a segundo plano o background con el objeto de liberar la terminal y continuar trabajando.

Pero si solo se está en una terminal esto puede ser difícil de controlar, y para eos tenemos el comando jobs que lista los procesos actuales en ejecución:
```bash
yes > /dev/null &

[1] 26837

ls -laR > archivos.txt &

[2] 26854

jobs

[1]-  Running                 yes >/dev/null &
[2]+  Running                 ls --color=tty -laR / >archivos.txt &
```
En el ejemplo previo, se ejecutó el comando yes y se envió a background (&) y el sistema devolvió [1] 26837, indicando asi que se trata del trabajo o de la tarea [1] y su PID, lo mismo con la segunda tarea que es un listado recursivo desde la raíz y enviado a un archivo, esta es la segunda tarea.

Con los comandos fg (foreground) y bg background es posible manipular procesos que esten suspendidos temporalmente, ya sea porque se les envió una señal de suspensión como STOP (20) o porque al estarlos ejecutando se presionó ctrl-Z. Entonces para reanudar su ejecución en primer plano usaríamos fg:
```bash
jobs

[1]-  Stopped                 yes >/dev/null &
[2]+  Stopped                ls --color=tty -laR / >archivos.txt &

fg %1

jobs

[1]+  Running                 yes >/dev/null &
[2]-  Stopped                ls --color=tty -laR / >archivos.txt &
``` 
Obsérvese como al traer en primer plano al 'job' o proceso 1, este adquirió el símbolo [+] que indica que esta al frente. Lo mismo sería con bg que volvería a reinicar el proceso pero en segundo plano. Y también es posible matar los procesos con kill indicando el número que devuelve jobs: kill %1, terminaría con el proceso en jobs número 1.
## COMANDO TOP 
Una utilería muy usada y muy útil para el monitoreo en tiempo real del estado de los procesos y de otras variantes del sistema es el programa llamado top, se ejecuta desde la línea de comandos, es interactivo y por defecto se actualiza cada 3 segundos.
```bash
top

top - 13:07:30 up 8 days,  6:44,  4 users,  load average: 0.11, 0.08, 0.08
Tasks: 133 total,   1 running, 131 sleeping,   0 stopped,   1 zombie
Cpu(s):  0.0%us,  0.2%sy,  0.0%ni, 99.7%id,  0.0%wa,  0.0%hi,  0.2%si,  0.0%st
Mem:    497356k total,   472352k used,    25004k free,    21500k buffers
Swap:  1156640k total,   257088k used,   899552k free,    60420k cached

  PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND
26156 sergon    15   0  2160 1016  784 R    1  0.2   0:00.93 top
    1 root      15   0  2012  616  584 S    0  0.1   0:00.98 init
    2 root      RT   0     0    0    0 S    0  0.0   0:00.29 migration/0
    3 root      34  19     0    0    0 S    0  0.0   0:00.00 ksoftirqd/0
    4 root      RT   0     0    0    0 S    0  0.0   0:00.00 watchdog/0
    5 root      RT   0     0    0    0 S    0  0.0   0:00.38 migration/1
```

Estando adentro de la apliación, presionando 'h' muestra una ayuda de los posibles comandos que permiten configurar top, por ejemplo, al presionar 's' pregunta por el tiempo en segundos de actualización, etc.

Estas son algunas de las herramientas, las más importantes y usadas, para adminsitrar procesos, hay varios programas en ambientes gráficos que en una sola pantalla permiten todo lo anterior y más, y en línea de comandos te recomiendo htop, que es como un top pero en esteroides.

# Comandos Linux para Discos duros y particiones
## COMANDOS
### LSCSI
El comando lsscsi muestra info de los dispositivos scsi/SATA conectados

Primero hemos de instalar el paquete lsscsi con:
```bash
apt-get install lsscsi
```
y lo ejecutaremos con:
```bash
sudo lsscsi
```
### LSBLK
lsblk es un comando que se utiliza para mostrar información acerca de todos los dispositivos de bloque disponibles. Ejemplos de dispositivos de bloque son los discos duros, unidades flash, CD-ROM …
 
Los detalles que muestra incluyen el punto de montaje y el tamaño total de la partición o el bloque. Lo que no incluye es el espacio libre y el disponible.
 
Mostrar todos los dispositivos:
```bash
lsblk -a
``` 
Mostrar columna tamaño en bytes:
```bash
lsblk -b
```
### FDISK
El propósito principal del comando fdisk es modificar las particiones del sistema de archivos, pero podemos utilizarlo para mostrar info de las particiones del sistema de archivos con la opción -l:
```bash
fdisk -l
```
### SFDISK
sfdisk es parecido a fdisk, pero con más características, ya que nos permite ver los volúmenes físicos (podemos ver los discos físicos) y también los volúmenes lógicos. Puede mostrar el tamaño de cada partición en MB:
```bash
sudo sfdisk -l -uM
```
### DF
df no es una utilidad de partición, pero imprime detalles acerca de los sistemas de archivos montados.
Por tanto nos mostrará también los discos físicos. El comando a utilizar es:
```bash
df -h
```
### CFDISK
CFdisk es un editor de particiones Linux con una interfaz de usuario interactiva. Puede ser utilizado hacer una lista de las particiones existentes, así como crear o modificar ellos.
### PARTED
Parted es otra utilidad de línea de comando para enumerar las particiones y modificarlos si es necesario.
He aquí un ejemplo que muestra los detalles de partición:
```bash
parted -l
```
### BLKID
blkid muestra los atributos como el uuid y el tipo de sistema de archivos de los dispositivos de bloque (particiones y volúmenes de almacenamiento).+
## CREAR PARTICIONES CON FSDISK EN LINUX
Con el comando fdisk podremos crear particiones en discos duros, USB´s y en general en dispositivos de almacenamiento.

Lo primero nos aseguramos de que nuestro dispositivo se encuentre conectado. Así que tal y como hemos visto, usaremos el comando lsblk o df-h para localizar el nuevo disco USB conectado:
```bash
lsblk
```
 

muestra nuestro dispositivo conectado como dispositivo /dev/sdb , y vemos también que está montado (tendremos que desmontarlo para crear una nueva partición y formatearla después).
```bash
lsblk dispositivos
```

Comenzamos usando fdisk en el dispositivo seleccionado:
```bash
fdisk /dev/sdb

 
Si el disco aún tiene alguna partición y queremos eliminarla, pulsamos primero sobre la opción

d

y así borraremos la partición;
 

luego escribimos los cambios al disco:

w
```
Después para crear la nueva partición, elegimos de nuevo el dispositivo donde queremos crearla; recordemos que es /dev/sdb
```bash
fdisk /dev/sdb

 

Creamos nueva tabla de particiones

o

 

creamos una nueva partición

n

 

primaria (p por defecto)
que ocupe todo el disco

y escribimos los cambios

w
```
## FORMATEAR PARTICIONES EN LINUX


Podemos formatear rápidamente al formato ext 4 con el comando ```mkfs```:
```bash
mkfs.ext4 /dev/sdb1
```
 
Y después usamos el comando blkid, para mostrar las particiones del disco sdb, y aparecerá la nueva partición /dev/sdb1 que acabamos de formatear en Linux, con el formato ext4.


# FIREWALL

Vamos a explicarte qué es un firewall o cortafuegos, soluciones diseñadas para proteger tu ordenador que pueden complementarse o integrarse en un antivirus. Son tipos de protección que posiblemente ya estés utilizando sin darte cuenta, pero eso no quiere decir que debas despreocuparte y no conocer lo que hacen y lo que no hacen.

Empezaremos explicándote de forma sencilla y entendible qué es un cortafuegos y para qué sirve exactamente. Luego, pasaremos a explicarte cómo funcionan diciéndote los dos tipos principales de cortafuegos, y terminaremos recordándote que no debes delegar 100% en ellos ni ninguna otra solución para proteger tu ordenador.
Qué es un cortafuegos y para qué sirve

El cortafuegos o firewall en inglés, en el mundo de la informática es un sistema de seguridad para bloquear accesos no autorizados a un ordenador mientras sigue permitiendo la comunicación de tu ordenador con otros servicios autorizados. También se utilizan en redes de ordenadores, especialmente en intranets o redes locales. Se trata de una de las primeras medidas de seguridad que empezó a implementarse en los ordenadores tras el nacimiento de Internet.

Su origen se remonta a finales de la década de los 80, cuando Internet daba sus primeros pasos y los primeros hackers descubrieron que con esta nueva red podían infiltrarse y hacer travesuras en los ordenadores de otras personas, lo que llevó a a una serie de importantes violaciones de seguridad y ataques de malware.
Once programas para eliminar malware gratis y cómo utilizarlos


Internet necesitaba ser más segura para extenderse, por lo que varios investigadores empezaron a desarrollar las primeras versiones de cortafuegos informáticos en 1988 como método para el filtrado de los paquetes digitales que le llegaban a un ordenador.

Con el tiempo fueron evolucionando para conseguir analizar mejor la información entrante y filtrar las posibles amenazas. La finalidad siempre ha sido la misma que siguen teniendo hoy, la de establecer unos criterios de seguridad, y filtrar todas las comunicaciones que entran o salen del ordenador para interceptar las que no cumplan con ellos y dejar pasar al resto.

Estos criterios van variando y evolucionando con el tiempo para mantenerse actualizados frente a unos ataques también en constante evolución. Es importante que sepas que los cortafuegos no eliminan el malware que intenta entrar, sólo trata de bloquear su acceso. Si ya tienes un virus en el ordenador el cortafuegos no podrá hacer tanto, y tendrás que combinarlo con un antivirus.
Cómo funcionan los cortafuegos
Internet

Los cortafuegos pueden ser de dos tipos, pueden ser software, de hardware o una combinación de ambos. Esto quiere decir que pueden ser aplicaciones que instales en tu ordenador o dispositivos que se conecten a él para controlar el tráfico.

Los cortafuegos físicos pueden ser productos independientes o venir directamente integrados en un router. Los independientes se suelen situar entre el punto de acceso a Internet y el switch que se encarga de distribuir la conexión entre los ordenadores de una misma red. El hecho de que vaya antes de la distribución de la red entre los equipos significa que todos los que haya en una red interna quedan protegidos.

Son buenos para muchos ataques exteriores, sobre todo para las redes internas e intranets. Esto les convierte en buenas herramientas para empresas y grandes redes. Pero no son tan seguros con muchos tipos de ataque que vengan a través de otra aplicación, como los troyanos o las amenazas que recibes a través de correos electrónicos fraudulentos.



Los más populares en los usuarios de a pié son los cortafuegos en forma de software, que son aplicaciones que pueden instalarse en los ordenadores. Además de interceptar los intentos de acceso desde el exterior también suelen incluir protecciones adicionales contra los troyanos y virus de correo más comunes. Su desventaja es que sólo protegen de manera individual a cada ordenador que los tiene instalados.

Ahora vamos a hablar de sus funciones. Como te hemos explicado, los cortafuegos se sitúan entre la red local e Internet, y su misión es protegerte bloqueando el tráfico no solicitado o que considere peligroso. Pero puede hacer otras cosas, como aprovechar que analiza el tráfico que entra o sale para configurar filtros para diferentes tipos de tráfico con los que decidir qué hacer con él.

En estas configuraciones se pueden hacer muchas cosas, como por ejemplo permitir únicamente las conexiones a servidores de direcciones IP concretas, descartando el resto por seguridad. Esto evidentemente a nivel doméstico no es muy efectivo, te impide navegar con facilidad, pero en ámbitos empresariales o más cerrados puede servir.

Al poder analizar el tráfico saliente, también pueden llegar a detectar si hay algún malware comunicándose con la red, monitorizando el uso de redes empresariales, o filtrando el tráfico. Además, también puede configurarse, por ejemplo, para que sólo el navegador de los ordenadores de una empresa pueda conectarse a Internet, bloqueando el acceso del resto de aplicaciones por seguridad.
Que no te hagan bajar la guardia

Siempre puedes instalar aplicaciones de firewall de terceros. Pero has de saber que sistemas operativos como Windows 10 ya llevan cortafuegos integrados, y muchos de los routers que hay hoy en día también tienen sus módulos para filtrar posibles amenazas, aunque suelen ser protecciones bastante básicas.

Aun así, tanto si tienes un cortafuegos integrado como si decides comprar o instalar uno, nunca debes delegar exclusivamente en él a la hora de protegerte. Sí, añaden una capa de seguridad extra a tu ordenador, pero eso no significa que no vayas a estar amenazado por ningún tipo de malware.

Lo mejor siempre es complementar tus protecciones. Si tienes un sistema operativo como Windows 10, que integra un antivirus propio con firewall, es verdad que posiblemente no necesites instalar aplicaciones de terceros. Pero eso no evita que tengas que seguir tomando muchas precauciones y navegar con precaución para evitar las amenazas más comunes. Lo mismo pasa si tienes sólo un firewall o un antivirus, puedes complementarlos aunque sin dejar de bajar la guardia.

