# Core-Code-Week-5-PseudoCode-Practice

python
## Challenge 1 - TiempoEnSegundos

  Funcion tiempo <- time(segundoss)
	definir dia, hora, min, seg como entero;
	dia = trunc(segundoss/84600) 
	hora = trunc(trunc((segundoss/3600))%24)
	min = trunc(trunc((segundoss/60))%(60))
	seg = segundoss%60 
	imprimir dia " dias," hora " horas," min " minutos y " seg " segundos."
  FinFuncion

  Algoritmo TiempoenSegundos
	Imprimir time(150)
  FinAlgoritmo
  
