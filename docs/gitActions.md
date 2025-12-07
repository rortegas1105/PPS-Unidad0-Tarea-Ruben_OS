# Configuración del Flujo de Trabajo y GitHub Pages

## Configuración del flujo de trabajo

Tenemos que rellenar el documento `CreacionDocumentacion.yml`.

<img width="802" height="710" alt="Creaciondocumentoyml" src="https://github.com/user-attachments/assets/d65961fb-2ad0-4aaa-92b4-28aa9d271b2a" />


El `name` es el nombre del workflow y debe funcionar cuando se hace un `push` en la rama principal.  
Debe tener permisos de escritura y ejecutarse en una máquina Ubuntu.

Después de configurarlo, podemos ir a nuestro repositorio, darle a **Actions** y podremos ver nuestro flujo de trabajo.

<img width="692" height="397" alt="repositorio-workflow" src="https://github.com/user-attachments/assets/277b38d4-686c-4e43-93ce-f832a8aed3b4" />


## Activar GitHub Pages

Vamos a activar GitHub Pages:  

1. Nos metemos en **Settings**.  
2. Seleccionamos **Pages** y lo configuramos.  
3. Le indicamos la rama desde donde se va a coger el contenido, en este caso `gh-pages`.

<img width="681" height="391" alt="settings-ghpages" src="https://github.com/user-attachments/assets/f0cc5fe3-75c3-47ae-bc6c-3171b337d1a1" />



Esto creará el `.io` correspondiente. En mi caso sería:

rortegas1105.github.io



Y la URL completa de mi página es:

https://rortegas1105.github.io/PPS-Unidad0-Tarea-Ruben_OS/



Al meternos en el enlace, podemos ver cómo es mi página.

<img width="1917" height="1078" alt="paginaios" src="https://github.com/user-attachments/assets/ff6ca3fd-5917-4dbe-b965-490ae3e5be6f" />

