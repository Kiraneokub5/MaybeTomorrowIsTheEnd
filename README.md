#include<iostream>
#include<math.h>

using namespace std;

int main()
{
float r1,r2,r;

cout << "magnitude one resistance (Om):";
cin >> r1;

cout << "magnitude one resistance (Om):";
cin >> r2;

r = r1+r2;
r = r1 * r2 / (r1 + r2);

if (r)
{
    cout << "resistance:" << r;
}
