# Git 
## Descargar git
link para realizar la descarga:
[Git](https://git-scm.com/downloads)

nota: si git es usado en windows usar la terminar que viene con git la cual es GitBASH

##Primeros pasos
git config -h: entrega todas las configuraciones posibles.

git --version : muestra la versión de git <br>

git config --global user.name "nombre": configuración global de git con nombre. <br>

git config --global user.email email: configuración global de git email.<br>

git config --global core.editor "code --wait": configuración global de editor de texto.<br>

git config --global core.autocrlf input: si es en sistema mac. <br>

git config --global core.autocrlf true: si es en sistema windows. <br>

##Comandos bash
Navegar en la estructura de archivos. <br>

ls: lista de las carpetas en cmd. <br>
pwd: ruta en donde se encuentra. <br>
cd: cambiar de direcctorio. <br>
cd ..: Salir del direccitorio. <br>
mkdir: crear un nuevo direcctorio. <br>
ls -a: <br>
rm: eliminacion de archivo. <br>
mv: cambiar nombre de archivo. <br>

##Comandos git
init: inicio de repositorio en el direcctorio seleccionado. <br>
status: ver estatus del repositorio. <br>
status -s: ver estatus del repositorio. <br>
add: agregar archivo a repositorio (stage). <br>
commit -m "texto": comprometer atchivo con un texto que de claridad de los cambios realizados. <br>
restore: recuperar archivo eliminado. <br>
diff: muestra las direferencias. <br>
diff --staged: muestra las direferencias (stage). <br>
log: historial de cambios. <br>
log --oneline: historial de cambios en una linea. <br>

### Ignorara archivos en git
se debe de crear un archivo .gitignore donde se deben agregar los nombres del los archivos y direcctorios.







