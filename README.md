# taller_git-github

COMANDOS GIT
Ramas
git branch: Ver ramas existentes.
git branch nombre_de_rama: Crear una nueva rama desde la rama actual.
git branch -d nombre_de_rama: Borrar una rama.
Cambio de ramas
git checkout nombre_de_rama: Cambiar/moverse a otra rama.
git checkout -b nombre_de_rama: Crear una nueva rama y moverse a ella.
Historial y estado
git log: Ver el historial de commits.
git status: Ver los cambios y el estado del repositorio local.
Commits
git commit -m "mensaje": Hacer un commit con un mensaje descriptivo.
Revertir cambios
git reset --hard HEAD~1: Restablece el último commit localmente.
git push --force origin nombre_de_rama: Forzar el push al repositorio remoto.
git revert HEAD: Deshacer el último commit manteniendo el historial intacto.
Subir y sincronizar
git push: Subir cambios al repositorio remoto.
git push origin nombre_de_rama: Subir una rama local al repositorio remoto.
git fetch rama_remota: Obtener los últimos metadatos del repositorio remoto (sin traer los archivos).
git pull: Traer los cambios del repositorio remoto al local.
Unir ramas
git merge rama_secundaria: Combinar los cambios de otra rama en la rama actual.
