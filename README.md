#include <iostream>
#include <string>
using namespace std;
int main()
{
	string name;
	float salary,sale,Commission_Percent;
	cout << "Enter Name : ";
	cin >> name;
	cout << "Enter Salary : ";
	cin >> salary;
	cout << "Enter Sale : ";
	cin >> sale;
    cout << "Enter Commission Percent : ";
	cin >> Commission_Percent;
	//output
	cout << "\nYour name = " << name << endl;
	cout << "Total Revenue " << ((sale*5)/100)+salary << " Bath" << endl;
	return(0);
}
