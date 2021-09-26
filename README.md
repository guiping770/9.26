#include<iostream>
using namespace std; 
int F(int n)

{
    if (n==0)
    {
        return 1;
    }
    return n*F(n-1);
}
int main(){
	cout<<F(10)<<endl;
	return 0;
}

  
