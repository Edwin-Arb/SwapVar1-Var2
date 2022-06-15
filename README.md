#include<iostream>
using namespace std;

void Swap(int *a, int *b)
{
	int temp = *a;
	*a = *b;
	*b = temp;
}
void main()
{
	setlocale(LC_ALL, "ru");
  
	int var1 = 43;
	int var2 = 67;

	cout << "var1\t" << var1 << endl;
	cout << "var2\t" << var2 << endl;

	cout << "Swap " << endl;
	Swap(&var1, &var2);

	cout << "var1\t" << var1 << endl;
	cout << "var2\t" << var2 << endl;
}
