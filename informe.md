# Práctica de creación y manipulación de archivos en Linux

## 1. Título

Creación y manejo de archivos y carpetas utilizando comandos de Linux en Git Bash.

## 2. Tiempo de duración

El tiempo aproximado para realizar esta práctica fue de 60 a 90 minutos.

## 3. Fundamentos

Linux es un sistema operativo que permite trabajar con archivos, carpetas y programas. Una de las formas de utilizarlo es mediante la terminal, donde se escriben comandos para realizar diferentes tareas sin necesidad de utilizar el mouse.

Para esta práctica utilicé Git Bash, una herramienta que permite ejecutar muchos comandos de Linux desde Windows. Con ella pude crear carpetas, trabajar con archivos de texto y comprobar los resultados de cada operación.

Durante el ejercicio utilicé varios comandos. Por ejemplo, `mkdir` sirve para crear carpetas, `ls` permite ver los archivos y directorios que hay en una ubicación y `cd` se utiliza para entrar en otra carpeta o cambiar de ubicación. Estos comandos son útiles para moverse por los directorios y mantener los archivos organizados.

También aprendí a utilizar `cp` para copiar archivos y `mv` para moverlos o cambiarles el nombre. El comando `cat` permite mostrar el contenido de un archivo de texto. Para eliminar archivos se utiliza `rm`, mientras que `rmdir` sirve para borrar una carpeta cuando está vacía.

Otro tema que practiqué fue la redirección de información. El símbolo `>` permite guardar el contenido de un comando en un archivo, reemplazando lo que tenía antes. En cambio, `>>` sirve para añadir información al final sin borrar el contenido existente. Esto lo utilicé para crear un archivo de resumen y agregar una línea nueva.

Por último, trabajé con el comando `history`, que muestra los comandos utilizados en la terminal. Al combinarlo con una tubería (`|`) y el comando `tee`, se puede guardar esa información en un archivo.

Esta práctica me ayudó a conocer mejor la terminal y a entender cómo se pueden realizar tareas sencillas de organización y manejo de archivos mediante comandos.

![Terminal de Git Bash](capturas/Ima1.png)
**Figura 3-1.** Terminal de Git Bash utilizada durante la práctica.




## 4. Conocimientos previos

Para realizar esta práctica fue necesario conocer algunos conceptos básicos:

- Qué es un sistema operativo.
- Qué diferencia hay entre un archivo y una carpeta.
- Cómo abrir y utilizar Git Bash.
- Cómo escribir comandos en la terminal.
- Cómo crear, copiar, mover y eliminar archivos.
- Para qué sirven los símbolos `>` y `>>`.
- Cómo guardar la información obtenida al ejecutar un comando.

## 5. Objetivos a alcanzar

- Aprender a utilizar algunos comandos básicos de Linux.
- Crear carpetas para organizar los archivos de la práctica.
- Crear archivos de texto y trabajar con su contenido.
- Practicar la copia, el movimiento y la eliminación de archivos.
- Comprender cómo funciona la redirección de información.
- Guardar el historial de comandos utilizados durante el ejercicio.

## 6. Equipo necesario

- Una computadora con Windows.
- Git Bash instalado.
- Visual Studio Code o un editor de texto.
- Acceso a Internet.
- Una cuenta de GitHub para subir el informe y los archivos solicitados.

## 7. Material de apoyo

- Guía de la práctica proporcionada por el docente.
- Git Bash para ejecutar los comandos.
- Documentación de Bash: https://www.gnu.org/software/bash/manual/
- Git for Windows: https://gitforwindows.org/
- Plantilla del informe: https://github.com/maguaman2/informe-tendencias

## 8. Procedimiento



**Paso 1. Crear las carpetas**


Primero creé la carpeta principal `proyecto_comandos`. Dentro de ella preparé las carpetas `documentos`, `imagenes` y `scripts` para organizar los archivos de la práctica.



**Paso 2. Crear el archivo de notas**


Después creé el archivo `notas.txt` dentro de la carpeta `documentos`. Escribí tres líneas relacionadas con los comandos que estaba aprendiendo.

**Paso 3. Copiar y mover el archivo**



Copié `notas.txt` a la carpeta `scripts` y cambié el nombre de la copia a `backup_notas.txt`. Luego moví ese archivo a la carpeta `imagenes`.

**Paso 4. Crear el resumen**

Utilicé el comando `cat` junto con el símbolo `>` para guardar el contenido de `notas.txt` en un nuevo archivo llamado `resumen.txt`. Después utilicé `>>` para añadir una frase al final del archivo sin perder las líneas anteriores.

**Paso 5. Eliminar el archivo y la carpeta**

Cuando terminé de trabajar con la copia, eliminé `backup_notas.txt` utilizando `rm`. Como la carpeta `imagenes` quedó vacía, pude eliminarla con `rmdir`.

**Paso 6. Guardar el historial de comandos**

Finalmente, utilicé `history` junto con una tubería y `tee` para guardar el historial de comandos en un archivo de texto con el nombre solicitado para la tarea.

**Figura 8-1.** Comandos ejecutados en Git Bash durante el procedimiento.

*En este apartado se debe insertar una captura real donde se vean algunos de los comandos utilizados.*

## 9. Resultados esperados

Al terminar la práctica, pude trabajar con archivos y carpetas desde Git Bash y comprobar cómo funcionan varios comandos de Linux.

Creé la estructura de carpetas solicitada y el archivo `notas.txt` con tres líneas. También practiqué cómo copiar un archivo, cambiarle el nombre y moverlo a otra ubicación. Después creé `resumen.txt` y agregué una línea nueva sin borrar el contenido anterior.

Además, eliminé el archivo de respaldo y la carpeta que había quedado vacía. Por último, guardé el historial de comandos en un archivo de texto.

Con esta actividad comprendí mejor para qué sirven los comandos básicos y cómo pueden ayudar a organizar archivos sin tener que realizar todas las operaciones desde el explorador de Windows.

**Figura 9-1.** Primera evidencia de la práctica.

![Captura 1](capturas/Ima1.png)

**Figura 9-2.** Segunda evidencia de la práctica.

![Captura 2](capturas/Ima2.png)

**Figura 9-3.** Tercera evidencia de la práctica.

![Captura 3](capturas/Ima3.png)

**Figura 9-4.** Cuarta evidencia de la práctica.

![Captura 4](capturas/Ima4.png)

**Figura 9-5.** Quinta evidencia de la práctica.

![Captura 5](capturas/Ima5.png)

**Figura 9-6.** Sexta evidencia de la práctica.

![Captura 6](capturas/Ima6.png)

**Figura 9-7.** Séptima evidencia de la práctica.

![Captura 7](capturas/Ima7.png)

## 10. Bibliografía

- GNU Project. (s. f.). *Bash Reference Manual*. https://www.gnu.org/software/bash/manual/
- Git for Windows. (s. f.). *Git for Windows*. https://gitforwindows.org/
- The Linux Documentation Project. (s. f.). *The Linux Documentation Project*. https://tldp.org/