# WSQ09---Factorial
This is the code for the WSQ09 Factorial Calculator

#include <iostream> 
using namespace std;

long factorial (long n)
{
  long f=1;
  for(int i=1;i<=n;i++)
  {
    f=f*i;
  }
  return f;
}
int main()
{
  int x;
  cout<<"Please introduce a number in which you wantthe factorial number of: ";
  cin>> x;
  int y = factorial(x);
  cout<<"The Factorial number of "<<x<<" is "<<y;
  return 0;
}

