\# Documentación del Ejercicio Práctico de Git



\## 1. Inicialización del Repositorio

\- Creación de la carpeta del proyecto y navegación a ella.

\- Comando: `git init`



\## 2. Configuración Inicial

\- Configuración de usuario y correo global:

&#x20; - `git config --global user.name "Enrique Romero Vargas"`

&#x20; - `git config --global user.email "enriqueromerovargas2312@alumnos.alborfp.com"`



\## 3. Primer Commit

\- Creación del archivo `index.html` con la estructura inicial de HTML.

\- Inclusión al área de preparación y commit:

&#x20; - `git add index.html`

&#x20; - `git commit -m "Primer commit: Estructura inicial de index.html"`



\## 4. Creación de Ramas

\- Creación y cambio a la rama de trabajo:

&#x20; - `git checkout -b desarrollo`



\## 5. Modificación y Merge

\- Edición de `index.html` añadiendo un nuevo párrafo en la rama `desarrollo`.

\- Commit de los cambios: `git commit -m "Añadir párrafo adicional en rama desarrollo"`

\- Cambio a `main` y fusión: `git checkout main` y `git merge desarrollo`



\## 6. Resolución de Conflictos

\- Creación de la rama `nueva-funcionalidad` y edición de `index.html`.

\- Cambio a `main` y modificación de la misma línea en `index.html`.

\- Ejecución de `git merge nueva-funcionalidad` resultando en un conflicto de fusión.

\- Edición manual del archivo `index.html` para retirar las marcas de conflicto (`<<<<<<<`, `=======`, `>>>>>>>`) manteniendo ambas líneas.

\- Confirmación de la resolución: `git add index.html` y `git commit -m "Resolver conflicto entre main y nueva-funcionalidad"`.



\## 7. Trabajo con Repositorios Remotos

\- Vinculación con GitHub: `git remote add origin https://github.com/enriqueromerovargas2312/ejercicio-git-practico.git`

\- Subida de todas las ramas:

&#x20; - `git push -u origin main`

&#x20; - `git push -u origin desarrollo`

&#x20; - `git push -u origin nueva-funcionalidad`

