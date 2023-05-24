# FED-2405-Layout

**SI NO HE EMPEZADO A TRABAJAR**

- Me creo un repositorio con README y licencia desde GitHub
- git clone url-del-repositorio 
- Trabajo
- git add . (para añadir los cambios a la zona de staging)
- git commit -m *mensaje* (para poner el mensaje que va a aparecer en el commit)
- git push (esto sube los cambios a la nube)

### Si tenía algún cambio en la nube que no tengo en local

Me va a dar error al hacer el git push, debo hacer primero un git pull.

Para hacer un git pull debo tener mis cambios commiteados.

### Si existe un conflicto

Al hacer git pull puede surgir un conflicto, lo resuelvo en el Merge Editor indicando qué versión quiero quedarme, y desde la propia interfaz de Git del VS le doy a merge y sync changes.

**SI YA HE EMPEZADO A TRABAJAR Y QUIERO SUBIR LOS CAMBIOS AL REMOTO**

- Me creo un repositorio vacío desde GitHub
- Me voy a la carpeta donde tengo mis archivos ya creados y hago git init (SOLO UNA VEZ)
- git remote add origin url-del-repositorio (esto enlaza el repo remoto con el local)
- git add .
- git commit -m *mensaje*
- git push