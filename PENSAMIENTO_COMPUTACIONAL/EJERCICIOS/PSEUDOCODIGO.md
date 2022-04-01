
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




6. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
7. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.
8. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
