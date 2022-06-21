Errores
Error:
En la constante restParas al seleccionar la clase habia una p de mas
Solucion:
Se termino quitando el caracter de mas para que pueda ser seleccionado correctamente

Error:
Se tenia un Math.random esto hace que genere numero aleatorios booleanos
Solucion:
Se agrego Math.floor dentro de el un Math.random con un rango de 99+1
esto con la finalidad de que si genere un cero simpre exista el numero 1

Error:
El boton submit no contiene la funcion checkGuess
Solucion:
Se agrego el atributo onclick con el valor de la funcion checkGuess() para ser llamada.

Error:
La variable ATTEMPS tiene un valor de 5 intentos
Solucion:
Se le fue cambiado el numero para que este pueda llegar hatas 10 intentos

Error:
La variable lowOrHi no estaba seleccionando una clase por falta del punto
Solucion:
Se le agrego el punto para que se seleccionara la clase correctamente

Error:
Los mensaje y colores que se agregaban en cada condicion estaban incorrectos
Soluciion:
Se le cambiaron los mensajes y los estilos a los colores correctos

Error:
El usuario puede agregar valores negativos y mas de 100
Solucion:
Se agrego una condicion, el valor ingresadi debe estar entre 0 y 100 para que pueda ser valido e ingresar sino solo se muestra una alerta

Error:
userGuess y randomNumber estaban igualados en una condicion "===" por lo que nunca iva a ingresar por que uno es de tipo string y otro de tipo int
Solucion:
Se le de unicamende dos "=" para que esto pueda tener validez y entrar a esa condicion

Error:
La variable resetButton no agrega el atributo onclick ni la clase resetGame()
Solucion:
Se les fue agregado el atributo y la funcion con la opcion de setAttribute

