---
permalink: /
title: "<span style="color:purple">10 Comandos basicos de Linux</span>"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



pwd - Print Working Directory.
======

El comando, pwd, significa "Directorio de trabajo de impresión". Esencialmente, escribes ese comando, y te dará la ruta de archivo exacta para el archivo o carpeta en la que estás.

cd - Change directory 
======

Esto significa "cambiar de directorio" o, en términos más simples, cambiar en qué carpeta estamos.

Al usar el comando, cd, podemos decirle en qué dirección moverse añadiendo más al comando.

cd or cd ~  - Nos lleva al directorio principal.

cd < folder name> - Nos lleva un paso adelante a la carpeta que se ha escrito.

cd ..- Nos lleva un nivel atrás a la carpeta padre.

cd ../..- Nos mueve hacia atrás dos niveles. Agrega más /... para cada nivel en el que queramos navegar hacia arriba.

Al escribir el nombre de una carpeta o un archivo, y está sólo un paso por delante, puedes pulsar "Tab" y se rellenará automáticamente en la carpeta/nombre de archivo.

ls
======

Ahora que estamos en una carpeta, puede que queramos ver lo que hay en esa carpeta. Al ejecutar el comando, ls, nos mostrará todo lo que hay en esa carpeta.

clear
======
Este comando hace exactamente lo que suena; "limpia" su terminal. A veces es más fácil hacer borrón y cuenta nueva cuando se intenta enfocar.

mkdir
======
Si hiciéramos clic con el botón derecho del ratón directamente en la vista del escritorio, aparecería ese pequeño menú, podríamos hacer clic en "Nueva carpeta", y entonces aparecería una nueva carpeta para que le pongamos un nombre. Este comando hace esa misma funcionalidad.

mkdir significa "Hacer directorio" o simplemente, hacer una nueva carpeta.

Desde donde sea que se ejecute este comando, creará la nueva carpeta en ese lugar. Así que navega a la ubicación deseada usando comandos cd, y luego escribe             mkdir <folder name>
mkdir <nombre de la carpeta>.

Para entrar en esa nueva carpeta, ejecutaríamos el comando: cd <folder name>.


touch 
======
Ahora que sabemos cómo crear una carpeta, vamos a crear algunos archivos dentro de esa carpeta. Si siguiéramos los comandos anteriores:

1.	mkdir new-folder
2.	cd new-folder


Ahora deberíamos estar en el directorio/carpeta "nueva carpeta". Vamos a crear un archivo dentro de esa carpeta. Ejecutando el siguiente comando, eso crearía un archivo:

touch new-file - este no tiene extensión, así que querríamos añadir .html, `.txt`, o cualquier otra extensión necesaria.

open 
======
Abrir un archivo o una carpeta escribiendo el comando:

open <folder/file name>

history 
======
¿Quiere saber todos los comandos que se han ejecutado en la sesión de terminal actual? Ejecute el comando, el history para verlos.

¡Otro truco! Usa las flechas "arriba" y "abajo" para navegar a través de los comandos anteriores.

¿Quieres limitar el número de comandos que muestra? Añade un número al comando: "Historia 10" mostraría los últimos 10 comandos escritos.

cat
======
Este comando nos permite ver el contenido de un archivo en particular. Necesitaríamos declarar el archivo en particular para que este comando funcione.

Si conocemos la ruta de acceso al archivo, podríamos ejecutarlo:

cat /Desktop/new-folder/new-file

O podríamos navegar desde nuestra carpeta de inicio a la carpeta nueva y luego ejecutar el comando.

1.	cd Desktop
2.	cd new-folder
3.	cat new-file

say 
======
Este es uno divertido. No es necesario para la navegación, pero hace que tu ordenador te hable.

Escriba: say "anything here"
diga "cualquier cosa aquí" y su ordenador dirá eso. ¡No olvides las citas de este comando!

¡Bonus Tip!
======
¿Quieres cambiar la Terminal para que se parezca a la Matriz? ¿Fondo negro, letras verdes?

En la esquina superior izquierda de la pantalla, haga clic donde dice "Terminal".
Haga clic en "Preferencias..."
Haga clic en "Perfiles"
En la lista de la izquierda, haz clic en "Homebrew Default"
Haga clic en "Por defecto" en la parte inferior.
Salga de la terminal y vuelva a abrirla para ver esos cambios. Ahora podemos codificar y lucir bien cuando nuestros amigos miren sobre nuestro hombro para ver qué es lo que estamos haciendo. Uh, sólo estamos haciendo carpetas y borrándolas, ¡pero ellos no lo saben! 🙂
