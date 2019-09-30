## Cheatsheet Git
***git Init*** 
 : *crea una carpeta .git el cual continene la referencia a todo lo que hacemos en el repositorio.*

***git add*** 
 : *Añade los archivos en el scenario para git hub*
 : **"\*.txt"** agrega todos los archivos txt de todo el proyecto.
 : **\*.txt** agrega todos los txt en el directorio actual.
 : **--all** agrega agrega todos los archivos.
 : **add pdfs/\* .pdf** Se agregan todos 

***git commit*** 
 : *toma el snapshot del archivo -- crea un resgistro historico del archivo seleccionado*
 : **- m**: es necesario y agrega un comentario a lo sufrido en el archivo.


***git status*** 
 : *muestra el archivo seleccionado, añadido o modificado*
 : **-s** muestra el estatus en una sola linea 

***git commit -- .*** 
 : *Restaura los archivos a el status de su ultimo commit*

***git log*** 
 : *Muestra los commit realizados hasta el momento (Linea de tiempo)*
 : **-oneline** muestra el log en una linea 
 : **git log  --oneline --decorate --all --graph** lo muestra mas bonito.

***git reset nombre_del_archivo*** 
 : *Quita el archivo del git add *

***git config --global alias.lg "log --oneline --decorate --all --graph*** 
 : *crea un shortcourt de la linea largar a la linea corta (crea un alias)*

***git config --global -e*** 
 : *Muestra las configuraciones del archivo.*

***git push*** 
 : *Se utiliza para subir las modificaciones a github*