# Stelarze Simon Hurtado

![N|Solid](assets/logos/logo-primary.svg)

Proyecto final para curso de desarrollo web realizado en CoderHouse. Con uso de HTML5, CSS3, SASS y Bootstrap.

## Descripción

Es un sitio web estatico sobre Stelarze S.R.L., con hosting de Firebase y responsive web design.

Cuenta con 5 secciones principales:
- Home
- Quienes Somos
- Servicios
- Empleos
- Contacto

Ademas cuenta con 3 secciones de aspectos legales:
- Politica de Cookies
- Politica de Privacidad
- Aviso Legal

## Visuales

Para este desarrollo se tuvo en cuenta las diferentes resoluciones que puede prensentar: mobile, tablet y desktop

![N|Solid](https://i.ibb.co/THSLXzv/banner-preview-rev-1.png)

Ademas se consideró el encabezado y pie de pagina del navegador en vista mobile para su diseño y pruebas de usabilidad.

## Instalación

Instalación del nodejs y el npm para poder editar los archivos .scss

> Iniciar el npm

```sh
npm init
```

> Instalar el nodemon

```sh
npm install -D node-sass nodemon.
```

Crear carpeta `SCSS` y `CSS` y sus archivos respectivos.

> Editar el package.json e insertar las lineas:

```sh
"build-css": "node-sass --include-path scss scss/style.scss css/style.css",
"watch-css": "nodemon -e scss -x \"npm     run build-css\"",
```

> Compilar con npm

```sh
npm run watch-css
```

## Hoja de ruta

Resumen de los commits realizados en el repositorio:

`Arreglos finales y salida a producción de la Entrega del Proyecto Final`
>Committed on 22 Jul 2022

`Modificaciones de SEO con documentacion y correcciones finales`
>Committed on 22 Jul 2022

`Modificación de las animaciones`
>Committed on 18 Jul 2022

`Modificaciones de diseño y estructura en el nav, encabezados y componentes`
>Committed on 17 Jul 2022

`Tercera entrega del proyecto final`
>Committed on 6 Jul 2022

`SASS II y SEO`
>Committed on 4 Jul 2022

`Segunda entrega del proyecto final`
>Committed on 22 Jun 2022

`Versión final con Bootstrap`
>Committed on 20 Jun 2022

`Animaciones y linea de tiempo`
>Committed on 17 Jun 2022

`Subida de archivos`
>Committed on 16 Jun 2022

## Autores y agradecimientos

Autor: Carlos Diego Simon Hurtado

Agradecimientos: 
A mis tutores(Martin Giando, Joaquin Viretti) por siempre corregirme, responder dudas, aconsejarme con el proyecto y a mi profesora Laura Avalle por todos los conocimientos aportados a los largo del curso para el desarrollo de este proyecto.

## Estado del proyecto

Finalizado

Entrega del Proyecto Final