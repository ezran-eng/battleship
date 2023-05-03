# Battleship
¡Hola y bienvenido a mi juego de Batalla Naval! Estoy emocionado de presentarte un emocionante juego de estrategia y azar, donde puedes poner a prueba tus habilidades contra un amigo. Pero este no es cualquier juego de Batalla Naval, este es un juego que yo mismo creé y estoy orgulloso de decir que incluye un componente de jugador contra jugador que hará que la jugabilidad sea aún más emocionante.

Las reglas del juego son simples: cada jugador agrega barcos a su campo uno por uno, sin mirar las pantallas del otro, y luego comienzan a bombardearse entre sí hasta que uno de ellos tenga éxito. Para que el juego sea justo y evitar que los jugadores miren los campos del otro, después de cada movimiento, aparecerá en la pantalla el mensaje "Presione Enter y pase el turno a otro jugador", borrando la pantalla del movimiento anterior.

Puedes comenzar a jugar siguiendo estas sencillas reglas: cada jugador agrega barcos a su campo uno por uno, sin espiar las pantallas del otro, y luego empiezan a dispararse el uno al otro hasta que uno de ellos tenga éxito. Para que el juego sea justo y evitar que los jugadores espíen los campos del otro, después de cada turno aparecerá en la pantalla el mensaje "Presiona Enter y pasa el turno a otro jugador", borrando la pantalla del movimiento anterior.

Para comenzar, necesitarás colocar tus barcos en el campo de juego ingresando las coordenadas de cada barco, uno a la vez. Deberás ingresar la longitud de cada barco y luego las coordenadas de inicio y final. Si cometes un error, el juego te pedirá que lo intentes de nuevo.

El juego se juega en una cuadrícula de 10x10, con la pantalla del jugador ubicada en la parte inferior y la pantalla del oponente en la parte superior. Las coordenadas se indican con letras para las filas (A-J) y números para las columnas (1-10).

Entonces, ¿estás listo para enfrentarte a tu amigo en un juego de Batalla Naval? ¡Descarga mi juego y comienza hoy mismo!

````
Player 1, place your ships on the game field

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Aircraft Carrier (5 cells):

> F3 F7

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Battleship (4 cells):

> A1 D1

1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ ~ ~
C O ~ ~ ~ ~ ~ ~ ~ ~ ~
D O ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Submarine (3 cells):

> J7 J10

Error! Wrong length of the Submarine! Try again:

> J10 J8

1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ ~ ~
C O ~ ~ ~ ~ ~ ~ ~ ~ ~
D O ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ O O O

Enter the coordinates of the Cruiser (3 cells):

> B9 D8

Error! Wrong ship location! Try again:

> B9 D9

1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ O ~
C O ~ ~ ~ ~ ~ ~ ~ O ~
D O ~ ~ ~ ~ ~ ~ ~ O ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ O O O

Enter the coordinates of the Destroyer (2 cells):

> E6 D6

Error! You placed it too close to another one. Try again:

> I2 J2

1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ O ~
C O ~ ~ ~ ~ ~ ~ ~ O ~
D O ~ ~ ~ ~ ~ ~ ~ O ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ O ~ ~ ~ ~ ~ ~ ~ ~
J ~ O ~ ~ ~ ~ ~ O O O

Press Enter and pass the move to another player
...
Player 2, place your ships to the game field

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Aircraft Carrier (5 cells):

> H2 H6

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ O O O O O ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Battleship (4 cells):

> F3 F6

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ O O O O O ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Enter the coordinates of the Submarine (3 cells):

> H8 F8

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O ~ O ~ ~
G ~ ~ ~ ~ ~ ~ ~ O ~ ~
H ~ O O O O O ~ O ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

...

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ O ~ ~
D ~ ~ ~ O O O ~ O ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O ~ O ~ ~
G ~ ~ ~ ~ ~ ~ ~ O ~ ~
H ~ O O O O O ~ O ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Press Enter and pass the move to another player
...

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
---------------------
1 2 3 4 5 6 7 8 9 10
A O ~ ~ ~ ~ ~ ~ ~ ~ ~
B O ~ ~ ~ ~ ~ ~ ~ O ~
C O ~ ~ ~ ~ ~ ~ ~ O ~
D O ~ ~ ~ ~ ~ ~ ~ O ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O O ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ O ~ ~ ~ ~ ~ ~ ~ ~
J ~ O ~ ~ ~ ~ ~ O O O

Player 1, it's your turn:

> I3

You missed!
Press Enter and pass the move to another player
...

1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
D ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
G ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
H ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
I ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
---------------------
1 2 3 4 5 6 7 8 9 10
A ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
B ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
C ~ ~ ~ ~ ~ ~ ~ O ~ ~
D ~ ~ ~ O O O ~ O ~ ~
E ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
F ~ ~ O O O O ~ O ~ ~
G ~ ~ ~ ~ ~ ~ ~ O ~ ~
H ~ O O O O O ~ O ~ ~
I ~ ~ M ~ ~ ~ ~ ~ ~ ~
J ~ ~ ~ ~ ~ ~ ~ ~ ~ ~

Player 2, it's your turn:

> A1

You hit a ship!
Press Enter and pass the move to another player
...
