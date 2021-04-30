# El_Patito
Algoritmo Promedio
	
	escribir "Ingrese la cantidad de datos:"
	leer n
	acum=0
	si n>0 entonces
	para i<-1 hasta n Hacer
		escribir "Ingrese el dato ",i,":"				//error corregido de n+1
		leer dato
		acum<-acum+dato
	FinPara
	SiNo
	Repetir
		escribir "No utilice números negativos"
		leer n										//no usar números negativos para la cantidad de datos
		si n<0 Entonces
		FinSi
	Hasta Que n>0
FinSi


	prom<-acum/n
	escribir "El promedio es: ",prom
	escribir "Si desea salir del ejecutor pulsar 0, si desea continuar pulse 1"
	leer orden
	si orden=1 Entonces
		escribir "Ingrese la cantidad de datos:"
		leer n
		acum=0
		si n>0 entonces
		para i<-1 hasta n Hacer
			escribir "Ingrese el dato ",i,":"
			leer dato
			acum<-acum+dato
		FinPara
	sino
		Repetir
			escribir "No utilice números negativos"
			leer n										
			si n<0 Entonces
			FinSi
		Hasta Que n>0
	FinSi
	si n>0 entonces
		para i<-1 hasta n Hacer
			escribir "Ingrese el dato ",i,":"				
			leer dato
			acum<-acum+dato
		FinPara
	FinSi
	si orden=0 Entonces
		escribir"Fin"
	FinSi
	
	prom<-acum/n
	escribir "El promedio es: ",prom
	escribir "Si desea salir del ejecutor pulsar 0, si desea continuar pulse 1"
	leer orden
	FinSi
	si orden=0 Entonces
		escribir"Fin"
	FinSi
	si orden=1 Entonces
		escribir "Ingrese la cantidad de datos:"
		leer n
		acum=0
		si n>0 entonces
			para i<-1 hasta n Hacer
				escribir "Ingrese el dato ",i,":"
				leer dato
				acum<-acum+dato
			FinPara
		sino
			Repetir
				escribir "No utilice números negativos"
				leer n										
				si n<0 Entonces
				FinSi
			Hasta Que n>0
		FinSi
		si n>0 entonces
			para i<-1 hasta n Hacer
				escribir "Ingrese el dato ",i,":"				
				leer dato
				acum<-acum+dato
			FinPara
		FinSi
	FinSi
	
	prom<-acum/n
	
	
	
	
FinAlgoritmo
