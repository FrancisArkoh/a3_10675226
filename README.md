# a3_10675226
assignment 2
#include <iostream>
using namespace std;
int gcf(int a,int b);
int main()
{
    int num1,num2,gcf;
    cout << "\n\n GREATEST COMMON FACTOR:\n";
    cout << "-----------------------------\n";
    cout << " Input the first number: ";
    cin >> num1;
    cout << " Input the second number: ";
    cin >> num2;

    for (int i = 1; i <= num1 && i <= num2; i++)
    {
        if (num1 % i == 0 && num2 % i == 0)
        {
            gcf = i;
        }
    }
    cout << " The Greatest Common Factor is: " << gcf << endl;
    return 0;
}
