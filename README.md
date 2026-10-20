# Portafolio Frontend - Salón de la Fama D&D

## Descripción
Este proyecto es un portafolio web personal construido para la asignatura Desarrollo de Frontend (ICINF1107). Su propósito es servir como un "Salón de la Fama" para mis personajes de Dungeons & Dragons, demostrando mis habilidades técnicas y mi creatividad.

## Tecnologías Utilizadas
* HTML5 (Estructura semántica pura, sin divs superfluos).
* CSS3 (Diseño responsivo y variables nativas).

## Decisiones de Diseño Orientadas al Usuario
* **Audiencia y Propósito:** Diseñado para otros jugadores de rol (Dungeon Masters) y evaluadores académicos. Necesitan ver información clara, rápida y estructurada.
* **Jerarquía Visual:** Se usó un fondo oscuro (`#1a1a1a`) con texto claro (`#f4f4f4`) para reflejar la temática de D&D y garantizar alto contraste. 
* **Accesibilidad (WCAG):** 
  * Se implementó un estado `:focus` color amarillo brillante para la navegación con teclado.
  * Todas las imágenes vectoriales SVG incluyen atributos `alt` descriptivos.
  * Formularios estructurados con etiquetas `<label>` forzadas a su respectivo `input`.
* **Responsividad:** 
  * **Móvil (default):** Tarjetas apiladas en 1 columna.
  * **Tablet (768px):** Grid de 2 columnas.
  * **Escritorio (1024px):** Grid de 3 columnas para mostrar a Sildra, Aldric y Torgun simultáneamente.

## Capturas de Pantalla
* [Vista Escritorio](img/capturas/escritorio.png)
* [Vista Tablet](img/capturas/tablet.png)
* [Vista Móvil](img/capturas/movil.png)
* [Evidencia de Accesibilidad (Foco de Teclado)](img/capturas/foco-teclado.png)

## Cómo abrirlo
1. Descarga el repositorio o descomprime el archivo ZIP.
2. Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Edge). No requiere instalación de dependencias ni servidores locales.
