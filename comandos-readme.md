configurar:
git config - -global user.name "name"
git config - - global user.email "email"

git config - - list

Para crear un repositorio
git clone [url]    o   git init 

Para verificaciones
git status
git log
git diff
git branch

Agregar

git add.
git add [archivo]

Mover

git commit -m "[mensaje]"

Enviar/Actualizar
git push

Bajar/Actualizar
git pull

Cambiar
git checkout -b [branch-name]

git merge
git switch
git restore --source [hash] [archivo]


para ver el status de un archivo es con: git status
para agregar los cambios recientes: git add .
 git commit -m "Agrega archivo de contacto"
para agragar el archivo al github: git push 
para ver los cambios en el bash de git: git diff 
git log --oneline

PARA REGRESAR A UNA VERSION EN CONCRETA:

git log --oneline
git restore --source f268c09 index.html
git commit -m "Actualiza el index"
git push

para saber cuantas ramas tenemos: git branch

para crear una nueva rama:  git checkout -b

para cambiar de ramas: git switch nombrederama

cuando estoy en una rama secundaria a la main: git push origin rama-donde-estes

Para unificar las ramas uso: git merge
