# Programacion-1-
En este programa subiremos las practicas realizadas en clase del curso de programacion I

//Ejemplo de tarea #1, Uso de "for"
//Algoritmo de los numeros del 1 al 10
//Empezamos seleccionando las librerias 
#include <iostream>
#include <conio.h>

//Habilitamos el salto de linea 
using namespace std; 

int main(){
	
	//Declaramos la variable i 
	int i;
	
	for( i=1; i<=10; i++){
		cout<<i<<endl;
	}

	 
	return 0;
}

			      
			    
			      
				      
			   		      
//Ejemplo de tarea #1, Uso de "do while"
//Algoritmo de los numeros del 1 al 20
//Empezamos seleccionando las librerias 
#include <iostream>
#include <conio.h>

//Habilitamos el salto de linea 
using namespace std; 

int main(){
    //Declaramos la variable 
	int i;
    i = 1;
	do{
		cout<<i<<endl;
		i++;//Aumenta el iterador de uno en uno
	}while(i<=10);
	
	return 0;
}
