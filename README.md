# exer5.0
#include<iostream>
using namespace std;
int main(){
	int num1 = 0;
	int resultado = 0;
	
	cout << "digite um numero: ";
	cin >> num1;
	
	if(num1 > 20){
		resultado = num1 + 8;
		cout << resultado;	
	}else if(num1 <= 20){
		resultado = num1 - 5;
		cout << resultado;
	}
	return 0;
}
