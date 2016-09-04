# Referencia-C-
Algoritmo de retorno por referencia em C++

#include <conio2.h>
#include <iostream>
#include <iomanip>
using namespace std;

void media (int &a, int &b)
{ a = a+b;
  b = a/2;
}
int main(){
    setlocale(LC_ALL,"PTB");
    int x, y;
    cout << "   \n\n\t\t\tInforme um valor: ";
    cin >> x;
    cout<< "   \n\t\t\tInforme outro valor: ";
    cin>> y;
    media(x,y);
    cout<<"   \n\t\t\tSoma: "<<x;
    cout<<"   \n\n\t\t\tMédia: "<<y;
    getch();


}
