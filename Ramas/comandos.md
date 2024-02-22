# Comandos para listar las ramas

git branch (ver las ramas disponibles)

# Comando para crear una nueva rama

git branch nombre_rama (Regla: el nombre de la rama no puede tener espacios)

# Comando para eliminar una Rama

git branch -D nombre_rama

# Cambiar entre ramas

git switch nombre_rama
git checkout nombre_rama
git checkout -b nombre_rama (Crea rama y se cambia a esa)

# Desvincular un archivo de git que se le estaba dando seguimiento

git rm --cached nombre_archivo

# Crear una nueva versión con archivos que ya se estaban dando seguimiento (ahorra el add .)

git commit -am "nombre commit"

# Comando para unir ramas

git merge nombre_rama (en master y arrastras los cambios de Juli)
