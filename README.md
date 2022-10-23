# Transportation
Below is the code simple program created using the c++ language. The program represents a travel service, which only 50 people being able to be transported at once.
Furthermore, the input will serve as the amount of those who are WAITING to be transported. This program will calculate and output the amount of empty seats the last vehicle will have.

CODE IS A FOLLOWS:
#include<iostream>
using namespace std;

int main()
{

int pass;
int seats;
cin>>pass;

seats=pass%50;
cout<<50-seats;
return 0;}
