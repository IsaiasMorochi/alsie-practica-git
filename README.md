# alsie-practica-git

1. Primer commit
2. Segundo commit
3. Tercer commit bugFix
Commit master
5. Quinto commit
6. Moverse entre commits: git checkout HEAD^
7. Ruta relativas: git branch -f main HEAD3
8. Rivirtiendo cambios: git reset deshace los cambios moviendo la referencia de una rama hacia atrás en el tiempo a un commit anterior. 
  En este sentido puedes imaginarlo como "reescribir la historia". 
  git reset va a mover la rama hacia atrás, como si el commit nunca se hubiera hecho.
9. git cherry-pick <Commit1> <Commit2> <...>
  Es una manera bastante directa de decir que quieres copiar una serie de commits sobre tu ubicación actual (HEAD). Personalmente amo cherry-pick porque hay muy poca magia involucrada y es bastante simple de entender.