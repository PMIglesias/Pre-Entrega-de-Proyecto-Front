# E-commerce Básico

## Propósito
Este proyecto es una página web de e-commerce diseñada para ser simple y accesible, dirigida a usuarios adultos con baja visibilidad. Incluye páginas separadas para Inicio, Productos, Contacto e Iniciar Sesión, con un diseño responsivo, un formulario de contacto funcional con Formspree, un carrusel de reseñas con valoraciones y una barra de búsqueda en la página principal.

## Estructura del Proyecto
- `index.html`: Página principal con barra de búsqueda, productos destacados y carrusel de reseñas.
- `products.html`: Página con todos los productos en tarjetas.
- `contact.html`: Página con formulario de contacto.
- `login.html`: Página con formulario de inicio de sesión.
- `styles.css`: Estilos aplicados para diseño responsivo y accesibilidad.
- `assets/`: Carpeta con imágenes y videos utilizados.
- `README.md`: Este archivo.

## Instalación
1. Clona el repositorio: `git clone <URL_DEL_REPOSITORIO>`
2. Asegúrate de tener una conexión a internet para cargar Google Fonts y Formspree.
3. Reemplaza `YOUR_FORM_ID` en el formulario de `contact.html` con tu ID de Formspree.
4. Coloca tus imágenes y videos en la carpeta `assets/`.
5. Abre `index.html` en un navegador.

## Características
- **Estructura semántica**: Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` en todas las páginas.
- **Formulario de contacto**: Integrado con Formspree en `contact.html`.
- **Diseño responsivo**: Flexbox para productos, carrusel para reseñas, y Media Queries para formularios.
- **Accesibilidad**: Fuentes grandes, alto contraste, ARIA attributes y navegación por teclado.
- **Multimedia**: Incluye imágenes, un video promocional y un carrusel de reseñas con estrellas.
- **Barra de búsqueda**: En la página principal (no funcional sin backend).
- **Inicio de sesión**: Página con formulario básico de login.
- **Navegación**: Incluye enlace a "Iniciar Sesión" en el navbar.

## Tecnologías
- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (para el carrusel de reseñas)
- Google Fonts
- Formspree

## Notas
- Asegúrate de reemplazar los archivos multimedia en `assets/` con contenido real.
- Para pruebas locales, usa un servidor como `Live Server` en VS Code.
- La barra de búsqueda y el formulario de login son estáticos; requieren un backend para funcionalidad completa.
- El carrusel de reseñas usa JavaScript simple; considera bibliotecas como Swiper.js para más opciones.