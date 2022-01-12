#include<iostream>
using namespace std;
int main(){
	int num, num2;

	for (int i = 0; i < 4; i++) {
		for (int j = 0; j < 6; j++)
			cout << "*"; 
		cout << endl;
	}
	for (int i = 0; i < 7; i++) {
		for (int j = 0; j < 11; j++)
			cout << "*";
		cout << endl;
	}
	cin >> num;
	cin >> num2;
	for (int i = 0; i < num; i++) {
		for (int j = 0; j < num2; j++)
			cout << "*";
			cout << endl;
	}

}
