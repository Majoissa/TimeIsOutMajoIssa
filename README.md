# Time is Out

## Introducción
Bienvenido al repositorio del videojuego "Time is Out". A continuación, se detallan las funcionalidades y características principales que se han implementado en el juego.

## Funcionalidades Implementadas

### Enemigos y Obstáculos
- **Sistema de partículas en la cabeza del enemigo**: Mejora la visibilidad y el impacto visual durante el combate.
- **Nivel 3**:
  - Todos los actores configurados (botones, puerta inicial y final, hammers).
  - Zonas especiales como la zona de victoria y la zona de morir en el agua. Triggers añadidos a ambas con funcionalidades de morir si toca el agua, y pasar al siguiente nivel si pasa a la victory zone.

### UI del Jugador
- **Indicador de daño**: La pantalla se torna roja rápidamente al morir para mejorar la retroalimentación visual al jugador.
- **Tecla 'M'**: Permite al jugador volver al menú principal de forma instantánea.

### Menú Principal
- **Selección de Niveles**: Escena con botones para comenzar los niveles 1, 2, y 3.
  - Los niveles se desbloquean progresivamente; solo el nivel 1 está disponible inicialmente.
  - Botón de salida que finaliza la ejecución del juego.

### Ambiente y Efectos
- **Sistema de partículas de nieve en Nivel 3**
- **Sistema de partículas de lluvia en Nivel 1**

### Mecánicas de Juego
- **Plataformas móviles**: Transportan al jugador de un punto a otro, añadiendo complejidad y dinamismo al juego.
- **Obstáculo de fuego móvil**: Presente en los niveles 2 y 3, este obstáculo debe ser esquivado para evitar la muerte y reinicio del nivel.

