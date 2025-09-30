# Snake 

## Historia del juego 
El primer Snake apareció en 1976 bajo el nombre de _**Blockade**_, creado por _**Gremlin Industries**_ como un juego de arcade. La idea central del juego era tan simple como adictiva: evitar chocar con las paredes y con tu propio cuerpo, que iba aumentando de longitud conforme avanzabas en el juego.

La versión más icónica, sin embargo, fue desarrollada por _**Taneli Armanto**_, un ingeniero finlandés que trabajaba para _**Nokia**_. En 1997, Armanto adaptó el juego para que fuera incluido en el _**Nokia 6110**_, uno de los primeros modelos de teléfono móvil que integraba juegos. Desde entonces, el Snake se convirtió en un fenómeno cultural. 

### Reglas y Mecánicas 
- Debes controlar una serpiente que avanza continuamente, moviéndola con las teclas de dirección (arriba, abajo, izquierda, derecha) para que coma la comida que aparece en la pantalla y crezca más.
- El objetivo principal es evitar dos cosas: chocar contra las paredes del área de juego y morder tu propia cola, ya que cualquiera de estos eventos provocará el fin de la partida. Cada vez que la serpiente come, su longitud aumenta, y su puntaje se basa en el número de segmentos o cuadrados que ha añadido a su cuerpo.

### Algoritmo
1. Inicializar:

    - Crear tablero.

    - Colocar serpiente y comida aleatoria.

    - Definir dirección inicial.

1. Bucle del juego:

    - Leer entrada del jugador (↑ ↓ ← →).

    - Mover serpiente (nueva cabeza en dirección, borrar cola si no comió).

    - Si come → crecer y generar nueva comida.

    - Verificar colisiones (bordes o cuerpo → fin).

    - Dibujar tablero y esperar un instante.

1. Fin:
    - Mostrar puntaje y opción de reiniciar.

### Diagrama de Flujo
![](../ASSETS/Diagrama%20sin%20título.drawio.png)