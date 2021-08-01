#include<iostream>
using namespace std;
main()
{
	double t;
	t=0;
	int n,i,m;
	m=1;
	cout<<"Nhap n: ";
	cin>>n;
	if(n>0)
		for(i=1;i<=n;i++)
	{
		m=m*i;
		t=t+1.0/m;
	}
	else
		{
		cout<<"N khong phai nguyen duong nhap lai: ";
		cin>>n;
	}
	cout<<"ket qua la: "<<t;
	return 0;
	}
