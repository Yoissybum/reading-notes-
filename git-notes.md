# **Comandos Importantes de Git**

## **📌Comandos para la Terminal** 🖥️

### 1. `mkdir nombreCarpeta` - Para crear una carpeta 📁
Creamos una carpeta en el directorio actual.

### 2. `touch nombreArchivo.html` - Para crear un archivo 📄
Creamos un archivo en el directorio actual (con extensión .html, .css, .txt, .md y demás).

### 3. `cd nombreCarpeta` - Para ir a un directorio ➡️
Entramos a una carpeta específica.

### 4. `cd ..` - Para regresar al directorio anterior ⬅️
Salimos de la carpeta que estábamos.

### 5. `ls` - Para listar los archivos 📋
Muestra todos los archivos y carpetas en el directorio actual.

### 6. `ls -R` - Para hacer un listado recursivo 🔄
Muestra todos los archivos y carpetas, y subcarpetas.

### 7. `rm -fr nombreCarpeta` - Para eliminar una carpeta y su contenido sin confirmar ❌
Eliminamos una carpeta y todo lo que contiene.

### 8. `rm nombreArchivo` - Para eliminar archivos 🗑️
Eliminamos archivos específicos.

### 9. `code .` - Para abrir VS Code 💻
Abrimos el directorio actual en Visual Studio Code.

### 10. `pwd` - Para mostrar el directorio actual 📍
Mostramos la ruta completa del directorio donde estamos.

### 11. `mv carpetaActual/nombreArchivo carpetaNueva/` - Para mover o renombrar archivos 📦
Movemos o renombramos archivos o directorios.

### 12. `cp carpetaActual/nombreArchivo carpetaParaCopiar/` - Para copiar archivos 📂
Copiamos ese archivo y está ahora en ambas carpetas.

### 13. `git log` - Para ver el historial de commits 📜
Muestra el historial completo de commits realizados en el repositorio.

### 14. `git clone <URL>` - Para clonar un repositorio remoto 🌐
Clonamos un repositorio desde GitHub u otro servidor.

## **📌 Flujo de Trabajo con Git** 

### 15. `git init` - Para iniciar un repositorio Git 🚀
Inicia un nuevo repositorio Git en la carpeta.

### 16. `git status` - Para ver el estado del repositorio 📊
Muestra el estado actual del repositorio, qué archivos han cambiado o están listos para commit.

### **_⚠Flujo A - C - P:_** 

### 17. `git add .` - Para preparar los archivos para el commit ✅
Añadimos todos los archivos modificados o nuevos al área de preparación.

### 18. `git commit -m "Mensaje del commit"` - Para crear un commit 📝
Creamos un commit con los cambios realizados.

### 19. `git push origin main` - Para subir cambios a GitHub ⬆️
Enviamos los commits a GitHub para que otros los vean.