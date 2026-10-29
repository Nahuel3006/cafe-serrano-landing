# Café Serrano – Café de especialidad en San Luis

Trabajo práctico de las Clases 1, 2 y 3 de JavaScript · Diplomatura en Desarrollo Fullstack con React, NodeJS y Herramientas de IA.

## Descripción

Página de una sola vista (`index.html`) con navbar, sección hero, carta de productos y footer.
Incluye un offcanvas para "Tu pedido", un carrusel de imágenes en el hero, un menú desplegable
y dos modales con formularios (Reserva y Contacto) validados con JavaScript.

## Tecnologías

- HTML5
- CSS3 (variables, Flexbox, media queries)
- Bootstrap 5.3.8 (CDN)
- JavaScript (validación de formularios, sin librerías externas)
- SVG locales e imágenes de Unsplash

## Estructura

```text
├── index.html
├── css/
│   ├── estilos.css
│   └── estilos-rotos.css
└── img/
    ├── taza.svg
    └── dulce.svg
```

## Cómo ejecutarlo

No requiere instalación ni compilación:

1. Abrir la carpeta en VS Code.
2. Instalar la extensión **Live Server**.
3. Clic derecho en `index.html` → **Open with Live Server**.

También se puede abrir con doble clic, pero hace falta conexión a internet para cargar
Bootstrap desde el CDN y las fotos del carrusel.

## Notas

- `css/estilos-rotos.css` conserva el nombre original del ejercicio, pero su contenido es la
  **versión corregida**: arregla el typo `.hero-titlo`, el `border-radius: 0` y el color inválido `#2B1D14e`.
- Los formularios usan las clases `needs-validation` y `novalidate` de Bootstrap; la validación
  se aplica con un script al final del `index.html`.

## Autor

Nahuel Solveira
