#include<iostream>
#include<algorithm>
#include<array>
using namespace std;
int main()
{
	array<int, 10> b;
	cout << "Kindly enter 10 numbers:" << endl;
	for (int i = 0; i < 10; i++)
	{
		cin >> b[i];
	}
	sort(b.begin(), b.end()); 
	cout << endl << b[9] << " is the largest number.";
	cout << endl << b[0] << " is the smallest number.";
		return 0;
}
