# Core-Code-Week-5-PseudoCode-Practice

## Challenge 1 - TiempoEnSegundos

``` python

  Funcion tiempo <- time(segundoss)
	definir dia, hora, min, seg como entero;
	dia = trunc(segundoss/84600) 
	hora = trunc(trunc((segundoss/3600))%24)
	min = trunc(trunc((segundoss/60))%(60))
	seg = segundoss%60 
	imprimir dia " dias," hora " horas," min " minutos y " seg " segundos."
  FinFuncion

  Algoritmo TiempoenSegundos
	Imprimir time(1500)
  FinAlgoritmo
  ```
  
## Challenge 2 - Distancia a Cero

``` python

	Funcion comparar <- distancia (x) 
	Imprimir "Ingrese sus numeros" 
	Para x=0 hasta 4 Con paso 1 Hacer 
	leer z
	si z>=0 entonces n=z+n
		sino t=z+t
		FinSi
	FIn Para
	Si abs(n) > abs(t) entonces 
		Imprimir "Verdadero"
		Sino Imprimir "Falso"
	FinSi
	FinFuncion

	Algoritmo Distancias
	Imprimir distancia(x)
	FinAlgoritmo
``` 

## Challenge 3 - Sum Of Pairs

``` python

	Funcion operar<-SumofPairs[x]
	Repetir 
		Imprimir "ingresa numero"
		leer x
		si x%2=0 entonces 
			n=x+n
		FinSi
		Hasta QUe x<0 | x>101
	imprimir "Número ingresado fuera del rango"
	Imprimir "Total números pares: " n
	FinFuncion
	Algoritmo SumPairs
	Imprimir SumOfPairs[x]
	FinAlgoritmo
``` 

## Challenge 4 - MidPoint

``` python

	Funcion sum <- MidPoint[x,z]
	Imprimir "ingrese numero 1"
	leer x
	Imprimir "ingrese numero 1"
	leer z
	n=((z+x)/2)
	Imprimir n
	FinFuncion
	Algoritmo PuntoMedio
	Imprimir MidPoint[x,z]
	FinAlgoritmo
```	

## Challenge 5 - Cashier

``` python
	Funcion cas <- cashier[x]
	Repetir 
	Imprimir "Select an option:" 
	Imprimir "a. to deposit." 
	Imprimir "b. withdraw." 
	Imprimir "c. go out."
	leer x
	Si mayusculas(x) == "A" entonces 
		Imprimir "How much would you like to deposit?"
		leer n
		balance = balance + n
	sino 
		si mayusculas(x) == "B" Entonces
			Imprimir "How much would you like to withdraw"
			leer n
			balance = balance - n
			fin SI 
		FinSi
		Imprimir "Saldo Actual " balance +1000
	Hasta que mayusculas(x) == "C"
	Imprimir "Gracias por la operacion, feliz día"
	FinFuncion
	Algoritmo Cash
	Imprimir cashier[x]
	FinAlgoritmo
```

## Challenge 6 - weather

``` python

	Funcion c <- weather[n]
	Repetir 
	Imprimir "Select one of the options"
	Imprimir "a. Temperature in Celsius" 
	Imprimir "b. Temperature in Farenheit" 
	Imprimir "x. Para salir del programa"
	Leer n
	w = w
	si mayusculas(n) == "A" Entonces
		Imprimir "Ingrese temperatura"
		leer a
		r= r+a
		sino 
		si mayusculas(n) == "B" Entonces
			Imprimir "Ingrese temperatura"
			leer a
			x = (a*(9/5))+32
			r = r+x
		FinSi
	FinSi
	p=p+1
	Hasta que mayusculas(n) == "X"
	promedio = r/p
	Imprimir promedio
	FinFuncion

	Algoritmo clima
	imprimir weather[n]
	FinAlgoritmo	
```

## Challenge 7 - If in JavaScript

``` Javascript

let x =10;
let y=8;
if (x>y){
    console.log("Operando Suma");
    console.log(x+y);
}
else {console.log("No se pudo")};
```

## Challenge 8 - While in JavaScript

``` Javascript

let i;
while(i<16){
    console.log(i)
    i++
}
``` 
## Challenge 9 - For in JavaScript

``` Javascript

let p;
for(p=0;p<20; p++)
{console.log(p*2)};
```
