# Ovsiyenko_lab6

#include <iostream>

using namespace std;

int main() {
    
    double num = 15.5;

    double* ptr = &num;

    cout<<"Початкове значення num: "<<num<<endl;

    *ptr += 5.5; 
    cout<<"Після збільшення на 5.5 через вказівник: "<<num<<endl;

    *ptr *= 2; 
    cout<<"Після множення на 2 через вказівник: "<<num<<endl;

    *ptr /= 3; 
    cout<<"Після ділення на 3 через вказівник: "<<num<<endl;

    return 0;
}
