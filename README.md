# Core-Code-Practice-Sessions-2-Challenges

## Challenge 1 - Logic Problem

    Alice - Nobody studied
    Bob - 1 studied
    Charlie - 2 studied
    Dan - 3 studied
    Eva - 4 studied
    
    If Alice tells the truth, and nobody studied, that means she did study. So that could not be possible 
    If Bob is telling the truth, he did studied, and that means 1 person studied. 
    If Charlie tells the truth, then he did studied but someone else has to study too, and that would mean that someone else has to tell the truth also. But if someone else is telling the truth then the Charlie's statement wouldn't be logical. By definition the next statements wouldn't be logical either. 
    Bob is the one that is telling the truth. 
    
## Challenge 2 - Milk & Cereal 

    1. Sacar el tazón y la caja de cereal
    2. Sacar el bote de leche de la refrigeradora
    3. Verter la leche en el tazón.
    4. Verter el cereal en el tazón con la leche
    5. Tomar el cereal
    
    PseudoCode
    Sacar tazon;
    Sacar cereal;
    Sacar leche;
    Insert leche into tazon;
    Insert cereal into tazon;
    Comer cereal; 
    
    ![image](https://user-images.githubusercontent.com/116524723/204697363-1d744299-145a-48a7-95d9-b0409e7aa282.png)
    
## Challenge 3 - Print My Name

``` python

    Algoritmo PrintMyName
	Imprimir "Javier Aguilar";
    FinAlgoritmo
```

## Challenge 4 - Print My Name & Age


``` python

    Algoritmo PrintMyNameAndAge
	Imprimir "Javier Aguilar";
    Imprimir 27;
    FinAlgoritmo
```
        
## Challenge 5 - Game 

        ![image](https://user-images.githubusercontent.com/116524723/204708972-dddb967b-3c92-4763-b24b-10323939cfbf.png)
        
## Challenge 6 - Mod 

``` python
        
    Algoritmo ParoImpar
    Leer x;
    Imprimir "El número ingresado por tu parte es " x;
    Imprimir "Y la respuesta a la operación solicitada es " (x%2);
    FinAlgoritmo
```

## Challenge 7 - Registro

``` python

    Algoritmo PrintMyName
	Imprimir "Bienvenido al registro de datos de Javier Aguilar"
	Imprimir "Para iniciar por favor marcar 1, para salir marcar 2";
	Leer x; 
	Si x=1 Entonces 
		Imprimir "Ingrese su primer nombre"; 
		Leer nombre; 
		Imprimir "Ingrese su apellido";
		Leer apellido;
		Imprimir "Ingrese su edad";
		Leer edad;
		Imprimir "Por favor ingrese el correo electronico dónde desea recibir información";
		Leer correo; 
		Imprimir "Por favor ingrese su dirección";
		Leer address; 
		Imprimir "Gracias por enviar su información, la hemos registrado por usted." 
		Imprimir "Por favor revise que los datos sean correctos a continuación";
		Imprimir nombre + " " + apellido; 
		Imprimir edad; 
		Imprimir correo;
		Imprimir address;
		Sino Imprimir "usted ha finalizado el registro";
	FinSi

    FinAlgoritmo
```

## Challenge 8 - Truth Tables

 	1.  T & T = T ✅
 	2.  T & F = F ✅
 	3.  F & T = T ❌
 	4.  F & F = F ✅
 	5.  T | T = T ✅
 	6.  T | F = F ❌
 	7.  F | T = T ✅
 	8.  F | F = F ✅
 	9.  ~T = T ❌
 	10. ~F = T ✅
 	11. (T & F) | (~F) = T ✅
 	12. (T | F ) & (F | F) = T ❌
 	13. ~((T | F ) & (F | F)) & F = T ?
 	14. ~((T | F ) & (F | F)) & T = F ?
	
## Challenge 9 - Boolean Results 

``` python

	Algoritmo boolean
	a <- 5 == 3
	// La variable "a" es el resultado de la operación "5 es igual a 3", por lo tanto es falso
	b <- 4 <> 3
	// La variable "b" es el resultado de la comprobación "4 no es igual a 3", por lo tanto es verdadero
	c <- 7 > 7
	// La variable "c" es el resultado de la comprobación de "7 es mayor que 7", por lo tanto es falso
	d <- 4 < 4 
	// La variable "d" es el resultado de la comprobación de "4 es menor que 4", por lo tanto es falso
	e <- 100 <= 90
	// La variable "e" es el resultado de la comprobación de "100 es menor o igual que 90", por lo tanto es falso
	f <- 40 >= 40
	// La variable "f" es el resultado de la comprobación "40 es mayor o igual que 40", por lo tanto es verdadero
	FinAlgoritmo
	
```

## Challenge 10 - Par o Impar 
	
``` python
	Algoritmo Ejercicio10
	Imprimir "Por favor ingrese un número"
	Leer x; 
	Si x%2=0 entonces 
		Imprimir "El número ingresado es par"
	Sino 
		Imprimir "El número es impar"
	FinSi
	FinAlgoritmo
```
