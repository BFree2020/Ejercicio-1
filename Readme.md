Comandos de la terminal
Pwd —En donde esta ubicado 
cd XXX—Para ubicarse en una carpeta
cd ----- vuelve a la parte principal
mkdir XXX--- crear nueva carpeta
ls—muestra archivos y carpetas
ls –al ----- trae todos los archivos ocultos y todos
clear---- limpiar consola--- ctrl L
ls-l …… Muestra todos los archivos, pero no ocultos
cd .. ----- para volver a la carpeta anterior
touch  XXX.txt---- crea archivos vacios
cd . ------- carpeta actual
cat XXX.txt  ------- muestra el contenido de un archivo
history ---- muestra toda la historia de comandos----- ¡NUM ----- con el signo de admiración puede repetir el comando de history
rm XXX.txt------ borrar archivos
COMANDO --help ---- muestra explicaciones del comando ejemplo; rm --help
rm –rf ------ borra carpeta
rm –rf .git deja que una carpeta ya no sea repositorio

GIT
git init—Iniciar carpeta
git status ---- muestra el estado de tus carpetas o proyectos
git add------ traquea archivos o se les da seguimiento 
git rm –cached Prueba.txt ----- elimina el traqueado osea el add
git commit --------envía los cambios al repositorio
git commit –m “Xxxxxx  xx”  --------envía los cambios al repositorio con un comentario del archivo 

configurar git 
git config ------- configuración de GIt
git config --list -------- se ve la configuración por defecto de tu git
git config --list –show-origin ----- donde esta las configuración guardadas 
git config --global user.name “xxxx xxx” --------- configuracion del Usuario de Git
git config --global user.email “xxxx@x” --------- configuracion del correo de Git
code xxx.txt ------- Me abre Visual estudio code para modificar el archivo plano
git log xx.txt ------- muestra la historia de un archivo 

git add . ------traquea todos los archivos de la carpeta actual

GIT ADD----- GIT COMMIT----- primero se debe estar traqueado el archivo y asi se hace el comit 

