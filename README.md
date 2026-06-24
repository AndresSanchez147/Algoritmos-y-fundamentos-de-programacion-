# Algoritmos-y-fundamentos-de-programacion-
ejercicios 

Algoritmo 1
	
	Definir num1 Como Entero
	
	Escribir"Ingrese su número"
	Leer num1;
	
	Escribir "El doble de ese número es", num1*2;
FinAlgoritmo


Algoritmo 2
	
	
	scribir "Hola Mundo!!"
FinAlgoritmo


Algoritmo 3
	
	Definir num1 Como Entero;
	Leer num1;
	
FinAlgoritmo


Algoritmo 4
	

	Definir A Como Entero;
	
	Escribir "ingrese numero :";
	Leer A;

   

FinAlgoritmo


Algoritmo 5
	
	Definir A Como Entero;
	A=55
  

   
   FinAlgoritmo


Algoritmo 6
	
	definir a Como Entero
	definir b Como Entero
	definir c Como Entero
	definir d Como Entero
	leer a
	leer b 
	leer c
	leer d 
	num1=a + b 
	num2= c * d
	r=num1-4
	r2=r^2
	r3=r2/num2
	Escribir  r3
   FinAlgoritmo


Algoritmo 7
	
	
	Definir a Como entero
	Definir p Como Real
	p = 3.1416; 
	
	Escribir"Ingrese su radio";
	Leer a;
	
	Escribir "Su área es: " p*a^2
	
FinAlgoritmo
	


Algoritmo 8
	
    
   
	Definir a Como entero
	Definir b Como entero
	
	Escribir"Ingrese su cateto 1";
	Leer a;
	
	Escribir"Ingrese su cateto 2";
	Leer b;
	
	Escribir "Su área es: " a*b/2
    
FinAlgoritmo



Algoritmo 9
      
	Definir a , b , c , d Como Entero
	Escribir " valor de a"
	leer a
	Escribir " valor de b"
	leer b
	Escribir " valor de c"
	leer c
	Escribir " valor de d"
	leer d
	
    Escribir (a < 17) Y (b < 17)
     Escribir (a=b) y (b=c) , (b<>c );
     Escribir (a<b) Y (b<c) Y (a<d) Y (d<c)
     Escribir (a=b) O  (b=C )  O (a=c)
	
	
FinAlgoritmo


Proceso Funciones_Cadena
Algoritmo 10



Escribir "Raíz cuadrada de 9:",rc(9)
	 
	Escribir "Valor absoluto de -3: ",abs(-3)
	Escribir "Seno de 90 grados : ", sen(90*PI /180)
	Escribir "Truncamos de 3.7: ",trunc(3.7)
	Escribir "Redondeamos 2.7: ",redon(2.7)
	Escribir "Un numero al azar del 0 al 9: ", azar(10)
	Escribir "Un numero al azar entre 10 y 20: "

FinProceso

Algoritmo  11
	
		Definir cad1,cad2 como cadena;
	Definir num como Entero;
	
	cad1<-"informática";
	
	Escribir "La longitud de cad1 es ",longitud(cad1);
	
	Escribir "El primer carácter de cad1 es ",subcadena(cad1,0,0);
	
	Escribir "El último carácter de cad1 es ",subcadena(cad1,longitud(cad1)-1,longitud(cad1)-1);
	
	Escribir "La cad1 en mayúsculas es ",mayusculas(cad1);
	
	cad2<-concatenar(cad1," es muy interesante");
	
	Escribir cad2;
	
	num<-ConvertirANumero("10");
	
	Escribir num;
	
	Escribir Concatenar("El número es ",ConvertirATexto(num));
	
	Escribir "El número es ",num;
	
	
FinAlgoritmo



Algoritmo 12
	
	definir edad Como Entero
	Escribir digite su edad 
	leer edad
	si edad>17  Entonces
		Escribir "accedio
	SiNo
		Escribir "no ùede acceder a la encuesta"
		
	FinSi
	
	
FinAlgoritmo



Algoritmo 13

	definir Heidy,Julian,Kevin  Como Entero
	Escribir "digite la edad de Heidy" 
	leer Heidy
	Escribir "digite la edad de Julian" 
	leer Julian
	Escribir "digite la edad de Kevin "
	leer Kevin
	si Heidy>=18  Entonces
		Escribir "Heidy puede votar"
	SiNo
		Escribir "no puede acceder a la votacion "
		
	FinSi
	si Julian>=18  Entonces
		Escribir "Julian puede votar"
	SiNo
		Escribir "no puede acceder a la votacion "
		
	FinSi
	si Kevin>=18  Entonces
		Escribir "Kevin puede votar"
	SiNo
		Escribir "no puede acceder a la votacion "
	
FinAlgoritmo


Algoritmo 14 
	
	definir numero Como Entero
	Repetir
		leer numero 
		Escribir numero 
	Hasta Que numero ==0
	
	
	
FinAlgoritmo


Algoritmo 15

	Para i <- Hasta 10 Con Paso 1 Hacer
	Escribir 1 
	FinPara

FinAlgoritmo


Algoritmo 16

	Limpiar Pantalla
	Escribir ""
	Escribir "captura de numeros"
	Escribir ""
	Definir catNumeros Como Entero
	Escribir "cuantos numeros quieres capturar ?" Sin Saltar
	leer catNumeros
	escribir""
	definir M Como Entero
	Dimension vNumero
FinAlgoritmo
	

Algoritmo 17
	
	n<-1;
	i<-1
	Dimension numeros [n]
	Mientras i<=3 Hacer
		Escribir "introduzca un elemento", i ,"del vector numeros "
		
	FinMientras
	
	
FinAlgoritmo


Algoritmo 18

	Definir i como entero
	Repetir
		Escribir "Ingrese un número"
		Leer i
		Escribir i
		
	Hasta Que i == 0
	
	
FinAlgoritmo



Algoritmo 19

	definir i como entero
	para i<- 1 Hasta 10 Con Paso 1 Hacer
		escribir 1
	FinPara
FinAlgoritmo


Algoritmo 20

	//se define la variable i como uno
	definir i como entero
	i=2
	//se hace el ciclo for para que cuente hasta 10
	para i<- 2 Hasta 10 Con Paso 2 Hacer
		//se lee
		escribir 1
	FinPara
FinAlgoritmo


Algoritmo 21

	//se define la variable i como uno
	definir i como entero
	//se hace el ciclo for para que cuente hasta 10
	para i<- 2 Hasta 10 Con Paso +2 Hacer
		//se lee
		escribir 1
	FinPara
	Esperar Tecla //cuando el usuario le de a enter se limpie la pantalla
    Limpiar Pantalla
FinAlgoritmo


Algoritmo 22

	Definir l Como Entero
	l=0
	Para l<-0 Hasta 33 Con Paso l+3 Hacer
		
		escribir l
	FinPara
FinAlgoritmo

Algoritmo 23

	definir num , i como entero
	dimension num[5]
	num[1]<-5 
	num[2]<-10
	num[3]<-15
	num[4]<-20
	num[5]<-25
	para i hasta 5 con paso 1 Hacer
		Escribir num[1]
	FinPara
FinAlgoritmo
