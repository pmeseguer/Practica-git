# PracticaGit - Respuestas
Pau Meseguer Fliquete
--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque te lleva al commit precedente del actual, perdiendo todos los cambios.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` 

`git checkout d1468ad` 

`git branch -D styled` 

`git branch styled` 

El primero para ver el historial de acciones, y acceder al codigo de la penultima acción, el segundo para volver al paso anterior (introduciendo el código), el tercero para borrar la rama styled y el ultimo para rehacerla en la posición inicial.

--

**3. El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?**

No, a pesar de que el mismo archivo tenga variaciones, la versión "master" es antecedente a la versión "styler", por consiguiente se mantendría la versión más moderna, en este caso la "styler" (con negrita).

--

**4. El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?**aa

Si, porque poseian el mismo archivo en distintas versiones y ninguno de los dos se encuentra en la base del otro.

--

**5. El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?**

No, porque "master" se encuentra en la base de "styled" y el merge lo que hace es dejar su historial igual al otro (mismos commits).

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph` 

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si, porque se encontraba en la base de "title".

--

**8.¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reset --hard HEAD~1`

En mi caso ese para deshacer el commit que evitaba que fuera un no fast-forward

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog`

`git reset --hard 58d9a93`

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git log`

`git checkout 85253c96...`

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog`

`git reset --hard 58d9a93`
