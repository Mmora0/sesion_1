# Esta es la documentación de la Sesión 1

Desarrollador por: MIGUEL ANGEL MORA ORTIZ
Programa: DESARROLLO DE VIDEOJUEGOS Y ENTORNOS INTERACTIVOS
SENA
Ibagué, Tolima 
Colombia

Clase 1 - Programación básica
Introducción al curso



Clase 2 

*variable - datos de corto tiempo


*función  - serie de código largo o corto que tiene un objetivo 
         
     * una función se invoca, mediante parentesis
     * dentro del parentesis va el parametro, que es el valor para la función

Programar: controlar el flujo de acciones que ocurren dentro de una computadora. Dominar la computadora




Clase 3


ARCHIVOS

*archivo.extensión
*carta.docx
*hoja.xls
*pagina.html

Crear un archivo no importa cual, todos son de inserción de texto.

Podemos usar un bloc de notas para maquetar en html

Etiquetas usadas:
<h1></h1>
<strong></strong>




Clase 4

HTML es un lenguaje que funciona como un árbol


Etiquetas usadas:
<html></html>
<head></head>
<title></title>
<body></body>
<h1></h1>
<p></p>
            




Clase 5

Script {etiqueta para código}


Orden de lectura=
html > head > title > script > body > h1 > p


Cuando se empieza la lectura de arriba hacia abajo, hay que dar primero los valores, luego la operación (alert), de esta manera =          alert("mensaje" + (operación de los valores dados)) El "+" por fuera de una operación es para unir, no sumar.     

*Cuando se unen dos o más valores, se llama concatenación.





Clase 6


meta charset="utf-8" />

 utf-8 = Estandar que nos permite agregar tildes, eñes y demás detalles de nuestro lenguaje.




Clase 7

Cómo se declara una variable?
	La forma correcta de hacerlo es reservando el nombre en la memoria para luego usarla en nuestra aplicación

(let) = Nos permite designar variables
(prompt) = Nos permite obtener un texto



Clase - 8

Condicional: Es un código que solo se ejecuta si la condición se cumple

(if) = Para determinar la condición
({}) = nos permite introducir el código que se va a ejecutar
(else if) = se usa para realizar el código en cascada si la primera condición no se cumple
(else) = se  usa cuando niguna de las otras condiciones se cumplen

Cuando se utiliza solo un '=' es para asignación (esto entra dentro de esto)
Utilizando dos '==' es para comparación (esto es igual a esto)



Clase - 9

(&&) = Para comparar dos cosas al mismo tiempo 

Se deben tener en cuenta todas laa opciones que se nos den, para que no queden condiciones libres 


Clase - 10

Para crear un número aleatorio en computadora se hace un rango de 0 a 1.

(Math.floor) = función utilizada para quitar decimales "Math" es la clase. '.' llama la función y "floor" el nombre de la función
(Math.random) = función para generar números aleatorios, entre 0 y 1.

Para programar un número aleatorio en un rango:

	min = 1   max = 3
	n = Math.floor(Math.random()*(max-min+1)+min)
	     

(function) = son parecidas a las variables
(return) = 



Clase - 11


Ejemplo de una función:
					comida = traer (sandwich, tienda)

*  El nombre de una función es un nombre de variable, los nombres de variable es una buena práctica que empiece con una letra y esta sea minuscula. Se coloca entre parentesis los parametros que le ponemos a la función y cada parametro separado por una coma ','. El "return" es para el paramet que quiero devolver

*alert = es una fución return, que no retorna nada. Realiza una acción = mostrar texto

Todo parentesis, corchetes, comillas que se abren se tienen que cerrar. 
Si hay un bloque dentro de un código, por buena práctica, gráficamente debe estar dentro de la función que lo abre.






Clase - 12


* Condiciones

Las condiciones se usan para cerrar un ciclo, para que esta no se repita infinitamente

Ejemplo:
		Mientras    { haya comida en el plato
			y 	{ tenga hambre

	 	-cuando sí	 =   comer(plato)

		-cuando no	 =   parar de comer()
				     limpiar(plato)

* Agregar un ciclo de 3 partidas en el juego.




Clase - 13

Instrucciones: son términos nativos de lenguajes de programación que modifican el flujo del código.

(while) = Le dice a la computador que siga haciendo un ciclo mientras una condición sea verdadera.



Clase - 14

Ruta absoluta = Una dirección detallada sobre una carpeta/archivo
Posición relativa = La ubicación sola del archio/carpeta que queremos abrir/trabajar


Clase - 15

D.O.M. = Es la forma en la que el navegador estructura las etiquetas html para que se pueda manipular en código de javascript 

window = Es cada una de las pestañas del navegador. Suceden los eventos del navegador
document =  Se ejerce especificamente lo que se encuentre dentro de la etiqueta html

	botón > click > función } Escuchador de eventos

* Por buena práctica el button, debe ir dentro de un contenedor