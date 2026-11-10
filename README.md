# Portafolio profesional de Luis Carranza

Sitio web personal de **Luis Carranza**, Ingeniero Electrónico egresado de la Universidad del Valle de Guatemala (UVG).

🌐 **Sitio web:** https://luiscarranza18.github.io

## Contenido del sitio

- **Sobre mí:** presentación y trayectoria profesional.
- **Proyectos:** tarjetas con una página de detalle para cada proyecto, con galería de fotos, rol, resultados y especificaciones.
- **Habilidades:** herramientas y competencias técnicas.
- **Contacto:** correo electrónico y perfiles profesionales.

## Tecnologías

Sitio estático hecho solo con **HTML, CSS y JavaScript**, sin frameworks ni dependencias. Las tipografías (Bricolage Grotesque e IBM Plex Sans) se cargan desde Google Fonts. Se publica con **GitHub Pages**.

## Estructura del repositorio

```
.
├── index.html     # Todo el sitio (estructura, estilos y lista de proyectos)
├── img/           # Fotografías de perfil y de los proyectos
├── docs/          # PDFs (esquemáticos, informes), si se necesitan
└── README.md
```

## Cómo editar el sitio

- **Textos:** se modifican directamente en `index.html`.
- **Colores:** se cambian en las variables CSS al inicio de `index.html` (bloque `:root`).
- **Proyectos:** se editan en la lista `projects`, dentro de la etiqueta `<script>` al final del archivo. Para agregar uno, se copia un bloque `{ ... }` y se cambian sus datos. El campo `id` debe ser una sola palabra en minúsculas, sin espacios ni tildes.
- **Fotos:** se guardan en `img/` y se referencian por nombre en el campo `photos` de cada proyecto. 

## Ver el sitio en local

Basta con abrir `index.html` en el navegador. No requiere instalación.

## Publicación

El sitio se publica automáticamente con GitHub Pages desde la rama principal del repositorio (`Settings → Pages`). Los cambios pueden tardar un par de minutos en reflejarse.

## Derechos de autor

© 2026 Luis Carranza. Todos los derechos reservados.

El código, los textos, las imágenes y demás contenido de este repositorio no pueden copiarse, modificarse ni distribuirse sin autorización expresa del autor.

## Contacto

- Correo: lpcarranza@uvg.edu.gt
- LinkedIn: https://linkedin.com/in/luis-carranza-41689b296
