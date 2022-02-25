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