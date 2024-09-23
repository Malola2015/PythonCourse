GitHub Copilot
Para guardar tu código en un repositorio privado en GitHub, sigue estos pasos:

Paso 1: Crear un Repositorio Privado en GitHub
Ve a GitHub y accede a tu cuenta.
Haz clic en el botón + en la esquina superior derecha y selecciona New repository.
Dale un nombre a tu repositorio y selecciona Private.
Haz clic en Create repository.


Paso 2: Configurar Git en tu Máquina Local
Abre la terminal en tu Mac.
Navega al directorio donde tienes tu archivo Practica1-2.ipynb.


Paso 3: Inicializar el Repositorio Local y Conectar con GitHub
Inicializa un nuevo repositorio Git en tu directorio local.
init
Agrega tu archivo al repositorio.
Realiza un commit con un mensaje descriptivo.
Conecta tu repositorio local con el repositorio remoto en GitHub. Reemplaza URL_DEL_REPOSITORIO con la URL de tu repositorio en GitHub.
git remote add origin https://github.com/tu-usuario/tu-repositorio.git


Paso 4: Subir el Código al Repositorio Remoto
Sube tu código al repositorio remoto en GitHub.

Resumen de Comandos
Resumen de Comandos
Inicializar el Repositorio Local: 

>git init

Agregar Archivos al Repositorio:

>git add Practica1-2.ipynb

Realizar un Commit:
> git commit -m "Añadir archivo Practica1-2.ipynb"

Conectar el Repositorio Local con el Remoto:

> git remote add origin https://github.com/tu-usuario/tu-repositorio.git

Subir el Código al Repositorio Remoto:
git push -u origin main


Nota
Asegúrate de reemplazar https://github.com/tu-usuario/tu-repositorio.git con la URL de tu repositorio en GitHub.
Si es la primera vez que usas Git, es posible que necesites configurar tu nombre de usuario y correo electrónico:
Siguiendo estos pasos, tu código estará guardado en un repositorio privado en GitHub.

git config --global user.name "Tu Nombre"
git config --global user.email "tu-email@example.com"


Paso 5: Agregar Colaboradores al Repositorio
Los alumnos deben ir a la página de su repositorio en GitHub.
Hacer clic en la pestaña Settings.
En el menú de la izquierda, seleccionar Collaborators.
En la sección Collaborators, deben buscar tu nombre de usuario de GitHub (Malola2015) y hacer clic en Add collaborator.
GitHub enviará una invitación que deberás aceptar para tener acceso al repositorio.


Paso 6: Compartir el Enlace del Repositorio
Los alumnos deben copiar la URL de su repositorio.
Pueden enviarte la URL por correo electrónico.