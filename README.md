# 🎮 DASH LEVELS — ¡Construye con tus manos!

> **Sistema web inteligente e interactivo para videojuegos dirigido a contribuir en la motricidad de los niños, potenciado por visión artificial en tiempo real.**

Dash Levels es una plataforma web experimental que fusiona el procesamiento biométrico avanzado con entornos interactivos tridimensionales. Mediante el uso de la cámara web, el sistema interpreta los movimientos y gestos de la mano del usuario para interactuar con videojuegos y mecánicas de construcción sin necesidad de un teclado, ratón o mando físico.

---

##  Características Principales y Modos de Juego

El sistema cuenta con una interfaz inmersiva de estética retro-futurista (Orange & Black Theme) y ofrece cuatro modalidades de interacción:

*   **🧱 Modo Retos (Desafíos contrarreloj):** Construcción guiada de figuras tridimensionales (como cohetes espaciales) colocando bloques mediante un sistema de objetivos y tiempo límite.
*   **🌟 Modo Libre:** Un espacio creativo sin restricciones ni límites de tiempo para experimentar libremente con las mecánicas de construcción.
*   **🎮 Modo Tetris:** El clásico juego de bloques adaptado para ser controlado en su totalidad mediante gesticulación manual.
*   **🎲 Modo Rubik 2x2:** Un rompecabezas tridimensional interactivo que se resuelve deslizando los dedos en el espacio.

---

##  Diccionario de Gestos Biométricos

Para controlar la interfaz y los entornos de juego, el usuario cuenta con los siguientes comandos gestuales mapeados por visión artificial:

| Gesto | Acción Asignada |
| :---: | --- |
| **👆** | **Señalar:** Mueve el cursor en pantalla y sirve para apuntar. |
| **🖐** | **Palma Extendida:** Sirve para seleccionar opciones del menú y navegar en la interfaz. |
| **🤏** | **Pellizcar:** Ejecuta la acción de construir o colocar bloques. |
| **✌️** | **Signo de Paz:** Alterna dinámicamente entre las gamas de colores disponibles. |

---

##  Arquitectura Tecnológica del Sistema


Este software está construido bajo una arquitectura cliente basada en tecnologías web de alto rendimiento:

*   **Procesamiento de Video e IA:** Integración de modelos para el rastreo de malla de mano (*Hand Tracking*) y extracción de coordenadas biométricas en tiempo real.
*   **Gráficos 3D:** Renderizado tridimensional mediante contextos WebGL (Canvas de soporte `three_canvas`).
*   **Estilos e Interfaz:** Animaciones fluidas basadas en CSS Custom Properties (`:root`), efectos de desenfoque de fondo (*backdrop-filter*) y tipografías dinámicas de Google Fonts (Nunito y Boogaloo).
*   **Diseño Sonoro:** Audio ambiental adaptativo implementado dinámicamente según el modo seleccionado.

## ⚡ El futuro es ahora
Construye, diviértete y experimenta una nueva forma de jugar. **¡Pruébalo ya en [DASH LEVELS](https://dashlevelss.netlify.app/)!**

*Desarrollado con mucho cariño🧡 por [**@hydem._**](https://www.instagram.com/hydem._?igsh=MXNiOGp5dTJ0Zjc4ZA==)*