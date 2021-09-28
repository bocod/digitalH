*********************
    CLASE 6 - GIT
*********************

git init        inicializa git
rm -rf .git     remueve git

.gitkeep        creando un archivo con ese nombre permite a git trackear una carpeta vacía

Si quiero seleccionar una carpeta en especial del workspace:
    - click derecho: Open in Integrated Terminal
    - y ahí le damos el comando de git  init para que sea ESA carpeta la que se suba al repo

git add                             comando para agregar archivos al repo
git add .                           agrega toda la carpeta
git add archivo archivo archivo     agrega esos archivos con los últimos cambios en el repositorio local para luego commitearlos.


A la derecha del nombre  del archivo    U   Untracked
                                        A   Added
                                        M   Modified

git commit      empaqueta los archivos para presentar en un repositorio remoto. Además de agregar los cambios luego es importante commitearlos.
Genera una "Marca en el tiempo" que me permitirá volver atrás y revisar los cambios realizados.
Se completa el comando de la siguiente forma:

git commit -m "Mensaje"            -m le agrega un mensaje

!importante     Es necesario hacer el add previamente para preparar el paquete que luego se commiteará como "checkpoint" en el historial de cambios