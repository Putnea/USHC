#include<iostream>
#include<iomanip>
using namespace std;
void U(int n)//n:size
{
	for (int i = 0; i < n-1; i++)
		cout << '*' << setw((n-1)*4-1) << ' ' << '*' << endl << endl;
	for (int i = 0; i < n; i++)
		cout << "*   ";
	cout << endl << endl << endl;
}
void S(int n)
{
	cout << "   ";
	for (int i = 0; i < n-1; i++)
		cout << "*  ";
	for (int i = 0; i < n-2; i++)
		cout << '*' << endl;
	cout << "   ";
	for (int i = 1; i < n; i++)
		cout << "*  ";
	cout << endl;
	for (int i = 0; i < n-2; i++)
		cout << setw(n*3+1)<<' '<< '*' << endl;
	for (int i = 0; i < n; i++)
		cout << "*  ";
	cout << endl << endl << endl;
}
void H(int n)
{
	for (int i = 0; i < (n-1)/2; i++)
		cout << '*' << setw((n-1)*4-1) << ' ' << '*' << endl << endl;
	for (int i = 0; i < n; i++)
		cout << "*   ";
	cout << endl << endl;
	for (int i = 0; i < (n-1)/2; i++)
		cout << '*' << setw((n-1)*4-1) << ' ' << '*' << endl << endl;
	cout << endl << endl;
	cout << "   ";
	for (int i = 0; i < n-1; i++)
		cout << "*  ";
	cout << endl << endl;
}
void C(int n)
{
	for (int i = 0; i < n-1; i++)
		cout << '*' << endl << endl;
	cout << "   ";
	for (int i = 0; i < n-1; i++)
		cout << "*  ";
}
int main()
{
	int n;//size
	do {
		cout << "Nhap kich thuoc(>=5): ";
		cin >> n;
	} while (n < 5);
	cout << "WELCOME TO THE\n";
	U(n), S(n), H(n), C(n);
	return 0;
}
