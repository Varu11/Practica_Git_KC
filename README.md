# Practica_Git_KC

# Practica_Git_KC

- ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
git reset --har HEAD~1
Lo uso porque quiero eliminar el último cambio que he realizado, y bajar el HEAD a la acción anterior.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog
porque me permite recuperar el paso anterior a lo eliminado.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
merge: main - not something we can merge
Verifico con git Branch, y veo que tengo 2 ramas: Master y Branch.
Main no existe


- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Already up to date.
No me sale conflicto

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No salió ningún conflicto:
$ git merge htmlify
Updating 56191bf..d32aaa7
Fast-forward
 git-nuestro.md | 10 ++++++++++
 1 file changed, 10 insertions(+)
 create mode 100644 git-nuestro.md


- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --all

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
No,porque son ramas diferentes.

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset --soft HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git reset --hard

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -d title

- ¿Qué comando o comandos utilizaste en el paso 30?
git merge --no-ff title -m "Rehacer el merge eliminado"

- ¿Qué comando o comandos usaste en el paso 32?
git checkout $(git rev-list --max-parents=0 HEAD)

- ¿Qué comando o comandos usaste en el punto 33?
git checkout dd9bbaa

