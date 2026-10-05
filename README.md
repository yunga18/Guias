# Retazos · Tu pequeño taller

Guías artesanales en español para aprovechar retazos de madera con una sierra de mano y un taladro. Incluye 16 proyectos ilustrados, búsqueda, categorías, favoritos y avance por pasos.

## Publicar en GitHub Pages

1. En este repositorio abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige **main** y **/ (root)**, y pulsa **Save**.
4. Cuando GitHub termine el despliegue, la dirección prevista es https://yunga18.github.io/Guias/.

No hace falta instalar paquetes ni contratar una base de datos. GitHub Pages debe estar habilitado en el repositorio para que la dirección funcione.

## Archivos

- `index.html`: estructura de la página.
- `style.css`: diseño adaptable a móvil.
- `app.js`: contenido de las 16 guías y comportamiento.
- `illustrations.js`: ilustraciones vectoriales de las nuevas guías y contenido detallado de los vehículos con movimiento.
- `.nojekyll`: permite servir estos archivos estáticos directamente.

Abre `index.html` en un navegador para probar la página. Se pueden editar las guías en la lista `projects` de `app.js`; los dos vehículos con movimiento están en `rollingProjects` de `illustrations.js`. Las imágenes son SVG incluidas en el código; no dependen de un servicio de imágenes. Las fuentes de Google son opcionales: si no cargan, se usan las fuentes del sistema.

## Tus datos

Favoritos y avances se guardan en el navegador mediante localStorage. No se sincronizan entre dispositivos. El avance del antiguo carrito decorativo no se cuenta como completado en las nuevas guías con mecanismo; sus favoritos se conservan. Los guardados del sitio anterior no se transfieren automáticamente al cambiar de dominio. No hay cuentas, suscripciones ni servicios de base de datos integrados.

## Proyectos y materiales

El carrito y la furgoneta incluyen 8 pasos cada uno, ruedas reales cortadas con sierra de copa y montaje con tornillos y arandelas. Las dimensiones son una propuesta de diseño no ensayada físicamente: el usuario debe verificar la combinación corona/agujero/tornillo, la longitud de inserción y la holgura de giro. Son modelos de empuje, sin motor ni dirección. Los llaveros necesitan una argolla y los colgantes un cordón; cada guía lo indica. Todos los cortes y perforaciones necesitan una sujeción segura, protección ocular y retirada de astillas antes del uso. Las ilustraciones son explicativas, no planos a escala.
