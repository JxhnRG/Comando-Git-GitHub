# Comandos Git en la gitbash
## Comando para configurar el nombre de usuario
```
git config --global user.name "username"
```
## Comando para configurar nuestro correo
```
git config --global user.email "email"
```
## Comando para inicializar un repositorio en una carpeta
```
git init
```
## Comando para renombrar nuestras ramas de git
```
git branch -m main
```
## Comando para ver el estado de los archivos en nuetro repositorio git
```
git status
```
## Comando para agregar nuestros archivos a nuestro repositorio
```
git add "name file"
```
## Comando para hacer commit y poder agregar nuestro archivos al repositorio
```
git commit -m "commit"
```
## Comando para ver nuestro historial de commits
```
git log
```
## Comando para regresar a una version anterior de nuestro archivo
```
git checkout
```
## Comando para regresar a una version anterior de nuestro archivo
```
git reset
```
## Comando para ver el historial de commits en forma de ramas
```
//Para ver en forma de rama
git log --graph

//Para ver en una sola linea
git log --graph --petty=oneline

//Para verlo de forma mas compacta
git log --graph --decorate --all --oneline
```
## Comandos para ver los cambios realizados
```
git diff
```
## Comando para desplazarse entre versiones
```
git checkout "host"
```
## Comando para moverse entre versiones

```
git reset --hard "host"
```
## Comando para ver el historial completo
```
git reflog
```
## Comando para mover la head junto al main
```
git checkout main
```
## Comando para agregar atajos

```
git config --global alias.name "action"
```
## Comando para defenir las versiones del archivo
```
git tag "name version"
```
## Comando para agregar todos los archivos al repositorio 
```
git add .
```
## Comando para cambiar de ramas
```
git branch "name branch"
```
## Comando para cambiar entre ramas
```
git switch "name branch"
```
## Comando para pegar los cambios de una rama a otra
```
git merge "name branch"
```
## Comando para generar un commit temporal que solo vemos nosotros
```
git stash
```
## Comando para ver la lista de stash
```
git stash list
```
## Comando para volver al lugar donde hiciste el stash
```
git stash pop
```
#### Aqui finaliza los comando de git
___
# GitHub
## Comando para crear las claves ssh
```
ssh-keygen -t ed25519 -C "your_email@example.com"
```




# Comandos para enlazar con git hub

## Comando para conectar con el repositorio
```
git remote add origin https://github.com/username/namerepository.git
```
## Comando para subir los archivos por primera vez al git hub
```
git push -u origin main
```
## Comando para subir los cambios 
```
git push
```
## Comando para bajar el historial pero no los archivos
```
git fetch
```
## Comando para bajar los cambios y los archivos
```
git pull origin main
```
