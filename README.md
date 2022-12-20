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
  
