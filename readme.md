# Curso de Git

- Duración: 20 horas
- Modalidad: On-line
- Fechas: 22, 23, 24 y 25 Septiembre 2025
- Horario 9:30 – 14:30 hs.

## Contenidos

- Introducción
  - Qué es un SCV y qué un SCV distribuido
  - Historia de GIT: C, kernel linux, contexto (SVN, Mercurial, ...)
  - Anatomía de un SCV distribuido | diferencias/parecidos con centralizados
  - Instalación en Windows
  - CheatSheets y Libros recomendados
- Quick Start
  - Primer repo (init), primer commit
  - Configuración inicial: email y name
  - add/commit y status/log/show
  - Mensajes de commit
  - Anatomía de un repositorio git: staging area, index and cache
- Aprendiendo a referenciar revisiones y paths
  - Anatomía de comandos típicos, referencias VS paths
  - HEAD, master, HEAD~1 y otras referencias útiles
  - Números de commit: SHA1, subcadena de SHA1
  - Nombres de tags, de heads y de branches
  - Referencias por mensaje de commit (:/cadena)
  - Para saber más: SPECIFYING REVISIONS en "man gitrevparse"
- Herramientas para preparar un buen commit en cualquier situación
  - git add p
  - git rm, git mv
  - git diff
  - git blame | git log Sstring
  - .gitignore
- Rescribiendo la historia
  - amend
  - checkout
  - reset
  - stash
  - git clean n | git clean f
  - revert
  - rebase
  - git bisect
- Trabajando en paralelo
  - branches
    - crear, borrar, intercambiar
    - crear desde ref (git checkout b mybranch master~1)
  - tags: crear, usar
  - patches: crear, aplicar
  - remotes:
    - remote v
    - push/pull
    - clones
    - repos bare
    - push branch, push tag
  - resolución de conflictos
  - merge VS rebase VS cherrypick
  - Pull Request
    - Creación
    - Uso
    - Merging
    - Cierre
- Utilidades
  - GitK, GitG y git gui | git log graph | formato git log
  - IntelliJ
- Configuracion de git
  - alias
  - .gitconfig
    - editor
    - coloreado comandos
    - formato salida comandos
    - otras opciones
  - Hooks
    - cómo crear
    - hooks de lado cliente: commits, emails, rebase, ...
    - hooks de lado servidor: prereceive, postreceive, update
- Subproyectos
  - crear submodules
  - workflow de commits
  - git submodule status recursive
  - git submodule foreach ...
- Integración con otras herramientas y entornos
  - SourceTree
  - Github
  - Gitlab
  - Bitbucket
- Buenas prácticas
  - Commits atómicos
  - Commits frecuentes
  - No commits de trabajo a medias
  - Test antes de commit
  - Buenos mensajes de commit
  - Usar branches, featurebranching
  - Workflows
    - Presentar las opciones más usadas
    - Fijar un workflow común

## Calendario

### Dia 1.a (Lunes 22/09/2025)

Clase interrumpida por motivos técnicos

- Presentación profesor / alumnos
- Introducción: Qué es un SCV y qué un SCV distribuido
- IDE / Editor de código: Visual Studio Code (VSC)
- Terminales
- Instalación de Git
  Configuración inicial

## Dia 1.b (Martes 23/09/2025)

- Revisión: Instalación y configuración de Git
- Primeros pasos con Git
  - Primer repo (init), primer commit
  - Anatomía de un repositorio git: working directory, staging area (index o cache) y repositorio (.git)
  - Estados de un archivo: untracked (U), tracked (modified (M), staged (A), committed)
  - add/commit/reset y status/log/show
  - Mensajes de commit
- Anatomía de comandos típicos, referencias VS paths
  - HEAD, master, HEAD~1 y otras referencias útiles
  - Referencias por mensaje de commit (:/cadena)
- Integración con otras herramientas y entornos
  - Clientes gráficos
  - Entornos de desarrollo
  - Repositorios remotos: GitHub, GitLab, Bitbucket
- Git internals
  - Estructura de un repositorio git: .git
  - Objetos git: blobs, trees, commits (y tags)
  - Creación y lectura de objetos
  - Creación del árbol de objetos en un primer commit
  - Modificación del árbol de objetos en commits sucesivos
  - Referencias: heads, ramas (tags y remotes)
  - Taller: creación de un repositorio git "a mano"

## Dia 2 (Miércoles 24/09/2025)

- Herramientas para preparar un buen commit en cualquier situación
  - Comprobar el repositorio. Git log
  - Alias
  - Operaciones en la Staging Area (Index)
    - Añadir ficheros
    - Eliminar de la Staging Area (Index)
  - Eliminar ficheros
    - Problemas con .gitignore
  - Cambiar nombre de ficheros
  - git diff
  - git blame
  - Recapitulando: Git básico
- Reescribiendo la historia
  - Advertencia
  - git command --amend
  - git checkout
    - git checkout a nivel de archivo
  - git reset
    - git reset a nivel de archivo
  - rebase interactivo
    - edit: modificando un commit
    - squash y fixup: fusionando commits
    - drop: eliminando un commit

## Dia 3 (Jueves 25/09/2025)

- Reescribiendo la historia (continuación)
  - Ref logs
  - Otros comandos
    - git stash
    - git clean
    - git revert
    - git bisect
- Trabajando en paralelo
  - Ramas
    - Crear y seleccionar
      - Crear desde referencia
    - Ver ramas
    - Borrar ramas
    - Mover y renombrar ramas
  - Combinación de ramas: Merge y Rebase
    - git merge
    - git rebase
    - git cherry-pick
    - Resolución de conflictos
  - Repositorios remotos
    - Repositorios "bare"
    - Clonar repositorios: git clone
    - git remote
    - git push
    - git pull (fetch + merge)
  - Pull Request / Merge Request
    - Creación
    - Uso
    - Merging -> actualización local
    - Cierre

### Dia 4 (Viernes 26/09/2025)

- Trabajando en paralelo (continuación)
  - Tags
  - Patches
  - Workflows
    - Presentar las opciones más usadas
    - Fijar un workflow común
  - Configuración de Git
    - Hooks
      - Hooks disponibles
        - hooks de lado cliente: commits, emails, rebase, ...
        - hooks de lado servidor: prereceive, postreceive, update
      - Husky (Utilidad para gestionar hooks en JS)
  - Submódulos
    - Crear submódulos
    - Workflow de commits
    - git submodule status recursive
    - git submodule foreach ...
  - Buenas Prácticas
