# Algoritmos-y-fundamentos-de-programacion-
ejercicios 

Algoritmo 1
	Definir num1 Como Entero
	
	Escribir"Ingrese su número"
	Leer num1;
	
	Escribir "El doble de ese número es", num1*2;
FinAlgoritmo


Algoritmo 2
	Escribir "Hola Mundo!!"
FinAlgoritmo


Algoritmo 3
	Definir num1 Como Entero;
	Leer num1;
FinAlgoritmo


Algoritmo 4
	Definir num1 Como Entero;
	num1 = 5;
FinAlgoritmo


Algoritmo 5
	Definir a Como entero
	Definir b Como entero
	Definir c Como entero
	Definir d Como entero

	Escribir"Ingrese su número";
	Leer a;
	
	Escribir"Ingrese su segundo número";
	Leer b;
	
	Escribir"Ingrese su tercer número";
	Leer c;
	
	Escribir"Ingrese su cuarto número";
	Leer d;
	
	Escribir "Su resultado es " [(a+b)-4]^2/(c*d)
FinAlgoritmo


Algoritmo 6
	Definir a Como entero
	Definir b Como entero
	
	Escribir"Ingrese su cateto 1";
	Leer a;
	
	Escribir"Ingrese su cateto 2";
	Leer b;
	
	Escribir "Su área es: " a*b/2
FinAlgoritmo


Algoritmo 7
	Definir a Como entero
	Definir p Como Real
	p = 3.1416; 
	
	Escribir"Ingrese su radio";
	Leer a;
	
	Escribir "Su área es: " p*a^2
	


Algoritmo 8
	
	Definir A Como Entero
	Definir b Como Entero
	Definir c como entero 
	
	Escribir "INGRESE A";
	
	LEER A 
	
	ESCRIBIR "INGRESE B" 
	
	LEER B 
	
	SI (A < 17) Y (B < 17) Entonces
		Escribir "VERDADERO"
	SINO	
	Escribir "FALSO"
	FinSi
FinAlgoritmo

FinAlgoritmo

	
FinAlgoritmo



lgoritmo 9
	Escribir "Raíz cuadrada de 9:",rc(9)
	Escribir "Valor absoluto de -3: ",abs(-3)
	Escribir "Seno de 90 grados : ", sen(90*PI /180)
	Escribir "Truncamos de 3.7: ",trunc(3.7)
	Escribir "Redondeamos 2.7: ",redon(2.7)
	Escribir "Un numero al azar del 0 al 9: ", azar(10)
	Escribir "Un numero al azar entre 10 y 20: "
	
FinAlgoritmo


Proceso Funciones_Cadena 10



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

FinProceso
