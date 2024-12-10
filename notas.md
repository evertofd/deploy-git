1. git init
2. Emparejar el proyecto local con el remoto
3. descomentar el dist desde el gitignore
4. Agregar la ruta en el vue.config.js
4. npm run build
5. git add .
6. git commit -m "mensaje"
7. git push
8. git checkout -b gh-pages => este comnado crea y se mueve automaticamente a la rama nueva
9. git subtree push --prefix dist origin gh-pages

################################# Si realizo cambios ################################################

1. npm run build
2. git add .
3. git commit -m "mensaje"
4. git push
5. git checkout gh-pages 
6. git pull origin "la rama donde hicieron los cambios"
7. git subtree push --prefix dist origin gh-pages