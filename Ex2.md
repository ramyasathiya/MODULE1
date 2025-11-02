# Ex.No2
# Ex.Name:Write a program in C++ to convert temperature in Fahrenheit to Celsius using class methods(define member as private & define methods within class)
## Date: 08-09-2025
## Aim:
To write a C++ program that converts temperature from Celsius to Fahrenheit using class concepts with private data members and methods defined inside the class.

## Algorithm:
1.Start the program.

2.Define a class conversion with private data members c (Celsius) and f (Fahrenheit).

3.Initialize Celsius value through a constructor.

4.Define a member function conv() inside the class to calculate Fahrenheit using the formula: F=(C*9/5)+32

5.Display the Celsius and Fahrenheit values and then stop the program.

## Program:
```
#include <iostream>
using namespace std;
class conversion{
    private:
    float c,f;
    public:
    conversion(float ce){
        c = ce;
    }
    float conv(){
        f = (c*9/5) + 32;
        return f;
    }
    
};
int main(){
    float ce;
    cin >> ce;
    conversion obj(ce);
    cout << "The temperature in Celsius:" << ce << endl;
    cout << "The temperature in Fahrenheit:" << obj.conv() << endl;
}
```
## Output:

<img width="1186" height="412" alt="image" src="https://github.com/user-attachments/assets/347dd07a-fa2a-4ac8-b324-049e4b31462b" />


## Result:
Thus the program in C++ to convert temperature in Fahrenheit to Celsius using class methods(define member as private & define methods within class) has been executed successfully.
