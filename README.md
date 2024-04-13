# 1. Se cambio el nombre de la carpeta por defecto a assets

# 2. Se creo el README.md con el siguiente comando: (fuera de assets)
touch README.md

# 2. Se cambia de directorio con:
cd ./assets

# Se creo la carpeta css e images "estando en assets" con el siguiente comando:
mkdir css images

# 4 Se cambio style.css a su carpeta correspondiente

# Se inicia el repositorio:
git init

# Se agrega los archivos al stage area
git add .

# Se agrega el primer commit del proyecto
git commit -m "este es mi primer comentario"

# Se creo una rama llamada development
git branch development

# Se situo en la rama development
git checkout development

# Se modifico la imagen y el link para que se dirija a mi Github
# Se Agrego los cambios al “stage”, y se realizo un último commit con un mensaje “errores corregidos
git add .
git commit -m "errores corregidos"

## Crear repositorio en Github
git remote add origin https://github.com/Celeste941/Desaf-o-evaluado---Branching.git

## Realizar el push de el main y la rama
git push --set-upstream origin development
git push --set-upstream origin main
