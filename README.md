#Tarea 01

#git reset [modo]  [commit]
Esta forma se restablece la cabeza rama actual a (commit) y posiblemente actualiza el indice (que se quede en el arbol de la (cometer)) y el arbol de trabajo en funcion de (modo). Si se omite (modo), por defecto es "--mixed".El (modo) debe ser uno de los siguientes:

##--soft
No toca el archivo de indice o el arbol de trabajo en absoluto (pero restablece la cabeza a (commit), al igual que todos los modos de hacer). Esto deja a todos sus archivos modificados "Los cambios que se cometan", como git status lo pondra.

##--mixed
Restablece el indice, pero no el arbol de trabajo (es decir, los archivos modificados se conservan pero no marcados para commit) e informa de lo que no se ha actualizado. Esta es la accion por defecto.

