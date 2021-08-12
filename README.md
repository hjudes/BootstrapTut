<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://getbootstrap.com/docs/5.1/assets/brand/bootstrap-logo-shadow.png" alt="Bootstrap logo" width="200" height="165">
  </a>
</p>

<h1 align="center">Bootstrap</h1>

# BootstrapTut
Sesión Bootstrap Diplomado SENA
Resumen de los pasos ejecutados en la sesión de Bootstrap realizada.
<br>
La presente guía será basada en la versión 5 de Bootstrap
<br>

## Contenido

- [Requerimientos técnicos](#requerimientos)
- [Instalación](#instalación)
- [Estructura de carpetas](#estructura-de-carpetas)
- [Importar JavaScript](#Importar JavaScript)
- [Copyright y licencia](#copyright-y-licencia)

## Requerimientos técnicos

Herramientas requeridas: Visual Studio Code, Node.js, cualquier navegador.

- Instalar Visual Studio Code: [Página oficial](https://code.visualstudio.com/Download)
- Instalar Node.js: [Página oficial](https://nodejs.org/en/)

Se utilizará la documentación [Getting started page](https://getbootstrap.com/docs/5.1/getting-started/introduction/) para referencia en cuanto al proceso de instalación, contenido del framework, plantillas, ejemplos y más.

La guía considerará los resultados obtenidos con Bootstrap v.5.1, Visual Studio Code v.1.59.0 y Node.js v.14.16.0 o 14.17.5.

## Instalación

Una vez instalados los componentes de Visual Studio Code y Node.js deberá ser creada la carpeta que se utilizará para almacenar los archivos.

Utilizaremos Parcel para incluir Bootstrap en el proyecto.

- Instalar Parcel Bundler
Instalar con [npm](https://www.npmjs.com/): `npm install -g parcel-bundler`

- Instalar Bootstrap
`npm install bootstrap`

- Crear el archivo package.json en el directorio usando
`npm init -y`

- Instalar Popper
`npm install @popperjs/core`

## Estructura de carpetas

Para iniciar, la estructura que se deberá tener es la siguiente:
```text
nombre-proyecto/
├── node_modules/
│   └── bootstrap/
│   └── popper.js/
└── scss/
│   ├── custom.scss
├── src/
│   ├── index.html
│   ├── index.js
│  
└── package.json
```
Crear archivos y carpetas correspondientes para finalizar esta parte del proceso.

## Importar JavaScript

Para la importación del JavaScript de Bootstrap en el punto de entrada (src/index.js) indicar la siguiente instrucción:
`import * as bootstrap from 'bootstrap';`

## Copyright y licencia

Bootstrap originado en [Twitter, Inc.](https://twitter.com) Código liberado bajo la licencia MIT. Documentos liberados bajo [Creative Commons](https://creativecommons.org/licenses/by/3.0/).
