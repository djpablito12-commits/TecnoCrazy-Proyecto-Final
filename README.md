# TecnoCrazy — Proyecto Final

**Proyecto Final del curso de Desarrollo Web de Coderhouse**

**Autor:** Pablo Cepeda
**Ubicación:** Santa Fe, Argentina
**Año:** 2026

## Descripción

TecnoCrazy es un sitio web dedicado a la tecnología, los accesorios para celulares, la reparación de dispositivos electrónicos y el desarrollo web.

El proyecto integra los conocimientos adquiridos durante el curso de Desarrollo Web de Coderhouse mediante la creación de un sitio estático de cinco páginas, con diseño responsivo, HTML semántico, Bootstrap, SCSS, animaciones y optimización SEO.

## Tecnologías utilizadas

* HTML5 y CSS3.
* SCSS / Sass.
* Bootstrap 5.
* AOS (Animate On Scroll).
* Flexbox y CSS Grid.
* Google Fonts.
* Git y GitHub.

Se utilizan los scripts necesarios para el funcionamiento de Bootstrap y AOS, sin desarrollar funcionalidades propias con JavaScript.

## Estructura del proyecto

```text
Teznocrazy_final/
├── index.html
├── pages/
│   ├── productos.html
│   ├── proyectos.html
│   ├── contacto.html
│   └── sobremi.html
├── assets/
├── scss/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── utilities/
│   └── main.scss
├── styles/
│   ├── style.css
│   └── style.css.map
├── robots.txt
├── sitemap.xml
└── README.md
```

## Páginas del sitio

### Inicio — index.html

Presenta la identidad de TecnoCrazy, su logo, una barra de navegación responsiva, un carrusel de Bootstrap y secciones dedicadas a accesorios, repuestos, herramientas y desarrollo web.

### Productos — productos.html

Muestra productos tecnológicos mediante tarjetas con imágenes, descripciones y precios. Incorpora Flexbox, transiciones y efectos visuales.

### Proyectos — proyectos.html

Presenta proyectos y servicios relacionados con el desarrollo de páginas web, las soluciones digitales y la reparación tecnológica.

### Sobre mí — sobremi.html

Incluye la presentación de Pablo Cepeda, su formación en programación, su experiencia en reparación de dispositivos electrónicos y su interés por el desarrollo web.

### Contacto — contacto.html

Permite comunicarse con TecnoCrazy mediante un enlace de correo electrónico y los datos de contacto disponibles en el sitio.

El botón de correo abre la aplicación de correo configurada en el dispositivo del visitante. El sitio no utiliza un servidor para procesar formularios.

## Bootstrap y diseño responsivo

Se utiliza Bootstrap 5 para implementar componentes como la barra de navegación adaptable, el menú hamburguesa y el carrusel de imágenes.

Los estilos personalizados incorporan Flexbox, Grid y media queries para adaptar el contenido a computadoras, tablets y celulares.

## SCSS y organización de estilos

El proyecto organiza los estilos en archivos parciales agrupados por función.

Se utilizan variables, nesting, mixins con parámetros, `@extend`, transiciones, transformaciones, efectos hover, animaciones y media queries.

El archivo `scss/main.scss` reúne los módulos mediante `@use`.

Para compilar los estilos, ejecutar desde la carpeta principal:

```bash
npx sass scss/main.scss styles/style.css
```

## Animaciones

El sitio incorpora animaciones propias mediante CSS y SCSS, utilizando `@keyframes`, `transition`, `transform` y efectos hover.

También utiliza la biblioteca AOS para animar elementos cuando aparecen durante el desplazamiento de la página.

## Identidad visual

La paleta de TecnoCrazy está compuesta por:

* Azul principal: `#1F66FF`
* Gris oscuro: `#262626`
* Fondo claro: `#F2F2F2`
* Texto: `#333333`
* Blanco: `#FFFFFF`

La tipografía principal es Poppins, obtenida mediante Google Fonts.

## SEO

El proyecto incorpora títulos y metadescripciones específicos para cada página, palabras clave, encabezados semánticos y atributos `alt` en las imágenes.

También incluye los archivos `robots.txt` y `sitemap.xml`.

**Pendiente de publicación:** actualizar el sitemap y robots.txt con las URL definitivas e incorporar enlaces canonical absolutos una vez que el sitio esté desplegado.

## Cómo ejecutar el proyecto

1. Clonar o descargar el repositorio.
2. Abrir la carpeta del proyecto en Visual Studio Code.
3. Abrir `index.html` mediante Live Server.
4. Navegar por las cinco páginas para explorar el sitio.

## Repositorio

[Ver el código fuente en GitHub](https://github.com/djpablito12-commits/TecnoCrazy-Proyecto-Final)

## Sitio publicado

**Pendiente:** incorporar aquí la URL de Vercel o Netlify una vez finalizada la publicación.

---

**Pablo Cepeda — Proyecto Final de Desarrollo Web, Coderhouse, 2026.**
