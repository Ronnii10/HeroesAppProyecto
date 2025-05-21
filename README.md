# HeroesApp

Este proyecto fue generado con [Angular CLI](https://github.com/angular/angular-cli) versión 16.2.11.

## Descripción

HeroesApp es una aplicación desarrollada en Angular que utiliza JSON Server como backend simulado para la gestión de datos. Esta guía explica cómo levantar el frontend y el backend localmente para pruebas o desarrollo.

## Requisitos previos

- Node.js
- Angular CLI (`npm install -g @angular/cli`)
- JSON Server (`npm install -g json-server`)
- Visual Studio Code (opcional, pero recomendado)
- Postman (opcional para probar el backend)

## Servidor de desarrollo

Ejecuta `ng serve` para iniciar un servidor de desarrollo. Navega a `http://localhost:4200/`. La aplicación se recargará automáticamente si cambias alguno de los archivos fuente.

## Generación de código

Ejecuta `ng generate component nombre-del-componente` para generar un nuevo componente. También puedes usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Compilación

Ejecuta `ng build` para compilar el proyecto. Los archivos de compilación se almacenarán en el directorio `dist/`.

## Ejecución de pruebas unitarias

Ejecuta `ng test` para ejecutar las pruebas unitarias mediante [Karma](https://karma-runner.github.io).

## Ejecución de pruebas end-to-end

Ejecuta `ng e2e` para ejecutar las pruebas end-to-end mediante una plataforma de tu elección. Para usar este comando, primero necesitas agregar un paquete que implemente las capacidades de pruebas end-to-end.

## Más ayuda

Para obtener más ayuda sobre Angular CLI, ejecuta `ng help` o consulta la [documentación oficial de Angular CLI](https://angular.io/cli).

## Instucciones

1. Abre Visual Studio Code en la carpeta del proyecto.
2. En la terminal integrada, ejecuta:

ng serve -o

3. Abre PowerShell y, si aún no lo has hecho, instala JSON Server globalmente:

npm install -g json-server

4. Navega a la carpeta donde está el archivo `db.json`:

cd ruta\a\tu\carpeta\del\proyecto\heroes-server

5. Ejecuta el servidor JSON:

json-server --watch db.json

6. Abre Postman y prueba con la siguiente URL:

http://localhost:3000/heroes
