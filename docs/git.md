# Creación del Repositorio

## 1. Creación del repositorio en GitHub

Lo primero que haremos será crear un nuevo repositorio en **GitHub**.

1. Accedemos a [GitHub.com](https://github.com) e iniciamos sesión.  
2. En la parte superior derecha, hacemos clic en **"New"** o **"Crear nuevo repositorio"**.  
3. Le damos un nombre, por ejemplo:  
   **PPS-Unidad0-Tarea-Ruben_OS**  
4. Marcamos la opción **"Add a README file"** (para que se cree el archivo `README.md` automáticamente).  
5. Finalmente, hacemos clic en **"Create repository"**.

![Captura del repositorio](https://github.com/user-attachments/assets/bc0a1760-2e55-46ce-a08d-79f6b7d741fa)

---

## 2. Creación de la estructura de carpetas y archivos

Una vez creado el repositorio, abrimos una terminal y ejecutamos los siguientes comandos para crear la estructura de directorios:


mkdir -p calculator docs .github/workflows
touch calculator/__init__.py calculator/gui.py
touch docs/index.md docs/git.md docs/gitActions.md docs/gitPages.md docs/docker.md docs/conclusiones.md
touch mkdocs.yml requirements.txt .github/workflows/CreacionDocumentacion.yml
Con el comando tree podemos ver la estructura:



## 3. Clonación y subida del repositorio
A continuación, clonamos el repositorio en nuestro equipo local utilizando SSH, ya que tenemos configurada la conexión entre la terminal y GitHub mediante una clave SSH.


git clone 

<img width="651" height="565" alt="git-clone" src="https://github.com/user-attachments/assets/bbd13b82-528c-49ab-8423-76cf58468b34" />

Después de clonarlo, accedemos al directorio del repositorio y añadimos todos los archivos con el comando:

git add .


Con el siguiente comando podemos ver el estado del repositorio y comprobar qué archivos están listos para subirse:


git status


<img width="656" height="560" alt="git-status" src="https://github.com/user-attachments/assets/b697cfc7-7b18-40ad-81b2-56b9d11ecba1" />

Si queremos ver toda la estructura del proyecto, incluidos los archivos ocultos, usamos:


tree -a

<img width="663" height="582" alt="tree-a" src="https://github.com/user-attachments/assets/6b08df96-2add-40ae-8493-9634d86c2929" />

Cuando tengamos todo preparado, realizamos el commit con el mensaje correspondiente:


git commit -a -m "Añadida estructura inicial del proyecto"
Finalmente, subimos los cambios al repositorio remoto con:


git push

<img width="677" height="605" alt="git-push" src="https://github.com/user-attachments/assets/59d764f0-dbe7-4ec9-903c-04118d126db2" />


Ahora podemos revisar el repositorio en GitHub y comprobar que todos los archivos y carpetas se han subido correctamente.

<img width="683" height="408" alt="repositorio-final" src="https://github.com/user-attachments/assets/ed68b1ea-4d1b-44ae-bdb1-aad9d59a8dd3" />

