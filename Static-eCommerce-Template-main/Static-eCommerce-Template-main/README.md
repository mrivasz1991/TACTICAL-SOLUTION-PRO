# NovaCompu - eCommerce Static Template

Plantilla básica de un sitio web de comercio electrónico desarrollada con
HTML estático. El proyecto está pensado como una práctica introductoria para
conocer la estructura de un sitio web, organizar sus archivos y reconocer el
esquema principal de una página de inicio (`index.html`).

![Vista previa de NovaCompu](img/logo.png)

## Estructura de la página principal

El archivo `index.html` contiene el desarrollo visible de la plantilla y se
organiza de la siguiente manera:

| Sección | Elementos principales | Función |
| --- | --- | --- |
| `head` | Codificación UTF-8, configuración responsive y título | Define información básica del documento. |
| `header` | Logo, nombre **NovaCompu** y menú principal | Presenta la identidad y navegación de la tienda. |
| `nav` | Enlaces a Acerca de, Productos, Contacto y Carrito | Muestra las áreas previstas para el sitio. |
| `main` | Sección de bienvenida y sección de productos | Contiene el contenido principal de inicio. |
| Productos más vendidos | Tabla con imágenes y enlaces de acción | Presenta diez artículos tecnológicos de ejemplo. |
| `footer` | Aviso de derechos reservados de 2026 | Cierra la página con información institucional. |



## Estructura de archivos

```text
static/
|-- index.html              # Página de inicio implementada
|-- about.html              # Página prevista: acerca de la tienda
|-- products.html           # Página prevista: catálogo de productos
|-- contact.html            # Página prevista: contacto
|-- cart.html               # Página prevista: carrito
|-- 404.html                # Página prevista para errores
|-- css/
|   `-- styles.css          # Archivo preparado para estilos CSS
|-- js/
|   `-- main.js             # Archivo preparado para lógica JavaScript
|-- img/
|   |-- logo.png            # Logotipo de NovaCompu
|   |-- captura1.png        # Captura utilizada en este README
|   |-- banner.jpg          # Recurso reservado para banner
|   `-- products/           # Imágenes del catálogo mostrado en inicio
`-- pages/
    |-- help.html           # Página prevista: ayuda
    |-- privacy.html        # Página prevista: privacidad
    `-- terms.html          # Página prevista: términos
```

|


## Tecnologías utilizadas

- **HTML5:** estructura semántica y contenido de la página inicial.
- **CSS:** carpeta preparada para incorporar diseño visual en una siguiente
  etapa.
- **JavaScript:** carpeta preparada para incorporar comportamiento interactivo
  en una siguiente etapa.


