# Aplicando algoritmos de Machine learning de regresión y clasificación a datos de partidas de ajedrez

El siguiente notebook es el proyecto final de la asignatura de Machine Learning de la licenciatura en Inteligencia Artificial impartida en la Universidad Autónoma del Estado de Morelos. El trabajo tiene como finalidad utilizar algoritmos de regresión y clasificación para encontrar el mejor modelo para el dataset que el alumno haya elegido.  
Para llevar acabo la práctica se usarán las librerías Numpy, Pandas, Matplotlib, Seaborn y Scikitlearn, todas librerías de python.
Para este proyecto se eligió un notebook con 4GB de informacion de 6.25 millones de partidas de ajedrez jugadas en lichess.org durante julio del 2016.


## Información del dataset
  
La información de las columnas es la siguiente:
- Event: Tipo de juego.
- White: DNI del blanco.
- Black: ID del negro.
- Result: Resultado del juego (1-0 victorias blancas) (0-1 victorias negras)
- UTCDate: Fecha UTC.
- UTCTime: Hora UTC.
- WhiteElo: ELO de las blancas.
- BlackElo: ELO de las negras.
- WhiteRatingDiff: diferencia de puntos de rating de las blancas después del juego.
- BlackRatingDiff: diferencia de puntos de rating de los negros después del partido.
- ECO: Apertura en codificación ECO.
- Opening: Nombre de la apertura.
- TimeControl: Tiempo de juego de cada jugador en segundos. El número después del incremento es el número de segundos antes de que el reloj del jugador comience a correr en cada turno.
- Termination: Motivo del final del juego.
- AN: Movimientos en formato Movetext.
