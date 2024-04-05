# Practical-4-1-
#include <iostream>
using namespace std;

void sort(int &a, int &b) {
    int temp = a;
    a = b;
    b = temp;
}

int main() {
    int num1;
    int num2;

    cout<<"Enter First no :";
    cin>>num1;

    cout<<"Enter Second no :";
    cin>>num2;

    cout << "Before the sort: " << endl;
    cout << num1 << " " << num2 << endl;

    sort(num1, num2);

    cout<< "After the sort : " << endl;
    cout << num1 << " " << num2 << endl;

    return 0;
}
