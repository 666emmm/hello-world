#include<iostream>
using namespace std;
void max(int x,int y)
{
	if(x<y)
		x=y;
	cout<<y<<endl;
}
void max(int x,int y,int z)
{
	if(x<y)
		x=y;
	if(x<z)
        x=z;
	cout<<x<<endl;
}

int main()
{
	void sort(int &i,int &j,int &k);
	int a,b,c;
	cin>>a>>b>>c;
	max(a,b);
    max(a,b,c);
	cout<<a<<" "<<b<<" "<<c<<endl;
    return 0;
}
void sort(int &i,int &j,int &k)
{ 
	void change(int &x,int &y);
	if(i>j) change(i,j);
	if(i>k) change(i,k);
	if(k>j) change(k,j);
	
}
void change(int &x,int &y)
{
	int q;
	q=x;x=y;y=q;
}

