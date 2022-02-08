#include <iostream>
using namespace std;

int power(int, int);

int main()
{
    int base, exponent, result;

    cout << "Enter base number: ";
    cin >> base;

    cout << "Enter an exponent: ";
    cin >> exponent;

    result = power(base, exponent);
    cout << base << "^" << exponent << " = " << result;

    return 0;
}

int power(int base, int exponent)
{
    if (exponent != 0)
        return (base*power(base, exponent-1));
    else
        return 1;
}
