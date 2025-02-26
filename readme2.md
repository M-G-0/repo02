# COMANDOS DE GIT  

> Lista comandos básicos que hemos estado usando últimamente.


## Primeros comandos

`git init` inicializar *git* repositorio  
`git clone linkRepositorio`  
`git status` ver el estado del repositorio  


## Comandos necesarios para realizar commits

`git add .  ` subir todos los documentos al *staging area*  
`git commit -m "Mensaje que le ponemos al commit"` *commit* con mensaje  


## Seguimiento de nuestro workflow

`git adog` (después de crear alias) ver el log más práctico  


## Trabajando con ramas

`git branch nombreRama` crear nueva rama  
`git checkout nombreRama` cambiar a rama o commit  
`git switch nombreRama` cambiar a rama  
`git checkout -b nombreRama` crear y dirigirnos a nueva rama  
`git merge nombreRama` fusionar rama con la que estemos  


## Repositorio Local <-> Repositorio Remoto

`git push origin nombreRama` enviar hacia la nube  
`git pull origin nombreRama` bajar de la nube  
`git remote -v` ver configuración remota  

Estos serían todos los comandos básicos que hemos usado