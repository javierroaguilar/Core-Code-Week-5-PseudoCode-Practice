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
