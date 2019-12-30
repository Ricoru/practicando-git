# Empenzando Git 2020 con EdTeam

# Tips a tener en cuenta:

- git commit -am (aplicar solo para archivos modificables, me permitira agregar y comitear en una sola linea todos los archivos)
- git checkout (file) antes de hacer git add / commit, se restaura los cambios a su versión original que estuvo antes de módificar
- git checkout -f (se resetean todos mis cambios realizados en todos los archivos que aya modificado) pero recuerda esto funciona antes de hacer git add / commit
- git para Linux o mac puedes usar el "git restore --staged (file)" para quitar un archivo del area de preparación o un archivo que ha sido aplicado "git add", para windows hay que usar el siguiente comando "git reset HEAD (file)"
- git diff me permite poder ver los cambios realizados en los archivos con los que están guardados en el repositorio
- git log --raw me muestra que archivos he modificado en ese commit
- git log --oneline me muerstra todos los commit con su hash y su mensaje.

## Rama development
Ahora tenemos 2 ramas en el proyecto

- Puedo usar git checkout o git switch para realizar cambios de ramas por ejemplo: master -> dev o dev -> master
- git branch -D (nombre rama) con esto eliminamos la ramas locales