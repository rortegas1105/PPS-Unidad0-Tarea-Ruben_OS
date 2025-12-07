# Publicación de la documentación con Docker

Para publicar la documentación generada por MkDocs mediante un contenedor NGINX, se realizaron los siguientes pasos:

**Cambiar de rama a `gh-pages`**  
   Primero, cambiamos de la rama `origin` a la rama `gh-pages`, donde se encuentra la documentación estática generada por MkDocs:

   git checkout gh-pages

 <img width="637" height="432" alt="cambio-rama-origin-pages" src="https://github.com/user-attachments/assets/09830fd3-9581-4ead-9fce-fa5004f1ab5d" />
  
   
**Crear y ejecutar el contenedor NGINX**
A continuación, se creó el contenedor NGINX con Docker, utilizando un bind mount para servir la carpeta site/ y redirigiendo el puerto 80 del contenedor al puerto 8085 de la máquina local:


Para comprobar que el contenedor se creó y está en ejecución correctamente, se utilizó:


docker ps

<img width="785" height="680" alt="creacion-contenedor" src="https://github.com/user-attachments/assets/897092a3-5d61-4c69-9350-64afdf1600d3" />



**Visualizar la página localmente**
Finalmente, gracias a la redirección de puertos, se puede visualizar la documentación en el navegador a nivel local accediendo a:



http://localhost:8085/

<img width="1918" height="1078" alt="localhost8085" src="https://github.com/user-attachments/assets/8e27a070-cb5e-40ce-b76a-09ea5ae9e5f9" />


**Por ultimo utilizamos el comando docker inspect**


<img width="1918" height="1078" alt="docker-inspect" src="https://github.com/user-attachments/assets/477af789-ec7d-485a-a496-f9fb0490d86f" />
