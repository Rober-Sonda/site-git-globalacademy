Propital

Bienvenidos al repositorio de la comisión 21
Instructivo para descargar el repositorio
Antes de comenzar asegurate tener instalado GIT en la computadora. Para revisar escribe en el buscador de Windows o del sistema operativo que tengas el programa GIT BASH. Si lo tienes está instalado correctamente.

Escribir en el buscador de windows el siguiente comando y luego dar Enter.
  cmd
Hacer click en el boton verde que dice "Code" del repositorio y copiar el enlace que allí figura.

Ir a la terminal que abrieron con el cmd y escribir el siguiente comando. Nota: Revisen bien en que carpeta van a ejecutar el comando para luego poder encontrar el archivo que se genera.

  git clone pegar_enlace_extraido_del_boton_Code
Una vez que ejecutan ese comando se debería crear una carpeta en la ubicación que figura en la terminal. Una vez que la carpeta se genera ya pueden arrastrarla al ícono de Visual Studio Code.
Comandos para recorrer en terminal
Moverte a un archivo/carpeta (directorio) interno de la carpeta actual (directorio actual).
  cd nombre_archivo
Regresar al directorio anterior.
  cd ..
Revisar todos los archivos del directorio actual
  dir
Crear una nueva carpeta
  mkdir nombre_carpeta
Limpiar terminal
  cls
Cerrar terminal
  exit
COMANDOS GIT
git init: inicializa git en un proyecto.
git remote add origin [enlace repo]: Conecta un proyecto con un repositorio.
git remote set-url origin [enlace nuevo repo]: Desvincula el proyecto de un repo, y lo vinculo al nuevo.
Preparamos nuestros cambios para ser enviados al repositrio.
git add [nombre achivo]: Registra un archivo para ser enviado al repo.
git add . : Registra todos los archivos.
Preparamos el backup
git commit -m [nombre commit]: Prepara una version segura a la cual podemos volver (un backup).
Enviamos las actualizaciones al repo
git push: Envia las actualizaciones a una rama generica
git push origin [nombre rama]: Envia las actualizacions a una rama origen (default)
Para revisar informacion
git status: Revisamos que esta registrado y que no. (rojo: no registrado. Verde: Registrado)
git log: revisamos la lista de commits realizados. (El que tiene el HEAD es el ultimo y apunta a la rama en la cual se realizó.)
Descargar de repo a PC
git clone [enlace repo]: Clona el proyecto del repo a la PC
Cambiar de rama
git checkout [nombre rama]
Actualizar el proyecto de repo a PC
git pull: Arrastra cambios que existen en el repo pero no en la PC, del repo a la PC.
Establecer tus datos de username e email
git config --global user.email "aldanacapoble@gmail.com"
git config --global user.name "Aldana Capoble"
Dar colaborador
Entran al repo -> Settings -> Collaborators -> Add people -> Buscan a "lirico" (Matias Dominguez) avatar de atomo.

=======================================
## Segundara tarea HTML

En esta segunda tarea trabajaremos sobre el archivo de la tarea anterior. 

## Consigna:

- A partir del menú de navegación previamente creado para la primera tarea, crear una paginación de modo que cada enlace del menú lleve a una nueva página del sitio. Ejemplo: Contacto lleve a contacto.html.
- Para poner en práctica los conceptos de tablas que vimos durante la clase, armar una pequeña galeria de fotos en alguna de las páginas usando las tablas de html.
- Crear al menos 5 secciones temáticas en la hoja principal que contengan elementos iframe. Pueden ser videos de youtube, listas de spotify o cualquier otra cosa que investiguen que pueda incorporarse via iframe.

## Nota:
- Para clonar el repo **git clone "enlace al repo"**
- Para bajar descargar nuevos cambios una vez clonado **git pull** estando parado en la rama de la cual se quieren bajar cambios.
- Para cambiarte de rama **git checkout "nombre de rama"**
=======================================
## Tercera tarea HTML

En esta tercera tarea trabajaremos sobre el archivo de la tarea anterior. 

## Consigna:

- Crear una página donde creen un formulario. Este formulario puede tener la impronta que gusten. Puede ser un formulario de contacto, un formulario de registro... incluso un formulario para crear un personaje de un 
- Agregar al sitio al menos un video y un audio consumidos desde una plataforma en la nube. Recomiendo DropBox para este punto.

## Investigación:
- Aplicar el concepto de lazy loading a los elementos que correspondan.

## Nota:
- Para clonar el repo **git clone "enlace al repo"**
- Para bajar descargar nuevos cambios una vez clonado **git pull** estando parado en la rama de la cual se quieren bajar cambios.
- Para cambiarte de rama **git checkout "nombre de rama"**