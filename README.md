# Práctica Flexbox 1: Maquetación de Estructura Básica (Beca Erasmus+)

Este repositorio contiene la primera fase del desarrollo de un formulario web para la solicitud de la Beca ERASMUS+ de movilidad a Polonia para el módulo de Desarrollo de Interfaces Web (DIW). El objetivo principal de esta entrega ha sido estructurar y maquetar la cabecera, el contenido principal y el pie de página siguiendo un diseño limpio y minimalista.

## Proceso de Desarrollo y Estructuración

Para la realización de esta práctica se han seguido de manera secuencial los siguientes pasos técnicos:

### 1. Configuración del Repositorio
* Se ha creado el repositorio público en GitHub siguiendo la nomenclatura especificada: `diw-flexbox1-GarciaCobos-Ayo`.
* Se procedió a clonar el repositorio localmente en el equipo de desarrollo.
* Se vinculó el espacio de trabajo con el entorno de desarrollo **Visual Studio Code**.

### 2. Estructuración Semántica (HTML5)
Se ha implementado una estructura HTML limpia, accesible y semántica dividida en tres bloques fundamentales dentro del `<body>`:
* **`<header>`**: Contiene la identidad de la aplicación (`.logo`) y un sistema de navegación principal (`<nav>`).
* **`<main>`**: Bloque destinado a albergar el núcleo de la aplicación, que actualmente inicializa el título del formulario de movilidad a Polonia (`<h1>`).
* **`<footer>`**: Sección de cierre que incluye los derechos de autor/créditos del proyecto de aula y un menú de navegación secundario para aspectos legales y de accesibilidad.

### 3. Diseño y Distribución del Flujo (CSS3 Flexbox)
La maquetación visual se ha resuelto de forma nativa utilizando el módulo **Flexible Box Layout (Flexbox)** con un enfoque minimalista:
* **Estructura Vertical del Documento**: El elemento contenedor global `body` se ha configurado con `display: flex` y `flex-direction: column` para gestionar eficientemente el espaciado en bloque (`gap`) entre la cabecera, el cuerpo y el pie de página.
* **Componentes en Bloque**: Tanto el `<header>` como el `<footer>` actúan como contenedores Flexbox ordenados en sentido vertical.
* **Navegación Vertical Desordenada**: Para cumplir con los requisitos visuales, la lista de navegación del menú principal (`main-nav ul`) se configuró mediante `flex-direction: column`, forzando a los elementos a posicionarse hacia abajo. Asimismo, se ha restaurado la propiedad `list-style: disc` combinada con un `padding-left` adecuado para preservar los puntos (viñetas) tradicionales de una lista desordenada.

## Tecnologías Utilizadas
* HTML5 Semántico
* CSS3 (Módulo Flexbox)
* Git y GitHub para el control de versiones
