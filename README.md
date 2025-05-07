#include <iostream>
using namespace std;

int main() {
	setlocale(LC_ALL, "Russian");
	int n, k, num;
	cout << "число учинеков: ";
	cin >> n; 
	cout << "количество яблок: ";
	cin >> k; 
	num = k / n;
	cout << "У каждого ученика есть " << num <<"яблок"; 
	system ("pause > nul");
	return 0;
}
