# Ex.No:1
# Ex.Name:Write a C++ Program to read two sequence of character  value from the keyboard and display the value on the monitor?
## Date:
## Experiment No: 1 — Constructor Overloading in C++ (Polynomial Equation Display)
## AIM

To write a C++ program to display polynomial equations using constructor overloading by passing coefficients during compile time.

Here is the **summarized algorithm** with step numbers:

---

## ALGORITHM

1. Start the program.
2. Define a class `Polynomial` with necessary data members.
3. Overload two constructors for:

   * Two-term polynomial (ax + b)
   * Three-term polynomial (ax² + bx + c)
4. Create objects in `main()` and pass coefficients during compile time.
5. Display both polynomial equations.
6. End the program.



## PROGRAM
```
#include<iostream>
using namespace std;

class Polynomial {
    int a, b, c;

public:
    // Constructor for 2-term polynomial
    Polynomial(int x, int y) {
        a = x;
        b = y;
        cout << a << "x + " << b << endl;
    }

    // Constructor for 3-term polynomial
    Polynomial(int x, int y, int z) {
        a = x;
        b = y;
        c = z;
        cout << a << "x^2 + " << b << "x + " << c << endl;
    }
};

int main() {
    Polynomial p1(95, 64);
    Polynomial p2(22, 28, 21);
    return 0;
}
```
## OUTPUT
<img width="1183" height="276" alt="image" src="https://github.com/user-attachments/assets/84cc27cb-e1aa-4203-9271-c8524ec139b0" />

## RESULT

Thus, the C++ program to display polynomial equations using constructor overloading was executed and verified successfully.
