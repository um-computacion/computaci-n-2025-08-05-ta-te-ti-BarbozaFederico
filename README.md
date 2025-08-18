## Autor
Federico Barboza
## Estructura del proyecto

- `src/`
  - `cli.py`: Interfaz de línea de comandos para jugar Tateti.
  - `jugador.py`: Clase para representar a cada jugador.
  - `tablero.py`: Clase que gestiona el tablero y la lógica de ganador.
  - `tateti.py`: Lógica principal del juego, alternancia de turnos y verificación de ganador.
- `tests/`
  - `test_tablero.py`: Pruebas unitarias para la clase Tablero.
  - `test_tateti.py`: Pruebas unitarias para la clase Tateti.
  - `test_cli.py`: Pruebas de integración para el flujo de juego.

## Cómo jugar

1. Abre una terminal en la raíz del proyecto.
2. Ejecuta el juego con:
   ```
   py src/cli.py
   ```
3. Ingresa las coordenadas de fila y columna (de 0 a 2) cuando se te solicite.
4. El juego alterna turnos entre dos jugadores y anuncia el ganador cuando alguien logra el tateti.

## Cómo ejecutar los tests

Puedes ejecutar las pruebas unitarias con:
```
py -m unittest tests/test_tablero.py
py -m unittest tests/test_tateti.py
py -m unittest tests/test_cli.py
```



