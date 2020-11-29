# swapping-of-values
/*This function takes two integer type variables as parameters and interchanges their values. */
#include <iostream>
using namespace std;
void swap(int &x, int &y)
{
  int c= 0;
  c=x;
  x=y;
  y=c;
}
int main()
{
  int a,b;
  cout<<"Enter two values:";
  cin>>a>>b;
  cout<<endl;
  swap(a,b);
  cout<<a<<b;
}
