#include<iostream>
#include<conio.h>
#include<stdio.h>
using namespace std;

	void array (){
	int array [] = {10,20};
	int arraym [2][2] = {{800,700},{400,500}};
	
	char question1 [] = "your love ?";
	char *she_is[3] = {"my","mymy","mymymy"}; // depcrecated
	string name [3] = {"kurani","kumala","wati"};
	
	// sebelum array dirubah
	
	cout<<"before value change / sebelum merubah array"<<endl;
	cout<<array[0]<<endl;
	cout<<arraym[0][1]<<endl<<endl;
	
	//change array value
	
	array [0] = 9000;
	arraym [0][1] = 7500;
	
	cout<<"after value change / sesudah merubah array"<<endl;
	cout<<array[0]<<endl;
	cout<<arraym[0][1]<<endl<<endl<<endl;
	
	//memanggil nama dg array
	
	cout<<"Hi, "<<question1<<endl;
	cout<<she_is[0]<<" ";
	cout<<name[0]<<endl;
	
	
	return 0;
	
}
