
Asegurate que tienes instalado la versión más reciente de Git. Y además tienes configurado tu nombre de usuario y e-mail para Git

https://docs.github.com/es/get-started/getting-started-with-git/set-up-git#setting-up-git

A continuación sigue los pasos siguientes:

Paso 1: Crear un Repositorio Privado en GitHub
- Ve a GitHub y accede a tu cuenta.
- Haz clic en el botón + en la esquina superior derecha y selecciona New repository.
- Dale un nombre a tu repositorio y selecciona Private.
- Haz clic en Create repository.


Paso 2: Configurar Git en tu Máquina Local
- Abre la terminal en tu PC.
- Navega al directorio donde tienes tu archivo (Por ej. Practica1-2.ipynb).


Paso 3: Inicializar el Repositorio Local y Conectar con GitHub
- Inicializa un nuevo repositorio Git en tu directorio local.
- Clona tu repositorio creado
- Agrega tu archivo al repositorio.
- Realiza un commit con un mensaje descriptivo.
- Subir el código al repositorio mediante un push.

Inicializar el Repositorio Local (si clonas el repositorio no tienes que hacerlo): 

> git init

Clonar el repositorio (ojo, poner vuestra dirección del repositorio)

> git clone https://github.com/Malola2015/PracsConGit.git

Agregar una carpeta con varios archivos  o un único archivo al Repositorio. A continuación ambas opciones.

Una carpeta con achivos sería:

> git add P1/.

Y un único archivo:

> git add Practica1-2.ipynb

Realizar un commit:

> git commit -m "Añadir archivo Practica1-2.ipynb"

Subir el código al repositorio remoto (mira si es main o master la rama correspondiente):

> git push -u origin main

Paso 5: Agregar Colaboradores al Repositorio
Los alumnos deben ir a la página de su repositorio en GitHub.
Hacer clic en la pestaña Settings.
En el menú de la izquierda, seleccionar Collaborators.
En la sección Collaborators, deben buscar el nombre de usuario de GitHub (Malola2015) y hacer clic en Add collaborator.
GitHub enviará una invitación

Y ya está todo listo para usarlo. Como puede que tu compañero (o tu mismo) añada cosas sin decírtelo, no te olvides SIEMPRE de hacer:

> git status
> git pull

Esas opciones te permitirán ver si hay cambios y estar sincronizado. Pero ojo, que git pull te sobreescribirá el fichero local.

También puede ocurrir que necesites borrar ficheros o carpetas, para ello usa:

> git rm Practica1-2.ipynb

Y después no te olvides de hacer commit y push.







