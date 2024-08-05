# CDS-experiment-1
experiment 1 cds 


AIM :-<br>
to download and install vs code <br>
To print hello world , add , subtract  two numbers ,see if the number is even or odd and check if the year is leap or not <br>

Theroy= in this program we have printed hello world and find the sum of two number(user input), average, even odd and also to check if the entered year is leap leap or not using basic cpp language <br>

Code <br>
    
    //Vandan gupte 
    //23070123147
    //experiment 1

    #include <iostream>
    using namespace std;

    int main() {
    cout << "Hello world" << endl;

    int a, b;
    cout << "Enter the value of the first number: ";
    cin >> a;

    cout << "Enter the value of the second number: ";
    cin >> b;

    int sum = a + b;
    cout << "The sum of the two numbers is: " << sum << endl;
    
    int avg = (a + b) / 2;
    cout << "The average of the two numbers is: " << avg << endl;

    int c;
    cout << "Enter a number: ";
    cin >> c;

    if (c % 2 == 0) {
        cout << "The number is even." << endl;
    } else {
        cout << "The number is odd." << endl;
    }

    int d;
    cout << "Enter the year you want to check whether it is a leap year or not: ";
    cin >> d;

    if ((d % 400 == 0) || (d % 100 != 0 && d % 4 == 0)) {
        cout << "The year entered is a leap year." << endl;
    } else {
        cout << "The year entered is not a leap year." << endl;
    }

    return 0;
}


Conclusion:- <br>
in this experiment we learnt to use the basic syntax print hello world 
, add two numbers , find if the number is even or odd and check if the year is leap or not <br>

![exp1].(https://github.com/VandanGupte101727/CDS-experiment-1/blob/main/Screenshot%202024-07-30%20151908.png)
