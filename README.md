\# Documentación del Ejercicio Práctico de Git



\## Comandos Utilizados



1\. \*\*Inicialización y Configuración:\*\*

&#x20;  - `mkdir mi-proyecto-web \&\& cd mi-proyecto-web`

&#x20;  - `git init`

&#x20;  - `git config --global user.name "Enrique Romero Vargas"`

&#x20;  - `git config --global user.email "enriqueromerovargas2312@alumnos.alborfp.com"`



2\. \*\*Primer Commit:\*\*

&#x20;  - `git add index.html`

&#x20;  - `git commit -m "Primer commit: Estructura inicial de index.html"`



3\. \*\*Gestión de Ramas y Merge:\*\*

&#x20;  - `git checkout -b desarrollo`

&#x20;  - `git merge desarrollo`



4\. \*\*Resolución de Conflictos:\*\*

&#x20;  - `git checkout -b nueva-funcionalidad`

&#x20;  - Edición de `index.html` en ramas paralelas.

&#x20;  - Resolución manual de las marcas `<<<<<<<`, `=======`, `>>>>>>>` en `index.html`.

&#x20;  - `git add index.html` y `git commit -m "Resolver conflicto"`



5\. \*\*Repositorio Remoto:\*\*

&#x20;  - `git remote add origin https://github.com/enriqueromerovargas2312/ejercicio-git-practico.git`

&#x20;  - `git push -u origin main`

&#x20;  - `git push -u origin desarrollo`

&#x20;  - `git push -u origin nueva-funcionalidad`

