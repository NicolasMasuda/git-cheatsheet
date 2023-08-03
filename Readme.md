# Git 

## Descargar Git
Para utilizar Git, primero debes descargarlo en tu sistema. Puedes descargar Git desde el siguiente enlace:
[Descargar Git](https://git-scm.com/downloads)

**Nota para usuarios de Windows:** Si estás utilizando Git en Windows, es recomendable usar la terminal que viene con Git, conocida como GitBASH.

## Primeros pasos
Antes de comenzar, hay algunas configuraciones globales que debes establecer en Git. Puedes usar los siguientes comandos:

- `git config -h`: Muestra todas las configuraciones posibles.
- `git --version`: Muestra la versión de Git instalada en tu sistema.
- `git config --global user.name "nombre"`: Configura globalmente el nombre del usuario.
- `git config --global user.email email`: Configura globalmente el correo electrónico del usuario.
- `git config --global core.editor "code --wait"`: Configura el editor de texto globalmente.
- `git config --global core.autocrlf input`: Establece la configuración para sistemas Mac.
- `git config --global core.autocrlf true`: Establece la configuración para sistemas Windows.

## Comandos bash
A continuación, algunos comandos útiles de la terminal para navegar en la estructura de archivos:

- `ls`: Lista las carpetas y archivos en el directorio actual.
- `pwd`: Muestra la ruta del directorio actual.
- `cd`: Cambia al directorio especificado.
- `cd ..`: Regresa un nivel en la estructura de directorios.
- `mkdir`: Crea un nuevo directorio.
- `ls -a`: Muestra todos los archivos, incluyendo los ocultos.
- `rm`: Elimina un archivo.
- `mv`: Cambia el nombre de un archivo.
- `cat`: Muestra el contenido de un archivo.

## Comandos Git
Estos son algunos comandos básicos de Git para gestionar tu repositorio:

- `git init`: Inicializa un nuevo repositorio en el directorio seleccionado.
- `git status`: Muestra el estado actual del repositorio.
- `git status -s`: Muestra el estado actual del repositorio de forma resumida.
- `git add`: Agrega archivos al área de preparación (stage).
- `git commit -m "texto"`: Realiza un commit con un mensaje claro que describa los cambios realizados.
- `git restore`: Restaura un archivo eliminado.
- `git diff`: Muestra las diferencias entre los cambios actuales y el último commit.
- `git diff --staged`: Muestra las diferencias de los cambios en el área de preparación (stage).
- `git log`: Muestra el historial de cambios realizados en el repositorio.
- `git log --oneline`: Muestra el historial de cambios en una sola línea.
- `git branch`: Muestra la rama actual en la que estás trabajando.
- `git checkout`: Cambia a una rama específica.
- `git checkout -b`: Crea y cambia a una nueva rama.
- `git merge`: Combina una rama con la rama actual.

## Ignorar archivos en Git
Para evitar que ciertos archivos y directorios se añadan al repositorio, debes crear un archivo `.gitignore` y agregar los nombres de los archivos y directorios que deseas ignorar.








