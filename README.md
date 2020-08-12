# No.of-Cards-in-A-Pyramid
Total number of cards needed to build a pyramid

#include<iostream>
using namespace std;
int main()
{
  int r;
  cout<<"Enter the no.of rows:";cin>>r;
  int sum=r*2;
  while((r-1)!=0)
  {
      sum=sum+((r-1)*3);
      r--;
  }
cout<<"Total cards needed are:"<<sum;
}   
