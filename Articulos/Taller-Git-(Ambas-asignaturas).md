Dentro del taller inicial de GIT, se buscará la comprensión del uso de GIT y la automatización con Azure Devops de manera totalmente práctica.

Este taller considera 2 clases y el objetivo es poder levantar su propio sitio web de gestión de contenidos, tal como está hoy en nuestro sitio documental (https://uv.trifenix.io).

En el taller podrán distribuir archivos [markdown](https://es.wikipedia.org/wiki/Markdown) y automatizar la distribución tanto en wikis, como sitios web.

# Porque el mismo contenido en ambas clases.

1. Para el caso de Arquitectura de software, GIT es dependiente para el curso de docker y Devops es parte principal del contenido de la asignatura.

2. Para el curso de desarrollo web, el uso de GIT es fundamental, es la herramienta de uso constante para cualquier desarrollador (no exclusivo), la comprensión de Devops será necesaria para la distribución de los programas construidos en próximas clases ([CI](https://en.wikipedia.org/wiki/Continuous_integration)/[CD](https://en.wikipedia.org/wiki/Continuous_delivery)).


# Material

Con el fin de poder mirar, comparar y seguir el curso, dispondrán de un usuario con acceso a github y azure devops. Este usuario es exclusivamente para poder revisar y construir su propio sitio.

## Usuario devops
user:  usuario.git1@trifenix.io
pass: [preguntar en clase]

## Usuario github
user: 3fnx-git1
pass: [preguntar en clase]

## Devops
El usuario tiene acceso a dos organizaciones dentro de Azure Devops.

### 1. devops de uv.trifenix.io
En el azure devops del sitio documental podrán ver los scripts y tareas programadas destinadas a actualizar la wiki del mismo y la actualización del sitio https://uv.trifenix.io

### 2. devops cliente
Este vendría a ser el devops que cada alumno debe tener con el fin de actualizar y enviar sus trabajos y documentos hacia https://uv.trifenix.io a través de la automatización de la wiki.


### 3. github uv.trifenix.io
Este github es público, la modificación de documentos en este github gatillará la creación del sitio web y la actualización de la wiki del proyecto.

### 4. github cliente
Cada alumno debe tener un fork del repositorio de documentación, en él podrán solicitar un [pull request]() al github principal.
























