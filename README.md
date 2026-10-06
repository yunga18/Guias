# Ánima · El taller de autómatas

Nueva web en español dedicada a figuras articuladas de madera. Sustituye por completo a Retazos. Incluye seis guías originales: perro juguetón, pájaro curioso, gato y mariposa, ballena, mariposa articulada y percusionista.

- Diez pasos ilustrados por proyecto, despiece, herramientas y comprobaciones.
- Figuras vectoriales originales, animación conceptual con control de manivela y tres mecanismos interactivos.
- Búsqueda, filtro de dificultad, favoritos y avance guardados en el navegador.
- Botón para imprimir la guía o guardarla como PDF desde el diálogo de impresión.
- Diseño móvil, navegación por teclado y enlaces directos a cada guía.

## Alcance de las guías

Son propuestas de diseño y montaje que requieren prototipo. No son planos de fabricación ensayados. Las ilustraciones no están a escala. Las animaciones son cinemáticas explicativas; no simulan colisiones ni fuerzas. Se especifica qué partes se mueven y cuáles son decorativas. El texto recomienda prueba previa de pivotes en cartón, mecanismo en seco y acceso desmontable para ajustes.

El mecanismo común utiliza un marco de 220 × 120 × 132 mm, eje de 6 mm, levas de radio 25 mm con excentricidad 4 mm y seguidores planos con dos guías. Los discos deben cortarse por su periferia: no se recomienda una corona con broca central porque el agujero central se solaparía con el excéntrico.

Referencias conceptuales: Cabaret Mechanical Theatre, Exploratorium y Rob Ives. Los creadores enlazados no han validado estos diseños. No se reproducen sus planos ni imágenes.

## Publicación

En GitHub: **Settings → Pages → Deploy from a branch → main → / (root) → Save**. URL prevista: https://yunga18.github.io/Guias/. Si Pages fue despublicado, hay que volver a habilitarlo. No necesita backend, base de datos ni dependencias de compilación.

## Archivos

- `index.html`: estructura.
- `style.css`: estilos y formato de impresión.
- `projects.js`: materiales y guías.
- `drawings.js`: figuras y diagramas SVG originales.
- `app.js`: interacciones y persistencia local.
- `.nojekyll`: publicación estática.

Para previsualizar localmente abre `index.html`. Las fuentes externas tienen alternativas locales. Los datos se guardan bajo `anima-saved` y `anima-progress`; no se sincronizan ni migran desde el antiguo Retazos.
