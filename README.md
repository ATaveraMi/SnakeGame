# SnakeGame

Snake Game Semana Tec

## Funciones del Juego -  Marce

### `change_colors()` Marce

Esta función cambia los colores de la serpiente y la comida cada 5 segundos (el tiempo se puede ajustar según las preferencias del usuario).

- **Descripción:**
  La función `change_colors()` selecciona aleatoriamente nuevos colores para la serpiente y la comida de una lista predefinida de colores. Utiliza la función `ontimer()` para llamar a sí misma cada 1000 milisegundos (1 segundo), permitiendo que los colores cambien en intervalos regulares.

- **Uso:**
  La función es llamada al inicio del juego con `change_colors()`, y continuará cambiando los colores mientras el juego esté en ejecución.



### `move_food()` Tavera


Esta función mueve la comida horizontalmente a través de la ventana del juego.

- **Descripción:**
  Descripción: La función move_food() incrementa la coordenada x de la comida en 10 unidades cada 500 milisegundos
. Cuando la comida alcanza el borde derecho de la ventana (coordenada x mayor a 190), la función la envuelve al borde izquierdo (coordenada x igual a -190). Utiliza la función ontimer() para llamar a sí misma cada 500 milisegundos, asegurando que la comida se mueva continuamente.

- **Uso:**
La función es llamada al inicio del juego con move_food(), y continuará moviendo la comida horizontalmente mientras el juego esté en ejecución.

