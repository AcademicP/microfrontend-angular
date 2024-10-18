# AngularCW

Esta aplicación forma parte del ecosistema de **microfrontends** gestionados por **Single-SPA**. El objetivo es proporcionar un sistema de **monitoreo IoT** que se carga de manera modular como un microfrontend Angular en un **modal flotante**.

## Requisitos Previos

- **Node.js**: Asegúrate de tener instalada la versión 16:
  nvm install 16

- **Angular CLI**: Si no tienes Angular CLI instalado, puedes hacerlo con:
  npm install -g @angular/cli

## Iniciar el Servidor de Desarrollo

Ejecuta el siguiente comando para iniciar un **servidor de desarrollo**:

  ng serve --port 5005

Accede en tu navegador a: http://localhost:5005/

La aplicación se **recargará automáticamente** si cambias alguno de los archivos fuente.

## Integración con Single-SPA

Para ejecutar esta aplicación dentro del ecosistema **Single-SPA**, usa:

  npm run serve:single-spa:angular-cw

Esto levantará la aplicación como un **microfrontend** listo para cargar en el layout de **Single-SPA**.

## Generación de Código

Para generar un nuevo componente:

  ng generate component component-name

También puedes generar otros elementos con:

  ng generate directive|pipe|service|class|guard|interface|enum|module

## Compilación del Proyecto

Para **compilar la aplicación**:

  ng build

Los archivos compilados se almacenarán en el directorio `dist/`.

Para generar una compilación de **producción**, usa:

  ng build --prod



O visita la documentación oficial de Angular CLI en https://angular.io/cli.

## Propósito del Proyecto

Este microfrontend Angular forma parte de un sistema más amplio destinado a **monitorear el crecimiento de hijuelos de plátano** mediante tecnología IoT. El proyecto se integra como una **aplicación modular** que se carga en un **modal flotante** usando **Single-SPA**.

## Conclusión

Este **README** proporciona toda la información necesaria para desarrollar, ejecutar y mantener este microfrontend Angular como parte del ecosistema **Single-SPA**.
