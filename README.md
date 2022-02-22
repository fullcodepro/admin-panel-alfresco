# Panel de Administración de ALFRESCO

## Descripción:

Este módulo de administración de Alfresco fue desarrollado utilizando consultas a la `REST API de Alfresco Content Services` con el fin de extender las funcionalidades del mismo permitiendo adaptarse a requirimientos específicos permitiendo la flexibilidad y despliegue de nuevas funcionalidades.

## Qué permite realizar el módulo provisto:

1. Navegar entre los diferentes nodos a patir de un nodo raíz.
2. Obtener información de un nodo específico de Alfresco acerca de sus propiedades.
3. Obtener un listado del contenido de un nodo.
4. Operaciones típicas de CRUD sobre un nodo.


>>> Puede acceder a la documentación oficial de API Explorer de Alfresco haciendo clic en el siguiente enlace:

[https://api-explorer.alfresco.com/api-explorer/](https://api-explorer.alfresco.com/api-explorer/)

## Instalación

Las siguientes dependencias son necesarias:

* Node.js
* node-fetch v2.6.2

Puedes descargar la versión oficial de `Node.js` directamente desde su sitio web oficial:

https://nodejs.org/en/download/

Una vez instalado Node.js:
1. Clonar este proyecto.
2. Ingresar al directorio generado.
3. Abrir un programa de línea de comandos y ejecutar los siguientes comandos:

``` bash
$ npm install
```

Al finalizar la insatlación de dependecias, puede poner en funcionamiento el prorama utilizando el siguiente comando:

``` bash
$ npm run dev
```


