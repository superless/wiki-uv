---
title: "Taller Git Devops JamStack"
metaTitle: "Desarrollo web y Arquitectura de software"
metaDescription: "Taller destinado a gestión documental sobre devops"
---

Dentro del taller inicial de GIT, se buscará la comprensión del uso de GIT y la automatización con Azure Devops de manera totalmente práctica.

Este taller considera 2 clases y el objetivo es poder levantar su propio sitio web de gestión de contenidos, tal como está hoy en nuestro sitio documental (https://uv.trifenix.io).

En el taller podrán distribuir archivos [markdown](https://es.wikipedia.org/wiki/Markdown) y automatizar la distribución tanto en wikis, como sitios web.

El objetivo final es que cada alumno participe en la creación de su propio sitio, con el que podrá validar antes de subir documentación en el sitio [https://uv.trifenix.io](https://uv.trifenix.io).

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

https://dev.azure.com/yo-fenix/blog


### 2. devops cliente
Este vendría a ser el devops que cada alumno debe tener con el fin de actualizar y enviar sus trabajos y documentos hacia https://uv.trifenix.io a través de la automatización de la wiki.

https://dev.azure.com/usuariogit1


### 3. github uv.trifenix.io
Este github es público, la modificación de documentos en este github gatillará la creación del sitio web y la actualización de la wiki del proyecto.

https://github.com/trifenix/wiki-uv

### 4. github cliente
Cada alumno debe tener un fork del repositorio de documentación, en él podrán solicitar un [pull request](http://aprendegit.com/que-es-un-pull-request/) al github principal.

https://github.com/3fnx-git1/wiki-uv

# Información adicional
- El proyecto considera la creación de su propio sitio web, utilizando www.netlify.com 

- Si desea tener su propio dominio, puede hacer uso de los dominios gratuitos otorgados por [github student pack.](https://education.github.com/pack).



- El trabajo puede ser hecho individual o en parejas.

- El trabajo es colaborativo, son libres de compartir código, mientras se haga con git.

- Cualquier contribución adicional del proyecto será considerado con puntos adicionales. 

- Si esa contribución adicional deriva en Forks de otros alumnos, ambos tendrán puntos.
 
- En arquitectura de software se evaluará principalmente devops, para desarrollo web git. 

- Si un alumno tiene solo una de las asignaturas, se evaluará devops principalmente en el caso de Arquitectura de software y git en caso de Web.

- Si un alumno que tiene una sola asignatura y logra completar todo el proyecto, tendrá un 7.0 y tendrá puntos adicionales para la próxima evaluación.

- La evaluación será puesta en el pull request.

- En el pull request, se podrá pedir que se explique algún commit realizado, con el fin de la comprensión del proceso y la evaluación.

 



# Como se evaluará el taller.
1. Aplicación Web, con dominio y pull request al sitio web principal 7.0
2. Pull Request al sitio web principal, usando un fork. 4.0.
3. Si no hace un pull request 1.0

Las notas intermedias dependerán de la historia de git que muestre cada alumno.



























