## Crear repositorio (una sola vez por proyecto)
git init

## Anadir archivos al repo
git add nombre-archivo

## Para poder crear un commit
git commit -m 'descripcion del commit'

## Tener una ayuda sobre el status de nuestro repo
git status

## Ver historial de commits
git log

## Renombrar la rama principal a main
git branch -M main

## Anadir un origen remoto
git remote add origin 

## Revisar origen remoto
git remote -v

## Cambiar el origen remoto
git remote set-url origin

## Subir el codigo a github
git push -u origin main