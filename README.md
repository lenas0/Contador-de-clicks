# Contador-de-clicks con Three.js

Un juego clicker incremental con un cubo 3D animado en el fondo. Haz clic para ganar puntos y desbloquea mejoras para aumentar tus ganancias automáticas y por clic.

## Descripción

Este es un juego idle/clicker donde los jugadores pueden acumular puntos haciendo clic en la pantalla y comprando mejoras que aumentan la eficiencia de generación de puntos. El juego cuenta con un cubo 3D rosado que gira constantemente en el fondo, creado con Three.js.

## Características

- Sistema de clics para generar puntos
- Cubo 3D animado en el fondo
- Tres tipos de mejoras diferentes
- Generación automática de puntos
- Interfaz colorida y moderna
- Diseño responsive
- Efectos de hover en botones
- Contador de puntos en tiempo real

## Tecnologías

- HTML5 - Estructura
- CSS3 - Estilos y animaciones
- JavaScript (ES6) - Lógica del juego
- Three.js (r128) - Gráficos 3D

## Instalación

Clona este repositorio y abre el archivo index.html en tu navegador web.

No requiere instalación de dependencias. Three.js se carga desde CDN.

## Estructura de archivos

El proyecto contiene:
- index.html - Estructura HTML principal
- main.js - Lógica del juego y animación 3D
- styles.css - Estilos y diseño visual
- README.md - Este archivo

## Cómo jugar

1. Abre el juego en tu navegador
2. Haz clic en cualquier parte de la pantalla para ganar puntos
3. Usa los puntos para comprar mejoras en el panel derecho
4. Observa cómo tu puntaje aumenta automáticamente con las mejoras

## Sistema de mejoras

El juego incluye tres mejoras diferentes:

- Mejora 1: Incrementa el valor base de cada clic
- Mejora 2: Aumenta el multiplicador de puntos
- Mejora 3: Incrementa la generación automática de puntos

## Mecánicas del juego

- Cada clic genera puntos según la fórmula: incrementoBase × multiplicador
- El juego genera puntos automáticamente cada frame
- Los puntos se muestran redondeados al número entero más cercano
- El cubo 3D gira continuamente en ambos ejes

## Características técnicas

- Renderizado 3D con WebGL a través de Three.js
- Animación a 60 FPS mediante requestAnimationFrame
- Interfaz posicionada absolutamente sobre el canvas 3D
- Diseño con fuente Poppins de Google Fonts
- Paleta de colores pastel moderna

## Paleta de colores

- Fondo principal: Rosa claro (#ffeefc)
- Panel de puntaje: Verde agua (#c1e1dc)
- Panel de mejoras: Rosa suave (#f6c1c1)
- Botones: Durazno (#f7d9c4)
- Botones hover: Lavanda (#d7bee2)
- Cubo 3D: Rosa brillante (#ffb6c1)

## Futuras mejoras

- Sistema de costos para las mejoras
- Diferentes tipos de mejoras con efectos visuales
- Sistema de guardado automático
- Más elementos 3D interactivos
- Achievements y logros
- Sonidos y efectos de audio
- Múltiples niveles o fases
- Sistema de prestigio

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

## Autor

Claudia Lorena Cerquera 
