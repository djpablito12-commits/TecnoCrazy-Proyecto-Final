# TecnoCrazy 🚀💻

## Descripción del proyecto

TecnoCrazy es un sitio web desarrollado como proyecto final para el curso de Desarrollo Web de Coderhouse.

El objetivo del proyecto es crear un sitio web para un emprendimiento tecnológico enfocado en la reparación de dispositivos electrónicos, venta de accesorios para celulares y desarrollo de soluciones digitales.

El proyecto busca combinar tecnología, diseño y funcionalidad, aplicando los conocimientos adquiridos durante el curso y utilizando HTML5, SCSS, Bootstrap y herramientas de desarrollo frontend.

---

# Tecnologías utilizadas

* HTML5
* SCSS / SASS
* CSS3
* Bootstrap 5
* JavaScript
* AOS (Animate On Scroll)
* Flexbox
* Google Fonts
* Diseño responsive
* Git
* GitHub

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
├── css/
│   └── style.css
│
├── assets/
│
├── robots.txt
├── sitemap.xml
└── README.md
```

---

# Páginas del proyecto

## Página principal — index.html

En la página de inicio se presenta la identidad de TecnoCrazy.

Elementos implementados:

* Barra de navegación responsive.
* Logo de TecnoCrazy.
* Presentación general del emprendimiento.
* Carrusel de imágenes mediante Bootstrap.
* Sección de accesorios para celulares.
* Sección de repuestos y herramientas.
* Sección dedicada a programación y desarrollo web.
* Animaciones y efectos visuales.
* Footer con información de contacto y redes sociales.

---

## Página Productos — productos.html

En esta sección se presentan diferentes productos relacionados con tecnología.

Elementos implementados:

* Tarjetas de productos.
* Imágenes descriptivas.
* Nombre y precio de los productos.
* Organización del contenido mediante Flexbox.
* Efectos hover y transiciones.
* Diseño adaptable a dispositivos móviles.

---

## Página Proyectos — proyectos.html

En esta página se presentan proyectos y servicios relacionados con:

* Desarrollo de páginas web.
* Soluciones digitales.
* Reparación tecnológica.
* Servicios relacionados con tecnología.

Se aplicaron estilos personalizados, animaciones y una estructura responsive para mejorar la presentación visual.

---

## Página Sobre mí — sobremi.html

Esta sección contiene información personal y profesional del desarrollador.

Incluye:

* Presentación de Pablo Cepeda.
* Formación en programación.
* Interés por la tecnología.
* Experiencia en reparación de dispositivos electrónicos.
* Información relacionada con el desarrollo web.

---

## Página Contacto — contacto.html

Página destinada a facilitar la comunicación con los usuarios.

Elementos implementados:

* Formulario de contacto.
* Campos para completar datos.
* Botones de envío.
* Información de contacto.
* Diseño responsive.

---

# SCSS y organización de estilos

Los estilos del proyecto fueron desarrollados utilizando SCSS/SASS.

El código se organizó mediante archivos parciales para mantener una estructura ordenada y facilitar el mantenimiento del proyecto.

Se aplicaron diferentes recursos de SCSS:

* Variables.
* Nesting.
* Mixins.
* Mixins con parámetros.
* `@extend`.
* Organización mediante partials.
* Transformaciones.
* Transiciones.
* Animaciones.
* Efectos hover.
* Sombras.
* Media queries.

El archivo `main.scss` funciona como archivo principal para importar los diferentes partials del proyecto.

---

# Animaciones

Se incorporaron animaciones para mejorar la experiencia visual y la interactividad del sitio.

Se utilizaron recursos de CSS/SCSS como:

* `transition`
* `transform`
* `@keyframes`
* Efectos `hover`
* Animaciones de entrada

Las animaciones fueron utilizadas de manera sutil para mantener una experiencia visual agradable sin afectar la navegación.

---

# Librería de animaciones — AOS

El proyecto incorpora la librería **AOS (Animate On Scroll)** para generar animaciones cuando determinados elementos aparecen durante el desplazamiento de la página.

La implementación de AOS permite incorporar efectos de entrada a diferentes elementos visuales del sitio.

El objetivo es mejorar la interacción y presentación del contenido manteniendo las animaciones de forma moderada.

---

# Diseño responsive

El sitio fue desarrollado para adaptarse a diferentes tamaños de pantalla.

Se trabajó principalmente con:

* Diseño desktop.
* Diseño mobile.
* Media queries.
* Flexbox.
* Componentes responsive de Bootstrap.
* Navbar adaptable.
* Organización flexible de tarjetas y secciones.
* Ajustes de tamaños, espacios y tipografías según el dispositivo.

La responsividad fue aplicada a las cinco páginas HTML del proyecto:

* `index.html`
* `productos.html`
* `proyectos.html`
* `contacto.html`
* `sobremi.html`

---

# Bootstrap implementado

Bootstrap 5 fue utilizado para complementar el desarrollo del sitio.

Se implementaron componentes y recursos como:

* Navbar responsive.
* Menú hamburguesa para dispositivos móviles.
* Carrusel de imágenes.
* Sistema de grillas.
* Clases utilitarias.
* Componentes responsive.

Los estilos personalizados mediante SCSS se combinaron con Bootstrap para adaptar el framework a la identidad visual de TecnoCrazy.

---

# Diseño y estilos

Para la identidad visual del proyecto se utilizó una estética tecnológica basada principalmente en tonos azules, negros, grises y blancos.

Paleta principal:

* Azul principal: `#1F66FF`
* Negro/gris oscuro: `#262626`
* Fondo claro: `#F2F2F2`
* Texto: `#333333`
* Blanco: `#FFFFFF`

