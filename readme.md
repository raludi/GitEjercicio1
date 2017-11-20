
# FORMULARIO

- Qué comando utilizaste en el paso 11? ¿Por qué?
	1. Realizo un `git log` para ver los commit.
 -	 Posteriormente un `git reset "identificador"` que hicimos en un primer momento para mover la rama
 - `git checkout — git-nuestro.md` para eliminar los cambios del working copy
		- Otra forma de evitar este último paso hubiese sido con `git reset --hard master` 
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	1. `git reflog` para ver en que momento se hizo el commit
	2. `git reset "identificador"` para movernos al commit en el que modificamos el archivo
	3. `git checkout — git-nuestro.md` para descartar los cambios del working copy
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
 - No causa ningún conflicto ya que contiene a master
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
 - Si, causa un confliecto en nuestro git-nuestro.md ya que se han modificado las mismas líneas de código
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
 - No, se realiza un merge fast forward y se actualizan los contenido de master a styled
- ¿Qué comando o comandos utilizaste en el paso 25?
 - `git log --graph` o al tenerlo configurado como alias usé directamente `git graph`
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
 - Si ya que ningún commit se queda descolgado, master unicamente se desplazaría a title
- ¿Qué comando o comandos utilizaste en el paso 27?
 1. `git reflog`para ver los registros
 2. `git reset "identificador"` 
- ¿Qué comando o comandos utilizaste en el paso 28? 
- `git checkout — git-nuestro.md` 
- ¿Qué comando o comandos utilizaste en el paso 29? 
- `git branch -D title`
- ¿Qué comando o comandos utilizaste en el paso 30? 
 1. Buscamos con `git reflog`el commit en el que hicimos el cambio
 2. Con `git reset --hard "identificador"` recuperamos el merge
- ¿Qué comando o comandos usaste en el paso 32?
 1. Buscamos con `git reflog`el primero commit que hicimos en la rama
 2. Con `git reset --hard "identificador"` nos movemos a él
- ¿Qué comando o comandos usaste en el punto 33?
-  1. Buscamos con `git reflog` el commit en el que fue el merge de title y master
 2. Con `git reset --hard "identificador"` nos movemos a él
