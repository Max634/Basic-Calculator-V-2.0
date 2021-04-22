
#include <iostream>
  using namespace std;
  int main ()
  {
  char op;
    double num1, num2;
    cout << "Enter the operator +, -, / , * ";
    cin >> op;
    cout << "Enter first number";
    cin >> num1;
    cout << "Enter second number";
    cin >> num2;
    switch (op) {
    case '+':
        cout << num1 + num2;
        break;
    case '-':
        cout << num1 - num2;
        break;
    case '*':
        cout << num1 * num2;
        break;
    case '/':
        cout << num1 / num2;
        break;
    default:
        cout << "Error !!!";
        break;
    }
    

    return 0;
}
