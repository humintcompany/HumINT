# Favicon de Tierra negra para HumINT

Icono negro con fondo transparente y continentes recortados. La silueta simplificada conserva legibilidad a 16 y 32 px.

## Archivos

- favicon.svg: versión vectorial, con un pequeño margen transparente y relleno negro explícito.
- favicon.ico: contiene tamaños de 16, 32, 48, 64 y 256 px.
- earth-black-512.png: imagen PNG transparente de 512 × 512 px.
- Otros PNG: 16, 32, 48, 64, 180, 192 y 1024 px.

## Integración

Copia los recursos necesarios a la carpeta pública de HumINT y sustituye la configuración del favicon existente. Utiliza el mecanismo de metadatos que ya tenga el proyecto para evitar iconos duplicados.

En un proyecto que configure los iconos directamente en HTML:

```html
<link rel="icon" href="/favicon.svg" type="image/svg+xml" sizes="any">
<link rel="icon" href="/favicon.ico">
<link rel="apple-touch-icon" href="/earth-black-180.png" sizes="180x180">
```

El icono solicitado es negro y conserva la transparencia; no incorpora una versión blanca para pestañas oscuras.

## Procedencia y atribución

Basado en Earth Americas, Font Awesome Free 6.7.2, por Fonticons, Inc. Copyright 2024 Fonticons, Inc.

Fuente: https://github.com/FortAwesome/Font-Awesome/blob/6.7.2/svgs/solid/earth-americas.svg

Icono bajo licencia Creative Commons Attribution 4.0: https://creativecommons.org/licenses/by/4.0/

Se incluyen el SVG de origen y LICENSE-FONT-AWESOME.txt. Adaptaciones: relleno negro explícito, margen exterior, título accesible y exportaciones PNG/ICO. Se mantiene el trazado del icono original.

Conserva esta atribución y los textos de licencia al incorporar los recursos al proyecto.
