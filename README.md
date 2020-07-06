# Function_sum_c-
C++ program to add two nos. using function
#include<iostream>
using namespace std;
int add (int,int);
int main()
{
	int a,b, sum;
	cout<<"enter the two values:";
    cin>>a>>b;
    sum = add(a,b);
    cout<<"sum:"<<sum;
    return 0;
}
int add (int x,int y)
{
	
	return(x+y);
}
