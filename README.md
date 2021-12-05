# lecturemath



//math
#include <iostream>
#include <math.h>
using namespace std;


int main() {
	double number;

	cout << "Type any number" << endl;
	cin >> number;

	cout << "The square-root of " << number << " is " << sqrt(number) << endl;
	cout << "The cube-root of " << number << " is " << cbrt(number) << endl;

	return 0;
}
