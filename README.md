# Repositorio_TorresRama_Juan
Primer repositorio creado en GitHub
// Calcula el promedio de una lista de n datos

Algoritmo Promedio
	
	Escribir "Ingrese la cantidad de datos:"
	Leer n
	
	acum<-0
	
	Para i<-1 Hasta n Hacer
		Escribir "Ingrese el dato ", i,":" 
		Leer dato
		mientras dato<0 
			escribir "El dato ingresado no es positivo, ingrese un numero positivo" 
			leer dato
		FinMientras
		
		acum<-acum+dato 
	FinPara
	
	prom<-acum/n
	
	Escribir "El promedio es: ",prom
	
FinAlgoritmo
