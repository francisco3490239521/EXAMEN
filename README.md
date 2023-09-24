/*regeistros(struct)
*/
#include<iostream>
#include<string.h>
#include<stdlib.h>

using namespace std;

int main (){
	struct producto{
	int id;
	string nombre;
	int existencia;
	float costo;
	string fecha;
	float precio;
	};
	producto*listaproducto=new producto[30];
	for(int i=0; i<30; i++){
	}
}
