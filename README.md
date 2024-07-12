# ansible-practica
ansible

Objetivo:
Este desafío tiene como objetivo validar que contamos con un entorno de
desarrollo válido y
realizar una actividad para modularizar un proyecto.
Requisitos:
1. Adaptar la estructura del proyecto para reducir la cantidad de líneas.
2. Identificar y crear posibles variables que se puedan reutilizar.
3. Mover lógica del playbook a archivos específicos.
4. Testar y validar que todo funciona.

Desafío 6.

Para este desafío lo que hice fue modificar todas las tareas que estaban
colocadas en el código del archivo main y las distribuí en dos carpetas.
Una carpeta llamada “apache” para tareas sobre la instalación y
configuración de apache y otra carpeta llamada “site-estatic” para las
tareas que van a modificar el sitio estático.
Estas dos carpetas fueron creadas dentro de la carpeta ya creada
“includes”.

Con esto logramos dejar el código más legible y así podemos ubicar las
tareas directamente desde sus archivos específicos y ordenadas en sus
carpetas según las funciones que cumplen.

En el pdf podemos ver una correcta salida, realizada desde la instancia controller
en la shell de multipass.
