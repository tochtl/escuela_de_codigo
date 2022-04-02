Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

Algoritmo inicio

	win<-73
	Escribir "Ingresa un numero del 1 al 100"
	Leer num1
	contador<-9
	Mientras win<>num1 Y contador>0 Hacer
		Si num1<win  Entonces
			Escribir "El numero " num1 " es menor."
 		SiNo
			Escribir "El numero " num1 " es mayor"
		Fin Si
		Escribir "Ingresa un numero del 1 al 100"
		Leer num1
		contador=contador-1
	Fin Mientras
	Si num1=win Entonces
		Escribir "Felicidades ganaste"
	SiNo
		Escribir "Lo siento perdiste"
	Fin Si
  

FinAlgoritmo

  ![image](https://user-images.githubusercontent.com/102439883/161403164-623c6ae3-7552-44c6-8be2-606d9324b1d5.png)


Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing
