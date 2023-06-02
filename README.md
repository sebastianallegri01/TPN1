#include <bits/stdc++.h>
using namespace std;
int contarletra(string f){
	int contador;
	for(int i=0;i<f.size();i++){
		if(f[i]=='a'|| f[i]=='e'||f[i]=='i'||f[i]=='o'||f[i]=='u'){
			contador++;
		}
		
	}
	return contador;
}
int main(){
	
	 string f;
	 int resultado;
	 cout<<"ingrese una frase: "<<endl;
	 getline(cin,f);
	 
	 resultado=contarletra(f);
	 
	 cout<<"la cantidad de vocales es de: "<<resultado;
	 
	 return 0;
	 
}
