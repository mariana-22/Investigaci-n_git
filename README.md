# Comandos básicos de Git y GitHub,

*Este documento contiene los comandos mas imprtantes para empezar a usar git("control de  versiones ) y GitHub (plataforma en la nube para repsitorios ).*

## configuraccion inicial.
*Antes de usar git por primera vez:*

`git config--global user.name"tunombre"`
`git config--global user.email "tuemail@example.com"`

**Comandos basicos de Git**

*Git init:Git init se utiliza para crear un nuevo repositorio git o reinicializar uno existente. Al ejecutar el comando, se crea un subdirectorio llamado git dentro del directorio actual que contiene todos los metadatos de git necesarios para el nuevo repositorio.*


*Git status:Git status muestra el estado actual del directorio de trabajo y del area de preparación en un repositorio Git.Es utl para identificar cambios preparados,no preparados y archivos no rastreados.*


*Git add archivo.txt:Se utiliza para agregar el contenido de un archivo especifico al inidice Git,que es la lista de cambios que se incluiran en el proximo commit.Esto permite a Git rastrear y administrar los cambios realizados en los archivos del directorio de trabajo.*

*Git commit -m:Se utuliza para hacer un "commit" o confirmación de los cambios realizados en el proyecto,agregando un mensaje que describe dichoos cambios.Es decir permite guardar un estado "instantanea" acatual del proyecto acompañado de uhn mensaje explicativo que documenta que se ha modidficado.*


*Git clone:Se usa para crear una copia local exacta de un repositorio Git existente. Esto significa que clona o copia todo el repositorio, incluyendo su historial completo de versiones, ramas y archivos, en un nuevo directorio en la máquina local o en otra ubicación especificada.*


*Git push:Es un comando de Git que se utiliza para transferir y guardar en un repositorio remoto los cambios que previamente han sido confirmados en el repositorio local. Su función principal es sincronizar el trabajo realizado en la computadora del usuario con el repositorio en línea, de manera que los cambios queden almacenados de forma segura y puedan ser compartidos o consultados por otros colaboradores.*




## Historial y Ramas🌿⏱️


**Git branch**
`git branch`
`git branch nombre_rama`
`git branch -d nombre_rama`


*Sirve para trabajar con ramas. Con `git branch` puedes ver la lista de ramas y en cuál estás ubicado.*
*Con `git branch nombre_rama` creas una nueva rama para desarrollar funcionalidades sin afectar la principal.*
*Finalmente, con `git branch -d nombre_rama` puedes eliminar una rama que ya no necesitas.*

**Git checkout**
`git checkout nombre_rama`


*Permite cambiar de una rama a otra dentro del repositorio.*


**Git merge**
`git merge nombre_rama`


*Fusiona el contenido de una rama con la rama actual.*
*Se utiliza principalmente para integrar el trabajo de una rama secundaria (por ejemplo, feature) con la rama principal (main o develop).*


**Git log**


`git log`


*Muestra el historial de commits realizados en el proyecto.*
*Incluye información como autor, fecha, identificador único (hash) y el mensaje del commit. Es útil para consultar los cambios hechos en el tiempo.*




## Actualizar y fusionar📥

**Git push**
`git push origin main`


*Envía los cambios confirmados en el repositorio local hacia el repositorio remoto.*
*Este comando es esencial cuando trabajas en equipo, ya que publica tu trabajo para que otros lo vean.*

**Git pull**
`git pull`


*Descarga y fusiona los cambios más recientes desde el repositorio remoto con tu rama local.*
*Es recomendable ejecutarlo antes de trabajar para asegurarte de estar actualizado con los cambios de otros colaboradores

---

###  Otros comandos útiles de Git (con explicación detallada)

* *git stash* → Guarda temporalmente los cambios que aún no quieres confirmar (commit).
   Ejemplo: si estás trabajando en una nueva funcionalidad, pero necesitas cambiar rápidamente de rama, puedes guardar tus cambios en el stash sin perderlos.

* *git stash pop* → Recupera los cambios que habías guardado con git stash y los aplica de nuevo en tu área de trabajo.
   Esto es útil cuando ya terminaste lo que estabas haciendo en otra rama y quieres continuar con el trabajo anterior.

* *git remote -v* → Muestra los repositorios remotos asociados a tu proyecto y sus URLs.
   Sirve para confirmar si tu proyecto está conectado a GitHub, GitLab o cualquier otro repositorio remoto.

* *git tag* → Lista todas las etiquetas (tags) creadas en el repositorio.
   Los tags se usan normalmente para marcar versiones importantes de un proyecto, como una *v1.0* estable.

* *git tag -a v1.0 -m "Versión 1.0"* → Crea una nueva etiqueta anotada (con mensaje y metadatos como fecha, autor, etc.) llamada *v1.0*.
   Esto se utiliza para identificar una versión específica del proyecto en la historia de commits.

---

















