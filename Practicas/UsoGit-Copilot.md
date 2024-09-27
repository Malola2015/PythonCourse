
# Instrucciones para el uso de Git

Asegurate que tienes instalado la versión más reciente de Git. Y además tienes configurado tu nombre de usuario y e-mail para Git. No sigues a la siguiente sección sin haber comprobado todo aqui:

https://docs.github.com/es/get-started/getting-started-with-git/set-up-git#setting-up-git

## Pasos

**Paso 1**: Crear un Repositorio Privado en GitHub
- Ve a GitHub y accede a tu cuenta.
- Haz clic en el botón + en la esquina superior derecha y selecciona New repository.
- Dale un nombre a tu repositorio y selecciona Private.
- Haz clic en Create repository.


**Paso 2**: Configurar Git en tu Máquina Local
- Abre la terminal en tu PC.
- Navega al directorio donde tienes tu archivo (Por ej. Practica1-2.ipynb).


**Paso 3**: Inicializar el Repositorio Local y Conectar con GitHub

1. Inicializa un nuevo repositorio Git en tu directorio local.
2. Clona tu repositorio creado.
3. Agrega tu archivo(s) al repositorio.
4. Realiza un commit con un mensaje descriptivo.
5. Subir el código al repositorio mediante un push.

Aqui se escriben los comandos:

- Inicializar el Repositorio Local (si clonas el repositorio no tienes que hacerlo): 

  > git init

- Clonar el repositorio (**OJO**, poned vuestra dirección del repositorio creado, este es el mío)

  > git clone https://github.com/Malola2015/PracsConGit.git

- Agregar una carpeta con varios archivos  o un único archivo al Repositorio. A continuación ambas opciones.

  Una carpeta con achivos sería (cambia P1 a lo que tú consideres):

  > git add P1/.

  Y un único archivo (cambia Practica1-2.ipynb a lo que tú consideres):

  > git add Practica1-2.ipynb

- Realizar un commit:

  > git commit -m "Añadir archivo Practica1-2.ipynb"

- Subir el código al repositorio remoto (mira si es main o master la rama correspondiente):

  > git push -u origin main

**Paso 4**: Agregar Colaboradores al Repositorio
- Debes ir a la página de tu repositorio en GitHub y hacer clic en la pestaña Settings.
- En el menú de la izquierda, seleccionar Collaborators.
- En la sección Collaborators, deben buscar el nombre de usuario de GitHub de tu compañero si no lo haces solo y a mi, si quieres que lo pueda ver (Malola2015) y hacer clic en Add collaborator.
- GitHub enviará una invitación.

## Otros comandos

Y ya está todo listo para usarlo. Como puede que tu compañero (o a ti mismo se te olvide) añada o modifique cosas sin decírtelo, no te olvides SIEMPRE de hacer:

> git status

> git pull

Esas opciones te permitirán ver si hay cambios y estar sincronizado. Pero ojo, que git pull te sobreescribirá el fichero local.

También puede ocurrir que necesites borrar ficheros o carpetas, para ello usa:

> git rm Practica1-2.ipynb

Y después no te olvides de hacer commit y push.







