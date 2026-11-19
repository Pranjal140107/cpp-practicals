[all.cpp](https://github.com/user-attachments/files/35096916/all.cpp)

#include <iostream>
using namespace std;
int main()
{
    int num1, num2;
    const int bonus = 10;
    int sum;
    cout << "Enter first number: ";
    cin >> num1;
    cout << "Enter second number: ";
    cin >> num2;
    sum = num1 + num2 + bonus;
    cout << "\nSum = " << sum << endl;
    cout << "Is sum greater than 50?"
         << (sum > 50) << endl;
    cout << "Are both numbers positive? "
         << (num1 > 0 && num2 > 0) << endl;
    cout << "\nFirst Number: " << num1;
    cout << "\nSecond Number: " << num2;
    cout << "\nConstant Bonus: " << bonus;
    cout << "\nFinal Result: " << sum << endl;
    return 0;
}
