# ArquiServicios-Gen1

Brenda KAren Gomez Flres
INGE-00026-1437-PROGRAMACIÓN WEB
Producto transversal. Entrega parcial

# Instrucciones:

Crea un proyecto de sitio web que abarque los temas más importantes del temario, utilizando HTML, CSS y JavaScript. La temática del sitio web es libre, pero debe incluir al menos las siguientes secciones:

a) Página de inicio: Esta página debe presentar una descripción general del sitio web y proporcionar una navegación clara hacia las demás secciones.

b) Sección de Arquitectura de Servicios: En esta sección, explica brevemente la evolución del desarrollo web y la arquitectura cliente-servidor. Puedes utilizar texto, imágenes y/o videos para ilustrar los conceptos.

c) Sección de Lenguaje de Marcas: Aquí, muestra ejemplos de etiquetas HTML5 y explica sus usos básicos. Utiliza al menos cinco elementos de control HTML y muestra su funcionamiento en situaciones diferentes.

d) Sección de CSS3: En esta sección, muestra ejemplos de reglas CSS3 y cómo se aplican a los elementos HTML. Incluye al menos una animación utilizando CSS3. Puedes utilizar frameworks de CSS3 si lo consideras necesario.

# General

Base para crear  Arquitectura de Servicios, Lenguaje de Marcas y CSS3


flowchart TB

    A[Inicio<br>index.html] --> B[Arquitectura<br>arquitectura.html]
    A --> C[Lenguaje de Marcas<br>lenguaje-marcas.html]
    A --> D[CSS3 y Animaciones<br>css3.html]

    B --> A
    C --> A
    D --> A

    subgraph E[Estructura de Archivos]
        F[assets/css/styles.css]
        G[assets/js/main.js]
        H[assets/img/]
    end

    A --- F
    A --- G
    A --- H
    B --- F
    C --- F
    D --- F