Se aplicaron diferentes recursos visuales:

* Variables.
* Transiciones.
* Efectos hover.
* Sombras.
* Transformaciones.
* Animaciones.
* Diseño responsive.
* Componentes de Bootstrap.

---

# Funcionalidades

El sitio web cuenta con:

* Navegación entre las diferentes páginas.
* Visualización de productos y accesorios tecnológicos.
* Carrusel de imágenes.
* Formulario de contacto.
* Diseño adaptable a dispositivos móviles.
* Presentación de proyectos y servicios.
* Información sobre el desarrollador.
* Animaciones CSS/SCSS.
* Animaciones mediante AOS.
* Componentes responsive de Bootstrap.

---

# Objetivo de la tercera pre-entrega

Esta etapa del proyecto tuvo como objetivo finalizar el diseño del sitio y mejorar su funcionamiento en dispositivos desktop y mobile.

Los principales objetivos fueron:

* Finalizar la responsividad de las cinco páginas HTML.
* Incorporar animaciones locales.
* Implementar una librería de animaciones.
* Profundizar el uso de SCSS.
* Utilizar variables y nesting.
* Implementar mixins con parámetros.
* Aplicar `@extend`.
* Organizar los estilos mediante partials.
* Mantener una estructura HTML limpia y ordenada.
* Mejorar la experiencia visual e interacción del usuario.

---

# Cómo visualizar el proyecto

Para visualizar el sitio web:

1. Clonar o descargar el repositorio.
2. Abrir la carpeta del proyecto.
3. Abrir el proyecto con Visual Studio Code.
4. Ejecutar `index.html` utilizando Live Server.

También es posible abrir directamente `index.html` en un navegador web, aunque se recomienda utilizar Live Server para una mejor experiencia de desarrollo.

---

# Repositorio

El proyecto se encuentra alojado en GitHub en un repositorio público.

Desde allí se puede acceder al código fuente, estructura de carpetas, archivos HTML, SCSS, CSS, imágenes y documentación del proyecto.

## SEO básico

El proyecto incorpora mejoras básicas de posicionamiento y accesibilidad:

* Etiquetas `title` específicas para cada página.
* Meta descriptions y meta keywords.
* Jerarquía semántica de encabezados con un `h1` visible por página.
* Enlaces canonical.
* Textos `alt` descriptivos en las imágenes.
* Nombres de archivos de imágenes más descriptivos.
* Archivo `robots.txt`.
* Archivo `sitemap.xml`.
* Referencias de contenido orientadas a TecnoCrazy y a Santa Fe, Argentina.

> Nota: si el sitio se publica en un dominio diferente al configurado en `sitemap.xml`, se debe actualizar allí la URL base de las páginas.

---

---

# Autor

**Pablo Cepeda**

Proyecto realizado para el curso de Desarrollo Web — Coderhouse.

**Año: 2026**
