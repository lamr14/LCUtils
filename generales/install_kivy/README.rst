============
install-kivy
============

Instala Kivy con Python 3 en un ambiente virtual.
Realiza los siguientes pasos:

- Crea una carpeta de proyecto
- Crea el ambiente virtual
- Emula la opción --always-copy de virtualenv
  que no funciona, requerida para instalar
  pygame.
- Instala Cython
- Descarga pygame, aplica un parche y
  lo instala.
- Instala Kivy
- Inicia el repositorio de git en la carpeta
  del proyecto.

El script puede ser ejecutado más de una vez,
en cada ocasión realiza solamente los pasos
que no han terminado.

Ha sido probado en las siguientes distribuciones:

- Fedora 20 con Python 3.3
- Debian testing con Python 3.4
