# git branch

Una rama Git es simplemente un apuntador móvil apuntando a una de esas confirmaciones.

La rama por defecto de Git es la rama master. Con la primera confirmación de cambios que realicemos, se creará esta rama principal master apuntando a dicha confirmación. En cada confirmación de cambios que realicemos, la rama irá avanzando automáticamente. Y la rama master apuntará siempre a la última confirmación realizada.

Cuando se crea una nueva rama se crea un nuevo apuntador para que lo puedas mover libremente.

Git sabe en qué rama estás en cada momento mediante un apuntador especial denominado **HEAD**. En Git, HEAD es el apuntador a la rama local en la que tú estés en ese momento. En este caso, en la rama master. Puesto que el comando git branch solamente crea una nueva rama, y no salta a dicha rama.

Se pueden crear todas las ramas que necesiten.

Las ramas nuevas que se crean apuntal al commit actual, que es donde está **HEAD**.

`git branch --no-merged`
Muestra las ramas que no han sido fusionadas a la rama actual.

`git branch --merged`
Muestra las ramas que han sido fusionadas a la rama actual.
