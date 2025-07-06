# Galería de Artículos con Efecto Overlay - Portafolio HTML y CSS

## Descripción
Este trabajo es una página web estática que presenta una galería de artículos con imágenes y un efecto de "overlay" interactivo. Ha sido desarrollado como parte de mi portafolio como estudiante universitario para demostrar mis habilidades en HTML5 y CSS3, especialmente en el uso de posicionamiento avanzado (`position: absolute;`), transformaciones (`transform: translateX;`), transiciones (`transition: all;`) y `flexbox` para la disposición de elementos. Cada artículo contiene una imagen y una capa superpuesta (overlay) que aparece al pasar el ratón (`hover`), revelando un título y una descripción. El diseño es limpio y moderno, utilizando una fuente personalizada de Google Fonts. Está diseñado para ser alojado en GitHub Pages y sirve como una muestra de mi preparación para un primer empleo como desarrollador frontend.

## Objetivo
Como estudiante universitario, creé este trabajo para:

* Demostrar mis habilidades en HTML semántico y CSS avanzado, incluyendo el manejo de `position: absolute;` para superposiciones, `transform` y `transition` para animaciones suaves, y `flexbox` para el centrado de contenido.
* Mostrar mi capacidad para diseñar y construir componentes de interfaz de usuario (`UI components`) interactivos y visualmente atractivos, como una galería de imágenes con efectos `hover`.
* Construir un portafolio que destaque mi potencial para contribuir en trabajos profesionales y obtener mi primer empleo en el sector del desarrollo web.

## Características
* **Galería Interactiva:** Muestra una cuadrícula de artículos, cada uno con una imagen y un efecto `overlay` que se desliza al pasar el ratón.
* **Efecto Overlay (`articles__overlay`):** Al hacer `hover` sobre un artículo, una capa con fondo de color y texto (título y descripción) se desliza suavemente desde la izquierda, cubriendo la imagen.
* **HTML Semántico:** Uso de elementos `article`, `img`, `h1`, `p` dentro de un contenedor `div.layout` y `flexbox` para la organización.
* **Posicionamiento Avanzado:** `position: relative` en el contenedor del artículo y `position: absolute` para la imagen y el overlay, permitiendo una superposición precisa.
* **Transformaciones y Transiciones CSS:** `transform: translateX(-40rem)` para ocultar el overlay inicialmente y `transform: translateX(0)` para mostrarlo al hacer `hover`, con una `transition` suave.
* **Flexbox para Centrado:** Utilizado para centrar el contenido (título y descripción) dentro del overlay y para organizar la galería principal.
* **Tipografía:** Fuente "Montserrat" importada desde Google Fonts para un estilo moderno.
* **Diseño Responsivo (implícito):** Aunque los artículos tienen un `width` fijo, el `flex-wrap: wrap` en el contenedor `.layout` permite que los artículos se ajusten a la siguiente fila si el ancho de la ventana es insuficiente.
* **Personalizable:** Fácil de modificar editando `index.html` para cambiar las imágenes, títulos y descripciones de los artículos, o `style.css` para ajustar los colores, tamaños, velocidades de transición, y la dirección del efecto de deslizamiento.
* **Alojado en GitHub Pages:** Configurado para despliegue público y demostración en línea.

## Tecnologías utilizadas
* **HTML5:** Estructura semántica para los artículos y el `layout`.
* **CSS3:** Estilos avanzados, `flexbox`, `position`, `transform`, `transition`, y tipografía personalizada.
* **Google Fonts:** Fuente `Montserrat` para un estilo tipográfico moderno (requiere enlace externo).
* **GitHub Pages:** Plataforma de alojamiento para mostrar el trabajo en línea.

## Estructura del trabajo
Galería-de-Artículos-con-Overlay/
├── index.html        # Estructura HTML de la galería de artículos
├── Assets/
│   ├── CSS/
│   │   └── style.css # Estilos CSS de los artículos, overlays y layout
│   └── Fonts/
│       ├── ...       # Fuentes (si las importas localmente)
│       └── Imagen/
│           └── imagenes-proyecto-25-css/ # Directorio de imágenes de la galería
│               ├── foto-1.jpg
│               ├── foto-2.jpg
│               └── foto-3.jpg
└── README.md         # Documentación del trabajo


## Habilidades demostradas
Como estudiante universitario, este trabajo muestra las siguientes competencias:

* **HTML5:** Uso de elementos semánticos para construir una galería de contenido estructurada.
* **CSS3:** Aplicación avanzada de `position: absolute;` y `relative` para superposiciones de elementos. Implementación de `transform` y `transition` para animaciones `hover` suaves y atractivas. Uso de `flexbox` para el `layout` y la alineación.
* **Diseño de Interacción (UX/UI):** Capacidad para crear elementos interactivos que mejoran la experiencia visual del usuario.
* **Control de versiones:** Gestión del trabajo con Git y GitHub.
* **Despliegue web:** Configuración de GitHub Pages para alojamiento público.

## Notas para empleadores
Soy un estudiante universitario apasionado por el desarrollo web, y este trabajo es parte de mi portafolio para demostrar mi aprendizaje en HTML y CSS. Refleja mi capacidad para:

* Diseñar y construir componentes visuales interactivos y dinámicos utilizando técnicas avanzadas de CSS.
* Gestionar el posicionamiento y la superposición de elementos para crear efectos visuales complejos.
* Gestionar trabajos con un flujo de trabajo organizado usando Git y GitHub.

Estoy entusiasmado por iniciar mi carrera como desarrollador frontend y aportar mis habilidades a su equipo. Si desea explorar más trabajos de mi portafolio o discutir mi experiencia, contácteme a través de los detalles proporcionados abajo.

## Contacto
Soy un estudiante en busca de mi primera oportunidad laboral en el desarrollo web. Puedes encontrarme en:

* **GitHub:** [https://github.com/JesusBustos12?tab=repositories](https://github.com/JesusBustos12?tab=repositories)
* **LinkedIn:** [https://www.linkedin.com/in/jesus-bustos-arizmendi-325329283/](https://www.linkedin.com/in/jesus-bustos-arizmendi-325329283/)
* **Correo:** jesusbustosarizmendi0@gmail.com

¡Gracias por revisar mi trabajo!
