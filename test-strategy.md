1- Revisando en consola se pudo comprobar que la función addEventListener no estaba "declarada" correctamente en checkGuess.

2- Se encuentra en consola que a la variable constante LowOrHi le hace falta el punto que le indica que es una clase.

3- Se comprueba en consola que Math.random necesita ser multiplicado por un número más alto para cumplir con el numero aleatorio entre 1 y 100.

4- Se para que el juego funcione se agrega Math.floor para que regrese un valor entero de Math.random.

5- La variable ATTEMPS estaba configurada únicamente para 5 intentos, se agregan los 10 intentos descritos en las instrucciones.

6- En código se observa lo siguiente:
	
	- Si el número ingresado es igual al número aleatorio, muestra: '!!!Pérdistes!!!' (Se cambió por 'felicitaciones')
	- Si la cantidad de intentos es igual a la variable ATTEMPS, muestra: 'Felicitaciones! adivinaste el número!' (Se cambió por '!!!Pérdistes!!!')

7- En el input de ingreso de número se modificó para que sólo permita ingreso de números.

8- En la función CheckGuess a la variable userGuess se le indica que el valor que espera recibir es un número. (Las letras las tomaba como intento).

9- Revisando en consola se pudo comprobar que la función addEventListener no estaba "declarada" correctamente en setGameOver.

10- Se agrega una alerta cuando el usuario ingresa un número menor a 1 o mayor a 100. 
    El ingreso menor a 1 o mayor a 100 se toma como intento fallido aunque muestre la alerta.
