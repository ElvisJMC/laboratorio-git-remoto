# laboratorio-git-remoto

## Descripción de los pasos seguidos para completar el laboratorio.

1. Crea un repositorio local:

- Accedo al disco duro de mi ordenador y dentro de la carpeta que utilizo para practicar (llamada Lemoncode) creo una carpeta llamada laboratorio-git-local.

- Desde VS code abro la carpeta laboratorio-git-local e inicializo el repositorio con git init -b main. Lo he hecho de esta manera para establecer mi rama local como "main" al igual que la rama en remoto y así evitar tener dos ramas diferentes, la de remoto como "main" y la local como "master".

2. Subir el repositorio a GitHub

- Creo un nuevo repositorio público en GitHub llamado laboratorio-git-remoto y le añado un readme.md.

- Conecto el repositorio local con el de GitHub desde la terminal VS code on el comando git remote add origin + URL.

- Para verificar que se ha hecho la conexión correctamente, utilizo el comando git remote -v y obtengo la siguiente información:
origin  git@github.com:ElvisJMC/laboratorio0.git (fetch)
origin  git@github.com:ElvisJMC/laboratorio0.git (push)





