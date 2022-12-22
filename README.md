#include <iostream>

using namespace std;



int main(){
	
	double  sales;
	cout<<"Enter your total sales ($)"<<endl;
	cin>>sales;
	
	double myTaxrate;
	cout << "Enter my tax rate (%)"<<endl;
 	cin>>myTaxrate;	
	
	double profits;
	cout <<"Include profit Earned"<<endl;
	cin>> profits;
	
	double myTax = ( myTaxrate / 100 ) *  sales;
	cout<<"Tax = $ "<<myTax<<endl<<endl;
	
	double dailySpend;
	cout<<"Enter your daily expenses"<<endl;
	cin>>dailySpend;
	
	
	 double totalMonthlysales =sales - (myTax + (dailySpend * 30)) + profits ;
	 cout<<"T.M.S = $"<< totalMonthlysales<<endl;
	


	return 0;
}
