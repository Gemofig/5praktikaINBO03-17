# 5praktikaINBO03-17 Петрищев Никита


#include "stdafx.h"
#include <iostream>

using namespace std;


void calc(int a, char b, int c) {
	switch (b)
	{
	case'+':cout << a << b << c << " = " << (a + c) << endl; break;
	case'-': cout << a << b << c << " = " << (a - c) << endl; break;
	case'/': cout << a << b << c << " = " << (a / c) << endl; break;
	case'*': cout << a << b << c << " = " << (a * c) << endl; break;
	default: cout << "Error" << endl;
	}
}
void calc(float a, char b, float c) {
	switch (b)
	{
	case'+':cout << a << b << c << " = " << (a + c) << endl; break;
	case'-': cout << a << b << c << " = " << (a - c) << endl; break;
	case'/': cout << a << b << c << " = " << (a / c) << endl; break;
	case'*': cout << a << b << c << " = " << (a * c) << endl; break;
	default: cout << "Error" << endl;
	}
}
int main() {
	setlocale(0, "");
	char q;
	float b, w;
	cout << "Первое число : ";
	cin >> b;
	cout << "Знак(+,-,/,*) : ";
	cin >> q;
	cout << "Второе число :";
	cin >> w;
	calc(b, q, w);
	system("pause");
	return 0;
}
