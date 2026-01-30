\# Registro de Actividad Git



\## 1. Reparto de Tareas

\* \*\*David\*\*: Desarrollo de funcionalidades en rama individual (feature/david-alonso) y modificaciones en el README y el index. Creación y documentación del GIT\_LOG en la rama main.

\* \*\*Alberto\*\*: Desarrollo de funcionalidades en rama individual (feature/alberto-larios),modificaciones en README, index, styles y creación del Javascript.

\* \*\*David y Alberto\*\*: Gestión de integraciones en la rama 'main', uso de herramientas de limpieza de historial y documentación técnica.



---



\## 2. Conflictos Generados y Resolución

\* \*\*Bloqueo del Rebase\*\*: Durante la unificación de commits, el sistema operativo bloqueó la carpeta '.git/rebase-merge', impidiendo avanzar. Se solucionó cerrando procesos activos y eliminando manualmente el directorio de bloqueo con 'rm -rf'.

\* \*\*Rechazo de Push (Desincronización)\*\*: El servidor rechazó una subida porque el historial local era diferente al remoto. Se resolvió mediante un 'pull' y, posteriormente, un 'push --force' tras limpiar el historial con un rebase interactivo.



---



\## 3. Comandos Git más Relevantes

\* \*\*'git stash'\*\*: Para guardar cambios temporales y poder limpiar el entorno de trabajo antes de una integración.

\* \*\*'git rebase -i'\*\*: Para realizar el "squash" de commits y unificar mensajes redundantes como "README ModV1" y "README ModV2" en uno solo.

\* \*\*'git push --force'\*\*: Para actualizar GitHub con el nuevo historial unificado.

\* \*\*'git log --oneline'\*\*: Empleado para visualizar el historial de commits de forma compacta y verificar las etiquetas de las ramas.

\* \*\*'git status'\*\*: Comando fundamental para comprobar el estado de la rama actual y verificar si existían procesos de rebase activos o archivos pendientes.

\* \*\*':wq' (en Vim): Comando utilizado dentro del editor Vim para guardar los mensajes de merge y las instrucciones de unificación (squash) y salir del editor.



