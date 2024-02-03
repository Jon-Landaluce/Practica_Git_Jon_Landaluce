● ¿Qué comando utilizaste en el paso 11? ¿Por qué?

Utilice el comando: git reset --hard HEAD~1
Porque: Este comando permite deshacer el commit perdiendo los cambios que tenemos en el working copy

● ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Utilice el comando: git reflog y git reset a6cfacd
Porque: git reflog nos lista todos los commits que se han hecho en orden (aunque se hayan borrado) y con git reset volvemos a ese commit usando el ID que le corresponde

● El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

Utilice el comando: git merge main
Porque: No causa conflicto porque se trata de un merge fast-forward, no estamos creando un nuevo commit sino que la rama styled absorbe el trabajo de main

● El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Utilice el comando: git merge –no-ff htmlify
Porque: En este caso si hacemos un merge normal si causa conflicto por lo que tenemos que aplicar un non fast-forward para evitarlo y crear un nuevo commit en el que tendremos que revisar el documento resultante ya que las versiones de estas ramas son diferentes

● El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

Utilice el comando: git merge styled
Porque: No genera conflicto porque como hemos explicado en el paso 13 se trata de un merge fast-forward

● ¿Qué comando o comandos utilizaste en el paso 25?

Utilice el comando: git log –graph

● El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Utilice el comando: git merge –no-ff title
Porque: Si, podria ser fast forward porque en la rama title solo hemos añadido el título y los estamos absorbiendo no hemos generado cambios en el resto del “código”

● ¿Qué comando o comandos utilizaste en el paso 27?

Utilice el comando: git reset HEAD~1

● ¿Qué comando o comandos utilizaste en el paso 28?

Utilice el comando: : git restore git-nuestro.md

● ¿Qué comando o comandos utilizaste en el paso 29?

Utilice el comando: git branch -D title

● ¿Qué comando o comandos utilizaste en el paso 30?

Utilice el comando: git reflog + git reset ef851fe

● ¿Qué comando o comandos usaste en el paso 32?

Utilice el comando: git reflog + git reset –hard c710890

● ¿Qué comando o comandos usaste en el punto 33?

Utilice el comando: git reset --hard d9b3c47

