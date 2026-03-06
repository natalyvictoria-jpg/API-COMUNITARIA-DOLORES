<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" alt="" />
</p>

<h1 align="center">
  🌐💻 APLICACIONES WEB ORIENTADA A SERVICIOS
</h1>


## GTID153

📘 **Materia:** Aplicaciones Web Orientada a Servicios  
👩‍💻❤️ **Nombre:** Nataly Victoria Gonzalez Aviles  
🏫 **Proyecto o Actividad:** API COMUNITARIA DOLORES HGO
📅 **Unidad:** 3  
⚙️ **Lenguaje:** Python  
🧠 **Propósito:** Desarrollar aplicaciones web utilizando APIs diferentes, aplicando los conocimientos adquiridos en la unidad 3 y comprendiendo su funcionamiento mediante su implementación en Python.  
👨‍🏫 **Docente:** Anastacio Rodriguez Garcia

# API Comunitaria Dolores Hidalgo

## Descripción del Proyecto

La API Comunitaria Dolores Hidalgo es un servicio web desarrollado utilizando Python y el framework Flask. Su objetivo es proporcionar información relacionada con la comunidad, como datos generales del municipio y registro de artesanos.

Este proyecto fue creado como parte del aprendizaje en el desarrollo de APIs modernas, aplicando el modelo REST y utilizando buenas prácticas en la organización del código.

La API permite que diferentes aplicaciones puedan consultar información mediante solicitudes HTTP, lo que facilita la integración entre sistemas web, aplicaciones móviles u otros servicios.

## Objetivos del Proyecto

- Comprender el funcionamiento de las APIs REST.

- Desarrollar un servicio web utilizando Python y Flask.

- Implementar endpoints para la consulta de información comunitaria.

- Organizar el proyecto utilizando una estructura modular.

- Documentar correctamente el funcionamiento de una API.

## Tecnologías Utilizadas

Python 3
Flask
JSON
Visual Studio Code
Git
GitHub

## Estructura del Proyecto

El proyecto fue organizado utilizando una arquitectura modular para facilitar el mantenimiento del código y permitir que la API pueda crecer en el futuro.

La estructura general del proyecto contiene los siguientes componentes:

## Carpeta app
Contiene el código principal de la aplicación, incluyendo la configuración y las rutas de la API.

## Carpeta routes
Contiene los diferentes endpoints organizados en archivos separados.

## Archivo run.py
Es el archivo principal encargado de ejecutar el servidor de Flask.

## Archivo config.py
Define la configuración del proyecto como el nombre de la API y su versión.

## Archivo requirements.txt
Contiene las dependencias necesarias para ejecutar el proyecto.

## Archivo README
Describe el funcionamiento del proyecto y la forma de utilizar la API.

# Instalación del Proyecto

Para ejecutar el proyecto en un entorno local es necesario seguir los siguientes pasos.

Primero se debe clonar el repositorio desde GitHub.

Después se debe acceder a la carpeta del proyecto.

Posteriormente se debe crear un entorno virtual de Python para instalar las dependencias necesarias sin afectar otras aplicaciones del sistema.

Una vez creado el entorno virtual, se debe activar y proceder a instalar las dependencias del proyecto utilizando el archivo requirements.

Finalmente se puede ejecutar la aplicación utilizando el archivo run.py.

Cuando el servidor se inicia correctamente, la API queda disponible en la dirección local del servidor.

## Ejecución de la API

Una vez iniciado el servidor, la API se ejecuta localmente en la siguiente dirección:

http://127.0.0.1:5000

Desde esta dirección es posible acceder a los diferentes endpoints que ofrece la API.

Endpoints de la API

Página principal

Este endpoint muestra un mensaje de bienvenida indicando que la API está funcionando correctamente.

Ruta
/

Método
GET

Estado de la API

Permite verificar que el servidor de la API está activo y funcionando correctamente.

Ruta
/api/health

Método
GET

Ping del servidor

Este endpoint permite comprobar la conectividad con el servidor y verificar la respuesta rápida del sistema.

Ruta
/api/health/ping

Método
GET

Listado de artesanos

Permite consultar la lista de artesanos registrados en la API.

Ruta
/api/artesanos

Método
GET

Consultar artesano por ID

Permite obtener la información de un artesano específico mediante su identificador.

Ruta
/api/artesanos/{id}

Método
GET

Registrar un nuevo artesano

Permite agregar un nuevo artesano al sistema enviando la información en formato JSON.

Ruta
/api/artesanos

Método
POST

## Manejo de Errores

La API incluye manejo básico de errores para mejorar la experiencia del usuario y facilitar la identificación de problemas.

Error 404
Indica que el recurso solicitado no fue encontrado.

Error 405
Indica que el método HTTP utilizado no está permitido.

Error 500
Indica que ocurrió un error interno en el servidor.

## Pruebas de la API

Las pruebas de la API se realizaron utilizando el navegador web y herramientas de prueba de servicios REST como Postman.

Cada endpoint fue probado para verificar que devuelve la información correcta en formato JSON y que responde adecuadamente ante errores.

## Resultados

Se logró desarrollar una API funcional utilizando Flask que permite consultar información de la comunidad y gestionar registros de artesanos.

El proyecto demuestra la implementación de una arquitectura basada en APIs, así como el uso de buenas prácticas en la organización del código.

Además, el sistema puede ampliarse fácilmente agregando nuevos endpoints o integrando bases de datos en el futuro.

## Conclusión

El desarrollo de esta API permitió comprender el funcionamiento de los servicios web y la importancia de las APIs en la comunicación entre sistemas.

La utilización de Flask facilitó la creación de endpoints que permiten compartir información entre aplicaciones de manera sencilla y eficiente.

Este tipo de arquitectura es ampliamente utilizada en aplicaciones modernas, permitiendo construir sistemas escalables y flexibles.


