# c-
#Write a C++ Program to find the product of two numbers entered by the User Your Output should look something like this Enter two numbers: 3.4 5.5 Product = 18.7

#include <iostream>
using namespace std;

int main() {
  double num1, num2, product;
  cout << "Enter two numbers: ";

  // stores two floating point numbers in num1 and num2 respectively
  cin >> num1 >> num2;
 
  // performs multiplication and stores the result in product variable
  product = num1 * num2;  

  cout << "Product = " << product;    
    
  return 0;
}
