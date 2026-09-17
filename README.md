# TecnoCrazy 🚀💻

## Proyecto Final — Desarrollo Web

TecnoCrazy es un sitio web desarrollado como Proyecto Final para el curso de Desarrollo Web de Coderhouse.

El proyecto representa un emprendimiento tecnológico enfocado en la reparación de dispositivos electrónicos, venta de accesorios para celulares y desarrollo de soluciones digitales.

El objetivo es combinar tecnología, diseño y funcionalidad aplicando los conocimientos adquiridos durante el curso mediante HTML5, SCSS/SASS, Bootstrap, diseño responsive, animaciones y optimización SEO.

---

# Tecnologías utilizadas

- HTML5
- SCSS / SASS
- CSS3
- Bootstrap 5
- JavaScript
- AOS (Animate On Scroll)
- Flexbox
- CSS Grid
- Google Fonts
- Git
- GitHub
- Diseño responsive
- SEO

---

# Estructura del proyecto

```text
TecnoCrazy/
│
├── index.html
│
├── pages/
│   ├── productos.html
│   ├── proyectos.html
│   ├── contacto.html
│   └── sobremi.html
│
├── scss/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── utilities/
│   └── main.scss
│
├── styles/
│   ├── style.css
│   └── style.css.map
│
├── assets/
│
├── robots.txt
├── sitemap.xml
└── README.md
```

El proyecto cuenta con `index.html` en la raíz y cuatro páginas adicionales dentro de la carpeta `pages/`, respetando la estructura solicitada para el Proyecto Final.

Todos los recursos multimedia se encuentran organizados dentro de la carpeta `assets/`.

Los archivos fuente de estilos se encuentran en `scss/` y el CSS compilado se encuentra en `styles/`.

---

# Páginas del proyecto

## Inicio — index.html

La página principal presenta la identidad y los principales servicios de TecnoCrazy.

Elementos implementados:

- Navbar responsive de Bootstrap.
- Menú hamburguesa para dispositivos móviles.
- Logo e identidad visual de TecnoCrazy.
- Banner principal.
- Presentación general del emprendimiento.
- Carrusel de imágenes mediante Bootstrap.
- Sección de accesorios para celulares.
- Sección de repuestos y herramientas.
- Sección de programación y desarrollo web.
- Animaciones y efectos visuales.
- Footer personalizado.
- Accesos directos a las diferentes páginas.
- Accesos a redes sociales.

---

## Productos — productos.html

Esta sección presenta productos y accesorios relacionados con tecnología.

Elementos implementados:

- Tarjetas de productos.
- Imágenes descriptivas.
- Nombre y precio de los productos.
- Organización responsive del contenido.
- Flexbox y CSS Grid.
- Efectos hover.
- Transiciones.
- Diseño adaptable a diferentes dispositivos.

---

## Proyectos — proyectos.html

En esta página se presentan proyectos y servicios relacionados con TecnoCrazy.

Incluye contenido relacionado con:

- Desarrollo de páginas web.
- Soluciones digitales.
- Reparación tecnológica.
- Servicios relacionados con tecnología.

Se aplicaron estilos personalizados, componentes responsive y animaciones para mejorar la presentación del contenido.

---

## Sobre mí — sobremi.html

Esta sección presenta información sobre el desarrollador del proyecto.

Incluye:

- Presentación de Pablo Cepeda.
- Formación relacionada con programación.
- Interés por la tecnología.
- Experiencia relacionada con reparación de dispositivos.
- Desarrollo web y soluciones digitales.

---

## Contacto — contacto.html

Página destinada a facilitar la comunicación con los usuarios.

Elementos implementados:

- Formulario de contacto.
- Campos para completar datos.
- Botones personalizados.
- Información de contacto.
- Diseño responsive.
- Componentes estilizados mediante SCSS y Bootstrap.

---

# HTML semántico

Los cinco archivos HTML utilizan etiquetas semánticas para organizar correctamente el contenido.

