# Creación del Repositorio



## 1. Creación del repositorio en GitHub

Lo primero que haremos será crear un nuevo repositorio en **GitHub**.

1. Accedemos a [GitHub.com](https://github.com) e iniciamos sesión.
2. En la parte superior derecha, hacemos clic en **"New"** o **"Crear nuevo repositorio"**.
3. Le damos un nombre, por ejemplo:  
   **PPS-Unidad0-Tarea-Ruben_OS**  
4. Marcamos la opción **"Add a README file"** (para que se cree el archivo `README.md` automáticamente).
5. Finalmente, hacemos clic en **"Create repository"**.

<img width="1918" height="1078" alt="Captura-repositorio" src="https://github.com/user-attachments/assets/bc0a1760-2e55-46ce-a08d-79f6b7d741fa" />



## 2. Creación de la estructura de carpetas y archivos

Una vez creado el repositorio, abrimos una terminal y ejecutamos los siguientes comandos para crear la estructura de directorios:


mkdir -p calculator docs .github/workflows
touch calculator/__init__.py calculator/gui.py
touch docs/index.md docs/git.md docs/gitActions.md docs/gitPages.md docs/docker.md docs/conclusiones.md
touch mkdocs.yml requirements.txt .github/workflows/CreacionDocumentacion.yml

con  el comando tree podemos ver la estructura


<img width="661" height="567" alt="Captura-estrutura-carpeta" src="https://github.com/user-attachments/assets/53dd275d-5e26-494a-91ff-c4f1a58b874c" />

