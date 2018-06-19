¿Qué comando utilizaste en el paso 11? ¿Por qué? 
Utilizé el comando:
$ git reset --hard HEAD~1
Porque mueve el HEAD a la posición anterior al commit y resetea el working copy al mismo

Rehacer el último commit (el que acabamos de deshacer) 
Localizamos el id del correspondiente commit
$ git reflog
Hacemos un reset al mismo
$ git reset --hard 3616ea2
Por que mueve el HEAD a la posición del commit localizado y resetea el working copy al mismo

El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?
No causo conflicto porque la rama styled ya contenia a la rama master, con lo cual al hacer merge git devolvió "Already up to date"

El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?
Si causo conflicto porque en ambas ramas el mismo fichero ha sido modificado en las mismas lineas

El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?
No causo ningún conflicto porque el puntero de la rama master estaba en el mismo lugar que el puntero de la rama styled

¿Qué comando o comandos utilizaste en el paso 25?
$ git log --graph --decorate --pretty=oneline

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Si podría ser un fast forward porque hemos mantenido el texto, solo hemos añadido un titulo en la parte de arriba

¿Qué comando o comandos utilizaste en el paso 27? 
$ git reset HEAD~1

¿Qué comando o comandos utilizaste en el paso 28?
$ git reflog
$ git reset --hard 3b34cbe

¿Qué comando o comandos utilizaste en el paso 29?
$ git branch -D title

¿Qué comando o comandos utilizaste en el paso 30?
$ git reflog
$ git reset --hard 2495ec1

¿Qué comando o comandos usaste en el paso 32?
$ git reflog
$ git reset --hard 4b455f9

¿Qué comando o comandos usaste en el punto 33?
$ git reflog
$ git reset --hard 2495ec1