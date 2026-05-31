# 👕 Configurador de Franelas Interactivo - Alta Fidelidad de Color

Este es un visualizador de productos interactivo desarrollado con tecnologías web nativas (**HTML5, CSS3 y JavaScript**). Permite a los usuarios explorar una paleta de colores corporativa y previsualizar en tiempo real cómo lucirá la prenda, garantizando una precisión cromática absoluta sin perder el volumen físico del producto.

[ Ver proyecto en vivo](https://landirianositeoficial-pro.github.io/Selector-de-color-para-franelas-/)


## 🚀 Características Clave

* **Renderizado Local Seguro:** Diseñado con lógica basada en el elemento `<canvas>` de HTML5 para saltarse las restricciones estrictas de aislamiento de archivos locales (`file:///` o bloqueos CORS).
* **Fidelidad Textil:** Utiliza un algoritmo de doble capa (`multiply` + `screen`) que inyecta el color exacto de la paleta mientras retiene de forma hiperrealista las sombras, pliegues y luces reflejadas de la tela.
* **Interfaz Inteligente (UI/UX):** La tarjeta de visualización detecta colores claros (como el blanco o blanco perlado) y oscurece el fondo del contenedor automáticamente para evitar que la prenda se pierda ópticamente.
* **Información Dinámica:** Muestra en pantalla el nombre comercial del color y su código HEX exacto según la selección del cliente.

## 🛠️ Tecnologías Utilizadas

* **HTML5 Canvas API:** Para la manipulación y repintado de píxeles en tiempo real.
* **CSS3 Moderno:** Diseño responsivo, variables nativas (`:root`) y animaciones fluidas en la paleta de botones.
* **Vanilla JavaScript:** Lógica síncrona optimizada para el manejo seguro de la carga de imágenes en caché.

## 📁 Estructura del Proyecto

Para el correcto funcionamiento local, el repositorio requiere mantener la siguiente estructura jerárquica en la carpeta:
* `index.html` — Código fuente unificado del configurador.
* `franela-base.png` — Mockup base de la prenda en escala de grises desaturada con canal alfa (fondo 100% transparente).

---
Desarrollado como parte de mi portafolio de herramientas interactivas de comercio electrónico.
