# Practica-MD
En este repositorio crearemos una guía de como configurar Git paso a paso

# GUIA PARA CONFIGURAR GIT PASO A PASO
---

1. Instalaremos Git Bash desde la web oficial [Pagina Oficial](https://git-scm.com/install/windows) 
seleccionando nuestro SO requerido Windows/Linux/MacOS.

<img width="776" height="373" alt="{7AF591C8-D773-4247-992A-0EAD0D301858}" src="https://github.com/user-attachments/assets/2662b812-ed9a-4d0f-a25a-45096312a726" />

2. Abriremos la consola de Git
 <img width="712" height="104" alt="image" src="https://github.com/user-attachments/assets/2e4e632f-155e-4467-a6ea-1d84989ee0f6" />

Deberá aparecernos de esta forma 👆🏻

2.1 Verificaremos la instalacion de Git

Verificamos usando el comando git --version 

<img width="216" height="70" alt="{3E60667B-1AD3-41B7-934E-DFB323547C55}" src="https://github.com/user-attachments/assets/35b70dd6-9d55-4d0c-98ef-6469c708217b" />

2.2 Establecer nombre de usuario y correo electronico

Estableceremos el nombre que acompañara cada uno de los commits que hagamos
Para ello usaremos el comando git config --global user.name "aqui va nuestro nombre y apellido"

Para el correo es necesario usar la misma direccion registrada en GitHub para vincular la autoria
Usaremos el comando git config --global user.email "micorreo@ejemplo.com"

3. Configurar el nombre de la rama principal predeterminada

Pegaremos en la consola el codigo git config --global init.defaultBranch main

4. Elegiremos el editor de texto que mas nos guste
En este caso usaremos VSC y nuevamente en la consola usaremos el comando:
git config --global core.editor "code --wait"

Podemos hacer una prueba con el comando git config --global --edit
y nos saldrá algo parecido a esto en VSC:

<img width="477" height="219" alt="{D2F4117B-95FC-4EE7-A07B-AE48792C041D}" src="https://github.com/user-attachments/assets/bd4341ae-2455-4f77-94f0-b7169fbd67fe" />



6. Verificar la configuración final
Revisaremos que todos los parámetros se hayan guardado correctamente en el archivo global:

git config --list 

Nos deberia salir una ventana asi

<img width="289" height="291" alt="{D3B1E39C-1DF2-4340-99B5-2363D9B684CF}" src="https://github.com/user-attachments/assets/4982178d-ed31-4f08-a00b-f2f1e7083ef5" />

Y esa es la guia rapida de como configurar GIT :D

--------------------

████████████████████████████████████████
████████████▓▒░══════════▓█▒═███████████
███████████▒══════════════██══██████████
███████████════════░░══▓█═██═══█████████
██████████▓════░═▒█▓▓██▓══▓█═══▓████████
██████████████████████████████▓█████████
██████████▒░▒░══▓█▒▒▓▒█═══▒█▒▒▒▓████████
██████████═════▒███▓▓▓░═══░█▒═══████████
██████████════════════════░█▒══░████████
████████████████████████████████████████
██████▒▓█████████████████████████▓▓█████
██████▒▓██▒▒▒▒▓█▒═══════██░░▒▒▒██▓██████
█████████▒███▓▒═▓█░═══░█▓═▒▓█████▒██████
██████═██▓████░══██═══██══▒░█████▓▓█████
██████══█▒▓▓▓▒░═██▓░═░██═══░▒▒▒▓█═░█████
█████▓══░══════░█░═════██══════▓█══█████
██████═════════█▓═══░═══█▓═════░░══█████
██████═░══════▓█═══░════▒█▓════════█████
██████════░══░▓══════════░██══░═░░═█████
██████════░══▒═══░═░══░════█▓══░═░═█████
██████▒════════════▓══▓═════░░══░══█████
██████▓════════░════════════════░═░█████
███████═══════░═══════════════════▓█████
████████═════════▓▓▓▓▓▓▓▓▓▒════░══██████
█████████═══════░▓▓▒▒▒▒▓▓▓▓══════███████
██████████═════════▒█▓▓█░══░░══░██▒█████
█▒█▓═██████▓═════════════░░═══▒██▒▒████▒
▓═██═▒███░▒██▓═══════════░═══████═████▒═
═══▒═══██▒═████▓═══════════▓█████═███▓══
══════███▓═▓█▒████▒═════▒▓███████═███▓══
════▒█▓═▓▓═░█══▓█████████████████═███▓══
═══▓██══█▓══██═══▒▓█████████████▓═████══
══█████▒█═══▓█═══════▒▓██████████░████▒═
▒███████▓════██══════════▒▒▓███████████░
███████▓═════▓█═══════════════█▒═▒██████
Diego Garcia



