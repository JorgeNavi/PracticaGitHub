# PracticaGitHub
. ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    "git reset --hard HEAD~1" porque pide que se pierdan los datos realizados en el working copy

. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    "git reflog" para que me muestre la información de los commits realizados y "git reset --hard identificador reducido del commit" para volver al mismo

. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    no, porque al no mandar al repositorio el archvo modificado a pesar de recuperar el commit, no hay conflicto entre las ramas

. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    no, porque la informacion del archvio es la misma. simplemente cambia la grafía

. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    no, por lo mismo que la anterior

. ¿Qué comando o comandos utilizaste en el paso 25?
    "git --log --decorate --pretty"

. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    si, porque el commit de title simplemente añade un titulo al archvo .md, por tanto HEAD solo tiene que moverse a ese commit en la rama main

. ¿Qué comando o comandos utilizaste en el paso 27?
    "git reset HEAD~1"

. ¿Qué comando o comandos utilizaste en el paso 28?
    "git reflog" y despues "git reset --hard (identificador reucido del commit)" para volver al commit en el que estaba guardado git-nuestro.md sin el titulo

. ¿Qué comando o comandos utilizaste en el paso 29?
    "git branch -D (nombre de la rama, en este caso "title")

. ¿Qué comando o comandos utilizaste en el paso 30?
    "git reset --hard (identificador del commit donde estaba title)" para situar HEAD allí y comprobé con "cat git-nuestro.md" que incluía el título.

. ¿Qué comando o comandos usaste en el paso 32?
    "git reflog" para que me muestre los commits y "git reset (indentificador reducido del commit inicial)" para volver al primer commit. Podría hacerse así para volver sin mas o con --hard para modificar el working copy pero como no se especifica me he limitado a volver sin más

. ¿Qué comando o comandos usaste en el punto 33?
    como ya tenía a la vista el git reflog no lo volví a poner. simplemente busqué la etiqueta del commit en el que puse el comentario que añadía el título y escribí "git reset (identificador reducido del commit donde añado título)"
