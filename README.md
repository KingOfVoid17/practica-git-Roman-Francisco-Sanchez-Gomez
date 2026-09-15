**NOMBRE**: Román Francisco Sánchez Gómez
**Matricula**: 2630012

# Creación y sincronización de repositorio con Git y GitHub

## Sincronizar los repositorios de Git a GitHub

### 1.Crear una carpeta en la computadora
se creo una carpeta donde se inicio un repositorio de Git despues de agregar los documentos que vamos a usar usando el **git add** y posterior mente hacer un **git commit**.
### 2.Crear una carpeta en GitHub
Se crea un repositorio en GitHub y lo vinculamos con el git y usando un **URL** y enviando el **git push** para enviarlo de el repositorio de git a git hub.


# Comando de Git utilizados


|comando|Funcion|
|-|-|
|`git init`|Inicializar un nuevo repositorio de Git en una carpeta local|
|`git status`|Muestra el estado de los archivos y los cambios pendientes|
|`git add nombre_archivo.`|Agrega un archivo en espesifico puede cambiar *-A* para enviar todo|
|`git commit -m "mensaje"`|guardar los documentos y agrega un texto para ubicarlo|
|`git log`|Muestra el historial de los *commit*|
|`git branch -M main`|cambiar el nombre de la rama principal a main|
|`git remote add origin URL`|vincular el repositorio local con el repositorio de Git a el repositorio de GitHub|
|`git push`|enviar los documentos del repositorio local al repositorio remoto|

## Explicación de cómo se creó el repositorio local

Para crear el repositorio local, primero se creó una carpeta destinada al proyecto. Después, desde la terminal se ingresó a dicha carpeta y se ejecutó el siguiente comando:

`git init`

Este comando convirtió la carpeta en un repositorio Git, creando internamente la información necesaria para que Git pudiera registrar y controlar los cambios realizados en los archivos.

Posteriormente, los archivos del proyecto se agregaron utilizando `git add .` y se realizó un primer registro de cambios con:

`git commit -m "Primer commit"`

De esta manera, el proyecto comenzó a tener un historial de versiones almacenado localmente en la computadora.

## Explicación de cómo se vinculó el repositorio local con GitHub

Después de crear el repositorio local, se creó un repositorio nuevo en GitHub. GitHub proporcionó una URL que identifica al repositorio remoto.

Para conectar ambos repositorios se utilizó el comando:

`git remote add origin URL_DEL_REPOSITORIO`

La palabra `origin` funciona como un nombre para identificar el repositorio remoto principal. Después de ejecutar este comando, el repositorio local quedó vinculado con el repositorio creado en GitHub.

## Explicación de la sincronización Local → GitHub

La sincronización desde la computadora hacia GitHub se realizó después de guardar los cambios mediante un commit.

El proceso fue el siguiente:

1. Modificar o crear archivos.
2. Verificar los cambios con `git status`.
3. Agregar los cambios con `git add .`.
4. Guardarlos en el historial con `git commit -m "Descripción del cambio"`.
5. Enviarlos a GitHub utilizando `git push`.


De esta forma, los cambios realizados en el repositorio local fueron enviados al repositorio remoto, permitiendo que la versión almacenada en GitHub se mantuviera actualizada.

## Explicación de la sincronización GitHub a Local

Para actualizar el repositorio local con los cambios realizados en GitHub se utilizó el comando:

`git pull`

Este comando descarga los cambios existentes en el repositorio remoto y los integra en los archivos almacenados localmente.

La sincronización GitHub → Local es útil cuando se realizaron cambios desde otra computadora, desde la página de GitHub o cuando varias personas trabajan en el mismo proyecto.

## Descripción de los archivos contenidos en el repositorio

El repositorio contiene los archivos 2 siguientes archivos

un archivo `README.md`, el cual contiene información general sobre el proyecto, como su nombre, objetivo, instrucciones de uso y descripción de los archivos.

y un txt que demuestra las actualizaciones que se le puede hacer desde el git al github y de github a git

## Conclucion
Al vincular Git con GitHub podemos enviar proyectos y codigos a la nube y que otras personas modifiquen nuestros codigos sin modificar nuestro codigo original