git init


git add Nombre del archivo
git commit -m "Descripción"
git -A
git --a
git log
git log --oneline
git diff
git status
git stash 
git stash list
git stash apply
git stash clear
git checkout -b Nombre de la rama **crea la rama y te mueves a ella automaticamente 
git branch -D nombre de la rama a borrar

GitFlow
Para crear sub-ramas dentro de las ramas usamos los prefijos: 
features/nombre
fix - hot fix/nombre
improvement/nombre

Para unir cambios definitivos a la rama main, es ideal primero pasarlos a la subrama correspondiente con el comando: 

git merge nombre de la rama a unir dentro de la rama donde quiero llevar mis cambios

Una vez incorporados los cambios se puede borrar esa rama nieta
