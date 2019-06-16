# Ejericio 1

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

En el paso 11 se usó el comando `git reset --hard HEAD~1` para volver al commit anterior.
 
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

En el paso 12 se uso `git reflog` para identificar el identificador del commit en la rama styled y luego se usó el comando
`git reset --hard 8972270` Volviendo al commit en la rama styled y recuperando los cambios.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causó ningún conflicto ya que el archivo git-nuesto.md venía de la rama master cuando se creo la rama styled.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Hubo conflicto al intentar realizar el merge de la rama htmlify en la rama styled  quedándonos con el contenido de la rama styled

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 



- ¿Qué comando o comandos utilizaste en el paso 25? 

El comando que se uso fue `git log --graph --decorate --pretty=oneline`

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Si podía ser un merge fast forward porque solo se hizo sobre un archivo 
que ya venía de master y el archivo en master no había sido modificado.

- ¿Qué comando o comandos utilizaste en el paso 27?

Se hizo un `git reset HEAD~N` N para el numero correspondiente.

- ¿Qué comando o comandos utilizaste en el paso 28?

Para descartar todos los cambios se uso `git checkout -- . `

- ¿Qué comando o comandos utilizaste en el paso 29?



- ¿Qué comando o comandos utilizaste en el paso 30?
- ¿Qué comando o comandos usaste en el paso 32?
- ¿Qué comando o comandos usaste en el punto 33?
