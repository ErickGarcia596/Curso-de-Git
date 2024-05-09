# ¡BIENVENIDOS AL CURSO DE GIT!
# CLASE 1
## Introduccion a GIT:
### ¿Que es un control de versiones?
Cambios que se realizan en código fuente u otro archivo y saber quien los realizó.
La importancia radica en:
1. Rendimiento.
2. Seguridad.
3. Flexibilidad.
### ¿Que es GIT?
Sistema distribuido que aloja una copia completa del repositorio en cada maquina local.
### ¿Que es un repositorio?
Es una carpeta en la que se almacenan las diferentes versiones de los ficheros de un proyecto.
### Los 3 estados de GIT
1. Modified.
2. Staged.
3. Commited.
### Comandos aprendidos
1. Comando "git init": Es un comando para inicializar GIT en un directorio.
2. Comando "git status": Es para ver enque estado se encuentran los archivos.
3. Comando "git add":  Indica a git si queremos añadir actualizaciones de un archivo.
4. Comando "git commit": Comando para generar regitro de un cambio.

# CLASE 2
## Ramas
### ¿Que es una rama?
Son una instantanea de la division del estado del codigo.
### ¿Para que sirven las ramas?
Permiten realizar un desarrollo no lineal y colaborativo. Cuando creamos una rama se crean desde el ultimo commit.
### Comandos aprendidos de inicializacion
1. Comando "git branch": Permite ver las ramas que se tienen creadas.
2. Comando "git branch "nombre de la rama"": Para crear una rama el nombre debe ser explicativo.
3. Comando "git switch "nombre de la rama"": Para cambiarnos a la rama que escojamos.
4. Comando "git checkout "nombre de la rama"": Para cambiarnos a la rama que escojamos. Tambien sirve para deshacer cambios.
5. Comando "git checkout -b "nombre de la rama"": Para crear una rama y cambiarnos a la que acabamos de crear.
## Fusionar ramas
Nos referimos que a los cambios que hemos realizado en la rama se intengran en otra rama, de forma que el codigo que habiamos generado en la nueva rama se asimila en otra.
### Comando aprendidos para fusion
1. Comando "git merge "nombre de la rama que queremos fusionar"": Para incorporar los cambios de una rama a la rama en la que nos encontramos en ese momento.
## Eiminar ramas ¿Porque?
Porque es una buena practica y mantenemos limpio el espacio de trabajo.
### Comandos aprendidos para eliminar ramas
Primeramente solo me deajara borrar las ramas que ya he fucionado y las que no estan fusionadas y se tratan de borrar me saladra un mensaje.
1. Comando "git branch -d "nombre de la rama a eliminar"": Para eliminar una rama.
### Comandos extra
1. Comando "git log --oneline": Solo me muestra el nombre de los commits.
2. Comando "git log --graph": Me muestra el historico como con graficos.
3. Comando "git mearge header --no-ff"
4. Comando "git log --graph --online"

ghhghg