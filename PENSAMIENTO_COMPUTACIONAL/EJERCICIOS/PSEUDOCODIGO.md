
Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.
1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

  Inicio

	  Escribir ("Escribe un numero a multiplicar por 9 : ")
  
	  Leer (numero1)
  
	  resultado<- (numero1 * 9)
  
	  Escribir ("El resultado es: " resultado)
  
  Fin

![image](https://user-images.githubusercontent.com/102439883/160260575-7a8c394d-cc33-4ccb-a009-ce4d9270b426.png)

2. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”. 

Inicio

	  Escribir "Escribe el numero a sumar: "
    
    Leer num1
    
  	contador<-1
    
		Mientras contador <= 10 Hacer
    
			resultado<-resultado + num1
      
			contador<-contador + 1
      
			Escribir "Escribe el numero a sumar: "
      
			Leer num1
      
		Fin Mientras
		
	Escribir "El resultaod es :" resultado
	
Fin

![image](https://user-images.githubusercontent.com/102439883/160261235-1d7aa8bf-a51a-496e-b4d9-984fd372be04.png)

3. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

Inicio

	Escribir "Ingresa la primera calificación:"
	
	Leer cal1
	
	Escribir "Ingresa la segunda calificación:"
	
	Leer cal2
	
	Escribir "Ingresa la tercera calificación:"
	
	Leer cal3
	
	Escribir "Ingresa la cuarta calificación:"
	
	Leer cal4
	
	promedio<-(cal+cal2+cal3+cal4)/4
	
	Si promedio>6 Entonces
	
		Escribir "Feliciidades haz aprobado"
		
	SiNo
	
		Escribir "Lo siento haz reprobado"
		
	Fin Si

Fin

![image](https://user-images.githubusercontent.com/102439883/161349887-b26c9915-523e-43d8-aa2a-845f22320b63.png)

4. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

Inicio

	Escribir "Escribe una letra: "
	
	Leer letra1
	
	Si num1 %2 ==0 Entonces
	
		Escribir "El numero " num1 " es par"
		
	SiNo
	
		Escribir "El numero " num1 " es impar"
		
	Fin Si

![image](https://user-images.githubusercontent.com/102439883/161349998-39e0392a-c238-42b9-b1c4-e8c333641c31.png)

5. Un programa que pida una letra y detecte si es una vocal.

Inicio

	Escribir "Escribe una letra: "
	
	Leer letra1
	
	Segun letra1 Hacer
	
		"A":
		
			Escribir "vocal"
			
		"E":
		
			Escribir "vocal"
			
		"I":
		
			Escribir "vocal"
			
		"O":
		
			Escribir "vocal"
			
		"U":
		
			Escribir "vocal"
			
		De Otro Modo:
		
			Escribir "consonante"

	Fin Segun
	
Fin

![image](https://user-images.githubusercontent.com/102439883/161350644-1c8ee697-77d3-495b-9966-667a115f76b8.png)

6. Programa que pida 3 números y los muestre en pantalla de menor a mayor.

Inicio

	Escribir "Escribir tres numero: "
	
	Leer num1, num2, num3
	
	Si (num1>num2) Y (num1>num3) Entonces
	
		may<-num1
		
		Si num2>num3 Entonces
		
			inter<-num2
			
			men<-num3
			
		SiNo
		
			inter<-num3
			
			men<-num2
			
		Fin Si
		
	SiNo
	
		men<-num1		
		
	Fin Si
	
	Si (num2>num1) Y (num2>num3) Entonces
	
		may<-num2
		
		Si num1>num3 Entonces
		
			inter<-num1
			
			men<-num3
			
		SiNo
		
			inter<-num3
			
			men<-num1
			
		Fin Si
		
	SiNo
	
		men<-num2
		
	Fin Si
	
	Si (num3>num1) Y (num3>num2) Entonces
	
		may<-num3
		
		Si num1>num2 Entonces
		
			inter<-num1
			
			men<-num2
			
		SiNo
		
			inter<-num2
			
			men<-num1
			
		Fin Si
		
	SiNo
	
		men<-num3
		
	Fin Si
	
	Escribir "Mayor "  may 
	
	Escribir "Intermedio " inter
	
	Escribir "Menor " men
Fin

![image](https://user-images.githubusercontent.com/102439883/161352657-35eea5b4-7dcb-4b6b-9d48-a1f759bb4bdc.png)


7. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.

Inicio

	Escribir "Escribe nombre"
	
	Leer nombre
	
	Escribir "Escribe numero"
	
	Leer numer
	
	Para numer<-1 Hasta numer Con Paso 1 Hacer
	
		Escribir nombre
		
	Fin Para

Fin

![image](https://user-images.githubusercontent.com/102439883/161353354-36f185be-34ae-4670-b90d-27482af09245.png)

8. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.

Inicio
	
	Escribir "Escribe un mumero"
	
	Leer num1
	
	Mientras num1>0 Hacer
	
		resultado<-resultado+num1
		
		contador<-contador+1
		
		Escribir "Escribe un mumero"
		
		Leer num1
		
	Fin Mientras
	
	Escribir "La suma es " resultado

Fin

![image](https://user-images.githubusercontent.com/102439883/161398423-3bb8c815-6d5b-4198-bfc1-96654f165b0c.png)

