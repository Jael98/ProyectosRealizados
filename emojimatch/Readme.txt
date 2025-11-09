# Memoria con Emojis

Un divertido juego de **memoria (Memory Game)** implementado en Python con **emojis** como cartas.  
El tablero es de **9 filas × 4 columnas** (36 casillas), con **18 pares únicos** de emojis ocultos bajo el símbolo ❓.

¡Encuentra todos los pares antes de quedarte sin intentos!

---

## Captura del juego
['❓', '❓', '❓', '❓']
['❓', '❓', '❓', '❓']
...
['❓', '❓', '❓', '❓']


> Al elegir una casilla, se revela el emoji. Si eliges otro igual → ¡par encontrado!  
> Si no, se ocultan de nuevo tras unos segundos.

---

## Características

- Tablero 9×4 con 18 pares de emojis únicos
- Validación de entrada robusta (números, rangos, errores)
- Efecto de "memoria" con `time.sleep()` y `clear_output`
- Interfaz limpia en consola con números de fila
- Emojis aleatorios en cada partida

---

## Requisitos

- Python 3.6 o superior
- Jupyter Notebook **(recomendado para mejor experiencia)**
- Módulos:
  ```bash
  pip install ipython