Entre las etiquetas utilizadas se encuentran:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<footer>`

La estructura del código mantiene una jerarquía organizada para facilitar la lectura y el mantenimiento del proyecto.

---

# SCSS y organización de estilos

Los estilos del proyecto fueron desarrollados utilizando SCSS/SASS.

El código fue dividido mediante partials para mantener una arquitectura organizada y facilitar el mantenimiento.

La estructura SCSS se divide principalmente en:

```text
scss/
├── base/
├── components/
├── layout/
├── utilities/
└── main.scss
```

Durante el desarrollo se utilizaron:

- Variables.
- Nesting.
- Mixins.
- Mixins con parámetros.
- `@extend`.
- Partials.
- `@use`.
- Transformaciones.
- Transiciones.
- Animaciones.
- Efectos hover.
- Sombras.
- Media queries.

El archivo `main.scss` se utiliza exclusivamente para cargar los diferentes partials mediante `@use`.

El resultado de la compilación se encuentra dentro de:

```text
styles/style.css
```

---

# Diseño responsive

TecnoCrazy fue desarrollado para adaptarse a diferentes tamaños de pantalla.

Se trabajó específicamente para:

- Mobile.
- Tablet.
- Desktop.

Para lograrlo se utilizaron:

- Media queries.
- Flexbox.
- CSS Grid.
- Componentes responsive de Bootstrap.
- Navbar adaptable.
- Menú hamburguesa.
- Imágenes adaptables.
- Tarjetas flexibles.
- Ajustes de tipografía.
- Ajustes de márgenes y espacios.

La responsividad fue aplicada a las cinco páginas:

- `index.html`
- `productos.html`
- `proyectos.html`
- `contacto.html`
- `sobremi.html`

El objetivo fue evitar scroll horizontal, superposición de elementos y deformación del contenido en diferentes dispositivos.

---

# Bootstrap

Bootstrap 5 fue utilizado para complementar el desarrollo del sitio.

Entre los recursos implementados se encuentran:

- Navbar responsive.
- Menú hamburguesa.
- Carrusel de imágenes.
- Sistema de grillas.
- Contenedores.
- Clases utilitarias.
- Botones.
- Componentes responsive.

La navbar está presente en las diferentes páginas del proyecto y fue personalizada mediante SCSS para mantener la identidad visual de TecnoCrazy.

---

# Animaciones

El proyecto incorpora animaciones nativas realizadas mediante CSS/SCSS.

Se utilizaron recursos como:

- `transition`
- `transform`
- `@keyframes`
- Efectos `hover`
- Animaciones de entrada

Las animaciones se aplicaron de manera moderada para mejorar la interacción sin afectar la navegación.

---

# Librería de animaciones — AOS

El proyecto incorpora la librería AOS (Animate On Scroll).

AOS permite ejecutar animaciones cuando determinados elementos aparecen durante el desplazamiento de la página.

Esta librería se combina con las animaciones propias desarrolladas mediante SCSS para mejorar la experiencia visual del sitio.

---

# Footer interactivo

El proyecto cuenta con un footer personalizado con la identidad visual de TecnoCrazy.

El footer incluye accesos directos a:

- Inicio.
- Sobre mí.
- Productos/Servicios.
- Proyectos.
- Contacto.

También incorpora accesos a redes sociales y medios de comunicación.

Los enlaces permiten navegar directamente entre las diferentes secciones del sitio.

El footer fue adaptado para visualizarse correctamente en diferentes tamaños de pantalla.

---

# SEO

El proyecto incorpora optimizaciones básicas de SEO y accesibilidad.

Cada página cuenta con elementos orientados a mejorar su identificación y posicionamiento:

- `<title>` descriptivo.
- Meta description.
- Meta keywords.
- Atributos `alt` en las imágenes.
- Jerarquía de encabezados.
- HTML semántico.
- Enlaces internos.
- Nombres descriptivos en archivos multimedia.
- Archivo `robots.txt`.
- Archivo `sitemap.xml`.
- Etiquetas canonical.

El contenido está orientado a TecnoCrazy y a sus servicios tecnológicos.

---

# Identidad visual

La identidad visual de TecnoCrazy utiliza principalmente tonos azules, negros, grises y blancos.

Paleta principal:

- Azul principal: `#1F66FF`
- Negro/gris oscuro: `#262626`
- Fondo claro: `#F2F2F2`
- Texto: `#333333`
- Blanco: `#FFFFFF`

También se utilizaron:

- Sombras.
- Bordes.
- Transformaciones.
- Animaciones.
- Efectos hover.
- Transiciones.
- Imágenes tecnológicas.
- Componentes personalizados.

---

# Funcionalidades

El sitio cuenta con:

- Navegación entre cinco páginas.
- Navbar responsive.
- Menú hamburguesa.
- Carrusel Bootstrap.
- Visualización de productos.
- Presentación de servicios.
- Formulario de contacto.
- Presentación del desarrollador.
- Animaciones SCSS.
- Animaciones mediante AOS.
- Footer interactivo.
- Accesos directos entre páginas.
- Enlaces a redes sociales.
- Diseño responsive.
- Optimización SEO.

---

# Objetivo del Proyecto Final

El Proyecto Final de TecnoCrazy integra los contenidos desarrollados durante el curso de Desarrollo Web.

Los principales objetivos fueron:

- Desarrollar cinco páginas HTML.
- Utilizar HTML semántico.
- Implementar Bootstrap.
- Desarrollar una navbar responsive.
- Trabajar los estilos mediante SCSS.
- Organizar SCSS mediante partials.
- Implementar variables.
- Utilizar nesting.
- Crear mixins con parámetros.
- Aplicar `@extend`.
- Utilizar `@use`.
- Incorporar animaciones nativas.
- Incorporar la librería AOS.
- Desarrollar un sitio completamente responsive.
- Optimizar el SEO.
- Organizar correctamente los recursos multimedia.
- Utilizar Git y GitHub para control de versiones.
- Publicar el proyecto mediante Vercel o Netlify.

---

# Cómo visualizar el proyecto

Para visualizar TecnoCrazy localmente:

1. Clonar o descargar el repositorio.
2. Abrir la carpeta del proyecto.
3. Abrir el proyecto con Visual Studio Code.
4. Abrir `index.html`.
5. Se recomienda utilizar Live Server para visualizar el sitio durante el desarrollo.

---

# Sitio publicado

El Proyecto Final será desplegado públicamente mediante Vercel o Netlify.

**Link del sitio:** pendiente de publicación.

Cuando se realice el deploy definitivo, este enlace será actualizado con la URL pública del sitio.

---

# Repositorio GitHub

El código fuente del Proyecto Final se encuentra alojado en un repositorio público de GitHub.

**Link del repositorio:** pendiente de publicación.

El repositorio contiene el código HTML, la arquitectura SCSS, el CSS compilado, los recursos multimedia y la documentación del proyecto.

---

# Autor

**Pablo Cepeda**

Proyecto Final realizado para el curso de Desarrollo Web — Coderhouse.

**Año: 2026**