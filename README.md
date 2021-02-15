# Lab-17.20-
#include <iostream>
using namespace std;

//	*********************************************************************
//	half
//
//	task:	  This function takes a quantity and returns half its value
//	data in:  the value to halve (double)
//	data out: the input divided by 2 (double)
//	********************************************************************
double half(double quantity)
{
	return quantity / 2.0;
}

int main() {
  double number, result;

	cout << endl << "Please input a number to half" << endl;
	cin >> number;

	cout << endl << endl;

	result = number/2.0;
  return result;
  // Fill in the code to pass the variable number to the half function and 
	// assign its return value to the variable result.
	
	cout << "Half of your number is " << result;
}
