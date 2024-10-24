# Tetris Game

Este proyecto es una implementación simple del clásico juego Tetris utilizando HTML, CSS y JavaScript. El objetivo es crear una experiencia de juego retro con algunas funcionalidades modernas como la pausa, caída instantánea y detección de game over.

## Características

- Juego de Tetris totalmente funcional con controles de teclado.
- Diferentes piezas: I, O, T, L, J, S, Z con colores característicos.
- Detección de colisiones y eliminación de líneas.
- Sistema de puntuación que aumenta con cada línea eliminada.
- Funcionalidad de pausa y reinicio del juego.
- Ajuste automático de la velocidad a medida que el jugador progresa.
- Efecto visual para el texto de pausa y un diseño minimalista.

## Controles del juego

- `↑`: Rotar la pieza.
- `← →`: Mover la pieza hacia la izquierda o derecha.
- `↓`: Bajar la pieza rápidamente.
- `Espacio`: Caída instantánea de la pieza.
- `P`: Pausar o reanudar el juego.

## Instalación

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu-usuario/tetris-game.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd tetris-game
   ```
3. Abre el archivo `index.html` en tu navegador favorito para comenzar a jugar.

## Cómo funciona

El juego utiliza un lienzo (`<canvas>`) en HTML para dibujar la cuadrícula del tablero y las piezas. El código JavaScript maneja la lógica del juego, incluyendo la generación aleatoria de piezas, la detección de colisiones, la rotación, y la fusión de las piezas en el tablero.

### Principales funciones

- **`createBoard`**: Inicializa el tablero del juego.
- **`spawnPiece`**: Genera una nueva pieza aleatoria.
- **`collision`**: Verifica si la pieza actual colisiona con el tablero o con otras piezas.
- **`merge`**: Funde la pieza actual en el tablero y verifica si el juego ha terminado.
- **`clearLines`**: Elimina las líneas completas y actualiza la puntuación.
- **`togglePause`**: Alterna entre pausar y reanudar el juego.
- **`update`**: Función principal de actualización del juego que se ejecuta en cada cuadro.

## Personalización

El estilo visual del juego puede ser modificado a través del archivo CSS. Puedes cambiar los colores de fondo, el tamaño de los bloques y el esquema de colores de las piezas. Además, puedes ajustar la lógica del juego en el archivo JavaScript, como la velocidad de caída o las puntuaciones asignadas a cada línea eliminada.

## Mejoras Futuras

Algunas posibles mejoras que podrían implementarse:
- Efectos visuales adicionales para cuando se eliminan líneas.
- Integración de sonidos para una mejor experiencia de juego.
- Guardado del puntaje más alto en el almacenamiento local del navegador.
- Soporte para diferentes niveles de dificultad.

## Licencia

Este proyecto se encuentra bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

