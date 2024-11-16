# Guía para Subir Archivos a GitHub

Esta es una pequeña guía paso a paso para subir archivos a GitHub utilizando Git Bash.

## Instalación de Git Bash

1. Descarga [Git Bash](https://git-scm.com/) según tu sistema operativo (Windows o Linux).
2. Sigue las instrucciones de instalación, seleccionando "Next" en todas las opciones.

## Navegación y Operaciones Básicas

- `ls`: Muestra la lista de archivos y carpetas en la terminal.
- `ls -al`: Muestra la lista de archivos y carpetas en la terminal, incluso los ocultos
- `pwd`: Indica la ubicación actual.
- `cd NombredelaCarpeta`: Navega internamente en una carpeta.
- `cd ..`: Sale de la carpeta actual.
- `mkdir NombredelaCarpeta`: Crea una nueva carpeta.
- `touch NombreArchivo.extension`: Crea un nuevo archivo.
- `cat NombreArchivo.extension`: Ver el contenido de un archivo.
- `rm NombreArchivooCarpeta`: Elimina un archivo o carpeta.
- `nv Archivo1.extension Archivo2.extension `: Cambia el nombre de un archivo

## Subir Archivos a GitHub

1. `git init`: Inicializa una carpeta como un repositorio localmente.
2. `git add Nombrearchivo` o `git add .`: Añade archivos al área de preparación.
3. `git commit -m "Mensaje para el commit"`: Realiza un commit con un mensaje descriptivo.
4. `git remote add origin url-del-github`: Conecta el repositorio local con el remoto en GitHub.
5. `git push -u origin master` o `git push -u main`: Sube los archivos al repositorio en GitHub.
6. `git status`: Muestra el estado actual; si está en verde, está listo para ser agregado.

Recuerda repetir los pasos 2, 3 y 5 al actualizar o eliminar archivos.

🚀 ¡Listo para subir tus archivos a GitHub! 🚀
